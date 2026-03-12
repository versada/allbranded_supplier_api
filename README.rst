=======================
allbranded supplier API
=======================

:Authors:
    Tomas Račys,
    Paulius Sladkevičius
    Darius Martinkus,
    Ugnė Sinkevičienė

:Version: 1.5 of 2026-03-12

To be able to import necessary information to allbranded systems, you should provide XML files based on XSD schemas.

XSD files have a data structure, including documentation of elements.

Access to XML files should be provided via HTTPS.

Please validate every XML file with XSD before providing the feed to us.

Product Data
============

:Version: 1.6

**Default Schema and Example**

- Schema - `xml_feeds_schema/schema/Products.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/Products.xsd>`_
- Example - `xml_feeds_schema/examples/Products.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/Products.xml>`_

**Optional Schema**

- Schema - `xml_feeds_schema/schema/ProductDecoTypesWithoutUnique.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/ProductDecoTypesWithoutUnique.xsd>`_
- Example - `xml_feeds_schema/examples/ProductDecoTypesWithoutUnique.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/ProductDecoTypesWithoutUnique.xml>`_

Change log
----------

.. list-table::
   :widths: 25 25 50 25
   :header-rows: 1

   * - Version
     - Date
     - Comments
     - Authors
   * - 1.6
     - 2026-03-12
     - Restore "QuantityPerCarton" as a required field, since it is expected to be provided from the code side as well.
     - Ugnė Sinkevičienė
   * - Version
     - Date
     - Comments
     - Authors
   * - 1.5
     - 2025-04-14
     - Option to define the same Decoration Types (@DecoTypeID) either at the product level or per individual decoration. This includes the introduction of two new schemas—Product-Based Decoration and Decoration-Specific Configuration—with corresponding examples to illustrate each approach.
     - Ugnė Sinkevičienė
   * - 1.4
     - 2025-04-01
     - Add Product.xsd.
     - Darius Martinkus
   * - 1.3
     - 2025-03-26
     - Update "WeightGR" type add :code:`type="xs:decimal"` making this element to accept decimal values.
     - Darius Martinkus
   * - 1.2
     - 2025-03-18
     - Update "QuantityPerCarton" add :code:`minOccurs="0"` making this element optional
     - Darius Martinkus
   * - 1.1
     - 2024-02-08
     - Update "EANCode" type from :code:`T_NotNullString` to :code:`xs:string`
     - Aleksander Milinkevich



Decoration Types & Pricing Data
===============================

:Version: 1.5

**Default Schema and Example**

- Schema - `xml_feeds_schema/schema/DecorationTypesPricing.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/DecorationTypesPricing.xsd>`_
- Example - `xml_feeds_schema/examples/DecorationTypesPricing.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/DecorationTypesPricing.xml>`_

**Optional Schema**

- Schema - `xml_feeds_schema/schema/DecorationTypesPricingWithoutUnique.xsd <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/schema/DecorationTypesPricingWithoutUnique.xsd>`_
- Example - `xml_feeds_schema/examples/DecorationTypesPricingWithoutUnique.xml <https://github.com/versada/allbranded_supplier_api/blob/14.0/xml_feeds_schema/examples/DecorationTypesPricingWithoutUnique.xml>`_


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
