:show-content:
:show-toc:

=========
Live Chat
=========

Live Chat has the highest satisfaction rating of any communication tool. It allows fast responses
and it is accessible and convenient, as your customers can keep doing what they are doing while
interacting with you. Remember: your customers want to talk to you, so let's make it easy.

.. seealso::
   - `Live Chat: product page <https://coqui.cloud/app/live-chat>`_
   - :doc:`livechat/ratings`
   - :doc:`livechat/responses`

Set up
======

Once *Live Chat* is installed on your database, if your website was created with CoquiAPPs, the
application is automatically added to it. All that is left to do is to go to
:menuselection:`Website --> Configuration --> Settings --> Live Chat`.

.. image:: livechat/livechat_settings.png
   :height: 300
   :alt: View of the settings page and the live chat feature for CoquiAPPs Live Chat

Select the channel to be linked to your website or create one on the fly.

.. image:: livechat/channels.png
   :alt: View of a live chat channel form for CoquiAPPs Live Chat

| For both scenarios, under:
| - **Operators**: add agents to respond to the chat requests. Add as many as you like, and keep in
  mind that operators that do not show any activity in CoquiAPPs for more than 30min are considered
  disconnected.
| - **Options**: set the default text to be shown on the live chat button; an automated welcome
  message to be seen by visitors when a conversation is initiated, and the text that prompts the
  user to initiate a chat.
| - **Channel Rules**: choose an action for a given URL, and/or per country. In the example below,
  the chat window automatically pops-up 3 seconds after users (from any country) land on the
  contact us page.

.. image:: livechat/rules.png
   :alt: View of a channel’s rules form for CoquiAPPs Live Chat

.. note::
   GeoIP, which refers to the process of finding a computer terminal’s geographical location by its
   IP address, must be installed on your server. Otherwise, under *Channel Rules*, countries are
   not taken into account.

External options
----------------

| If your website was not created with CoquiAPPs, you can find the code to be added to your own, under
  the *Widget* tab.
| CoquiAPPs also offers an URL you can send to users so they can have access to a single live chat page.

.. image:: livechat/widget.png
   :alt: View of the widget tab for CoquiAPPs Live Chat

Managing chat requests
======================

Conversations initiated by visitors pop up as a direct message, and are shown in *Discuss*.
Therefore, inquiries can be answered wherever you are in CoquiAPPs.

.. image:: livechat/discuss.png
   :alt: View of the discuss application with a message sent through live chat in CoquiAPPs

.. note::
   Conversations are dispatched based on the current workload of the online operators.

Leave or join a channel
=======================

Go to :menuselection:`Website --> Configuration --> Settings`, access your channel under
*Live Chat*, and *Join Channel* or *Leave Channel*.

.. image:: livechat/joinchannel.png
   :alt: View of a channel form and the option to join a channel for CoquiAPPs Live Chat

.. toctree::
   :titlesonly:

   livechat/ratings
   livechat/responses
