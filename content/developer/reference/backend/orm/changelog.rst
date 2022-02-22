.. _reference/orm/changelog:

=========
Changelog
=========

Odoo Online version 15.5
========================

- :meth:`~odoo.models.BaseModel.search_count` takes :attr:`limit` argument in account. (`#95589 <https://github.com/odoo/odoo/pull/95589>`_)
  It limits the number of record to count, which improve the performance if a partial result is acceptable.

Odoo Online version 15.4
========================

- New API for flushing to the database and invalidating the cache with
  `#87527 <https://github.com/odoo/odoo/pull/87527>`_.
  New methods have been added to `odoo.models.Model` and `odoo.api.Environment`,
  and are less confusing about what is actually done in each case.
  See the section :ref:`SQL Execution <reference/orm/sql>`.

Odoo Online version 15.3
========================

- Arguments name change for :meth:`~odoo.models.BaseModel.search`, :meth:`~odoo.models.BaseModel.search_count`
  and :meth:`~odoo.models.BaseModel._search`:  `args` is called `domain` now. (`#83687 <https://github.com/odoo/odoo/pull/83687>`_)
- :meth:`~odoo.models.BaseModel.filtered_domain` now conserve order of the current recordset (`#83687 <https://github.com/odoo/odoo/pull/83687>`_)
- With `#83687 <https://github.com/odoo/odoo/pull/83687>`_, :meth:`~odoo.models.BaseModel.browse` doesn't accept :class:`str` as ids anymore.
- Deprecate :meth:`~odoo.models.BaseModel.fields_get_keys` and :meth:`~odoo.models.BaseModel.get_xml_id` methods of :class:`~odoo.models.BaseModel` (`#83687 <https://github.com/odoo/odoo/pull/83687>`_)
- Remove :meth:`~odoo.models.BaseModel._mapped_cache` method (`#83687 <https://github.com/odoo/odoo/pull/83687>`_)
- Remove :attr:`limit` attribute of :class:`~odoo.fields.One2many` and :class:`~odoo.fields.Many2many`

Odoo Online version 15.2
========================

- Remove :attr:`_sequence` attribute of :class:`~odoo.models.BaseModel`:  Let PostgreSQL uses the default sequence of the primary key
  `#82727 <https://github.com/odoo/odoo/pull/82727>`_
- :meth:`~odoo.models.BaseModel._write` of :class:`~odoo.models.BaseModel` doesn't raise error anymore for no existing records 
  (`#82727 <https://github.com/odoo/odoo/pull/82727>`_)
- Specific index types on :class:`~odoo.fields.Field`:  With `#83274 <https://github.com/odoo/odoo/pull/83274>`_ and
  `#83015 <https://github.com/odoo/odoo/pull/83015>`_, developers can now define what type of
  indexes can be used on fields by PostgreSQL. See the :ref:`index property <reference/fields>` of
  :class:`~odoo.fields.Field`.
- With `#82896 <https://github.com/odoo/odoo/pull/82896>`_, translated :class:`~odoo.fields.Field` 
  are not prefetch by default anymore (expect the :attr:`~odoo.models.BaseModel._rec_name` field).
- Remove :attr:`column_format` and :attr:`deprecated` attributes of :class:`~odoo.fields.Field` (`#82727 <https://github.com/odoo/odoo/pull/82727>`_)

Odoo Online version 15.1
========================

- With `#79622 <https://github.com/odoo/odoo/pull/79622>`_, the :meth:`reversed` works efficiently on recordset.
