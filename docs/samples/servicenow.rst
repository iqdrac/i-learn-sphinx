ServiceNow Documentation Sample
===============================

Overview
--------

This sample demonstrates structured enterprise documentation for ServiceNow platform workflows.

Admonitions
-----------

.. warning::

   Back up your ServiceNow instance before executing the script.

Tables
------

.. list-table:: Script fields
   :header-rows: 1

   * - Field
     - Purpose
   * - Name
     - Identifies the script
   * - Active
     - Turns the script on or off

Code blocks
-----------

.. code-block:: javascript
   :linenos:

   var gr = new GlideRecord('incident');
   gr.addQuery('active', true);
   gr.query();
