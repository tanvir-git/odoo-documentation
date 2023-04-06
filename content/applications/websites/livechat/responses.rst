=============================
Commands and canned responses
=============================

In the Odoo *Live Chat* application, *commands* allow the user to perform specific actions both
inside the chat window, and through other Odoo applications. The *Live Chat* app also includes
*canned responses*. These are customized, pre-configured substitutions that allow users to replace
shortcut entries in place of longer, well-thought out responses to some of the most common questions
and comments.

Both commands and canned responses save time, and allow users to maintain a level of consistency
throughout their conversations.

Execute a command
=================

Live chat *commands* are keywords that triggers pre-configured actions. When a live chat *operator*
is participating in a conversation with a customer or visitor, they can execute a command by typing
`/` followed by the command.

Commands, and the resulting actions, will only be visible in the conversation window for a live chat
operator. A customer will not see any commands entered on their end of the chat.

.. image:: responses/responses-ticket-link.png
   :align: center
   :alt: View of the chat window with a helpdesk ticket created in Odoo Live Chat.

More information about each available command can be found below.

Help
----

If an operator types `/help` in the chat window, an informative message that includes the potential
entry types an operator can make is displayed.

.. image:: responses/responses-help.png
   :align: center
   :alt: View of the message generated from using the /help command in Odoo Live Chat.

.. seealso::
  - :doc:`/applications/productivity/discuss/overview/get_started`
  - :doc:`/applications/productivity/discuss/overview/team_communication`

Helpdesk & Helpdesk search
--------------------------

The `/helpdesk` and `/helpdesk_search` commands allow operators to both create helpdesk tickets
directly from a conversation, and search through existing tickets by keyword or ticket number.

.. important::
   The `/helpdesk` and `/helpdesk_search` commands can only be used if the *Helpdesk* app has been
   installed, and *Live Chat* has been activated on a *Helpdesk Team*. To activate :guilabel:`Live
   Chat`, go to :menuselection:`Helpdesk application --> Configuration --> Teams`, and select a
   team. Scroll to the :guilabel:`Channels` section and check the box labeled :guilabel:`Live Chat`.

Create a ticket from a live chat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If an operator types `/helpdesk` in the chat window, the conversation is used to create a *Helpdesk
Ticket*.

After entering the `/helpdesk` command, select a title for the ticket and type it into the chat
window, then press `Enter`.

.. image:: responses/helpdesk.png
   :align: center
   :alt: View of the results from a helpdesk search in a Live Chat conversation.

The newly created ticket will be added to the *Helpdesk* team that has live chat enabled. If there
is more than one team with live chat enabled, the ticket will automatically be assigned based on the
team's priority.

The transcript from the conversation will be added to the new ticket, under the
:guilabel:`Description` tab.

To view the new ticket, click on the link in the chat window, or go to :menuselection:`Helpdesk app`
and click the :guilabel:`Tickets` button on the kanban card for the appropriate team.

Search for a ticket from a live chat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If an operator types `/helpdesk_search` in the chat window, they can search through *Helpdesk*
tickets by ticket number or keyword.

After entering the `/helpdesk_search` command, type a keyword or ticket number, then press `Enter`.
If a related ticket is found, a link will be generated in the conversation window.

.. image:: responses/helpdesk-search.png
   :align: center
   :alt: View of the results from a helpdesk search in a Live Chat conversation.

History
-------

If an operator types `/history` in the chat window, it will generate a list of the most recent pages
the visitor has viewed on the website (up to 15).

.. image:: responses/responses-history.png
   :align: center
   :alt: View of the results from a /history command in a Live Chat conversation.

Lead
----

By typing `/lead` in the chat window, an operator can create a *Lead* in the *CRM* application.
After typing `/lead`, create a title for this new lead, then press `Enter`.

.. image:: responses/responses-lead.png
   :align: center
   :alt: View of the results from a /lead command in a Live Chat conversation.

The `/lead` command can only be used if the *CRM* app has been installed. To access the lead, click
on the link in the chat window, or navigate to the :menuselection:`CRM app` to view the
:guilabel:`Pipeline`.

The transcript of the conversation is added to the :guilabel:`Internal Notes` tab of the lead form.
On the :guilabel:`Extra Information` tab of the lead form, the :guilabel:`Source` will be listed as
:guilabel:`Livechat`.

Leave
-----

If an operator types `/leave` in the chat window, they can automatically exit the conversation.

.. seealso::
   - :doc:`/applications/sales/crm/acquire_leads`
   - :doc:`/applications/services/helpdesk/overview/getting_started`

Canned responses
================

*Canned responses* are customizable inputs where a *shortcut* stands in for a longer response. An
operator will enter the shortcut, and it will automatically be replaced by the expanded
*substitution* response in the conversation.

Create canned responses
-----------------------

To create a new canned response, go to :menuselection:`Live Chat app --> Configuration --> Canned
Responses --> New`.

From here, choose a :guilabel:`Shortcut` and enter it into the :guilabel:`Shortcut` field.

Then, click into the :guilabel:`Substitution` field, and enter the custom message that will be sent
to visitors in place of the :guilabel:`Shortcut`. Click :guilabel:`Save`.

.. tip::
   Try to connect the :guilabel:`Shortcut` to the topic of the :guilabel:`Substitution`. The easier
   it is for the *operators* to remember, the easier it will be to use the *canned responses* in
   conversations.

Use canned responses in a live chat conversation
------------------------------------------------

To use a canned response during a live chat conversation, type a colon (`:`)  into the chat window,
followed by the shortcut.

.. example::
   An operator is chatting with a visitor. As soon as they type `:` they would see a list of
   available responses. They can manually select one from the list, or continue to type. If they
   want to use the canned response `'I am sorry to hear that.'`, they would type `:sorry`.

.. image:: responses/canned-responses.png
   :align: center
   :alt: View of a chat window and the use of a canned response in Odoo Live Chat.

.. tip::
   Typing `:` into a chat window on its own will generate a list of available canned responses.
   Responses can be manually selected from the list, in addition to the use of shortcuts.

   .. image:: responses/response-list.png
      :align: center
      :alt: View of a chat window and the list of available canned responses.
