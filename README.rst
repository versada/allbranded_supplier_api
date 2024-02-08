=======================
allbranded supplier API
=======================

:Authors:
    Tomas Račys,
    Paulius Sladkevičius

:Version: 1.1 of 2023-09-06

To be able to import necessary information to allbranded systems, you should provide XML files based on XSD schemas.

XSD files have a data structure, including documentation of elements.

Access to XML files should be provided via HTTPS.

Please validate every XML file with XSD before providing the feed to us.

Product Data
============

:Version: 1.1

- Schema - `xml_feeds_schema/schema/Products.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/Products.xsd>`_
- Example - `xml_feeds_schema/examples/Products.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/Products.xml>`_

Change log
----------

.. list-table::
   :widths: 25 25 50 25
   :header-rows: 1

   * - Version
     - Date
     - Comments
     - Authors
   * - 1.1
     - 2024-02-08
     - Update "EANCode" type from :code:`T_NotNullString` to :code:`xs:string`
     - Aleksander Milinkevich



Decoration Types & Pricing Data
===============================

:Version: 1.1

- Schema - `xml_feeds_schema/schema/DecorationTypesPricing.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/DecorationTypesPricing.xsd>`_
- Example - `xml_feeds_schema/examples/DecorationTypesPricing.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/DecorationTypesPricing.xml>`_

Change log
----------

.. list-table::
   :widths: 25 25 50 25
   :header-rows: 1

   * - Version
     - Date
     - Comments
     - Authors
   * - 1.1
     - 2023-09-06
     - Rename DecorationTypes.xsd to DecorationTypesPricing.xsd
     - Paulius Sladkevičius

Stock Data
==========

:Version: 1.0

- Schema - `xml_feeds_schema/schema/Stock.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/Stock.xsd>`_
- Example - `xml_feeds_schema/examples/Stock.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/Stock.xml>`_


In case you've any questions, please contact your point of contact.
