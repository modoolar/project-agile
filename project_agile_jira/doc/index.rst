.. image:: https://www.gnu.org/graphics/lgplv3-147x51.png
   :target: https://www.gnu.org/licenses/lgpl-3.0.en.html
   :alt: License: LGPL-v3

===========================
Project Agile JIRA Importer
===========================

This module enables you to import your projects and tasks from JIRA to Odoo.

Usage
=====

In order to migrate projects from JIRA to Odoo, follow next steps:

1. Navigate to Project > Services > Jira and create an configuration object
that points to your Jira instance.
2. Click on Synchronize Projects Button
3. Assign a workflow to each project
4. Click on Synchronize Tasks.

After last step, for each task, a Request job will be created, and
"Proccess JIRA requests" cron job gets executed, each importation Request
will get executed.

Credits
=======

Contributors
------------

* Sladjan Kantar <sladjan.kantar@modoolar.com>
* Petar Najman <petar.najman@modoolar.com>
* Игорь Митин <igor.mitin@outlook.com>

Maintainer
----------

.. image:: https://www.modoolar.com/web/image/ir.attachment/3461/datas
   :alt: Modoolar
   :target: https://modoolar.com

This module is maintained by Modoolar.

::

   As Odoo Gold partner, our company is specialized in Odoo ERP customization and business solutions development.
   Beside that, we build cool apps on top of Odoo platform.

To contribute to this module, please visit https://modoolar.com
