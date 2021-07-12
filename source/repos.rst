Repository Purposes
-------------------

Our codebases fall in one of six categories:
 1. Common/general software used throughout ReDATA codebases
 2. Documentation
 3. Identity and access management (IAM)
 4. Data curation
 5. Data preservation
 6. Infrastructure as Code (IaC)

+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| Software name                                 | Category      | Purpose                                                                    |
+===============================================+===============+============================================================================+
| :ual-re:`LD-Cool-P <LD-Cool-P>`               | Curation      | Python command-line API for data curation                                  |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`ReBACH <ReBACH>`                     | Preservation  | Software to support data preservations with ``Dart`` and other tools       |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`ReQUIAM <ReQUIAM>`                   | IAM           | Python command-line API for IAM                                            |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`ReQUIAM_csv <ReQUIAM_csv>`           | IAM           | Python command-line API and database of groups for IAM                     |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`figshare <figshare>`                 | Curation,     | A forked copy of `cognoma's`_ repository used to gather                    |
|                                               | Preservation  | public/private data from Figshare API                                      |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`ldcoolp-figshare <ldcoolp-figshare>` | Curation      | Python backend API for access to the Figshare API for Figshare for         |
|                                               |               | Institutions instances                                                     |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`redata-commons <redata-commons>`     | General       | A set of common modules, code, and external libraries used throughout      |
|                                               |               | ReDATA codebases.                                                          |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`redata-docs <redata-docs>`           | Documentation | The repository hosting the current pages you are viewing on Read The Docs  |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+
| :ual-re:`redata-iac <redata-iac>`             | IaC           | Repository containing Infrastructure as Code (IaC) and scripts used on the |
|                                               |               | operational side of ReDATA                                                 |
+-----------------------------------------------+---------------+----------------------------------------------------------------------------+

Repository Details
------------------

**More details about each repository:**

+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| Software name                                 | Tag version                | Changelog     | Documentation                 | Main branch | PyPI                                        |
+===============================================+============================+===============+===============================+=============+=============================================+
| :ual-re:`LD-Cool-P <LD-Cool-P>`               | |ldcoolp_version|          | `CHANGELOG`__ | `README`__                    | ``master``  | TBD                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`ReBACH <ReBACH>`                     | N/A                        | TBC           | `README`__                    | ``main``    | TBD                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`ReQUIAM <ReQUIAM>`                   | |ReQUIAM_version|          | `README`__    | `README`__                    | ``master``  | N/A                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`ReQUIAM_csv <ReQUIAM_csv>`           | |ReQUIAM_csv_version|      | TBC           | :rtd:`RTD <requiam-csv>`      | ``master``  | N/A                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`figshare <figshare>`                 | |figshare_version|         | N/A           | N/A                           | ``master``  | N/A                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`ldcoolp-figshare <ldcoolp-figshare>` | |ldcoolp-figshare_version| | `CHANGELOG`__ | :rtd:`RTD <ldcoolp-figshare>` | ``main``    | :pypi:`ldcoolp-figshare <ldcoolp-figshare>` |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`redata-commons <redata-commons>`     | |redata-commons_version|   | `CHANGELOG`__ | :rtd:`RTD <redata-commons>`   | ``main``    | :pypi:`redata <redata>`                     |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`redata-docs <redata-docs>`           | |redata-docs_version|      | N/A           | :rtd:`RTD <redata>`           | ``main``    | N/A                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+
| :ual-re:`redata-iac <redata-iac>`             | |redata-iac_version|       | TBC           | N/A                           | ``master``  | N/A                                         |
+-----------------------------------------------+----------------------------+---------------+-------------------------------+-------------+---------------------------------------------+

.. _`cognoma's`: https://github.com/cognoma/figshare

.. |ldcoolp_version| image:: https://img.shields.io/github/v/tag/UAL-RE/LD-Cool-P?label=%20
   :alt: LD-Cool-P GitHub tag version

.. |ReBACH_version| image:: https://img.shields.io/github/v/tag/UAL-RE/ReBACH?label=%20
   :alt: ReBACH GitHub tag version

.. |ReQUIAM_version| image:: https://img.shields.io/github/v/tag/UAL-RE/ReQUIAM?label=%20
   :alt: ReQUIAM GitHub tag version

.. |ReQUIAM_csv_version| image:: https://img.shields.io/github/v/tag/UAL-RE/ReQUIAM_csv?label=%20
   :alt: ReQUIAM_csv GitHub tag version

.. |ldcoolp-figshare_version| image:: https://img.shields.io/github/v/tag/UAL-RE/ldcoolp-figshare?label=%20
   :alt: ldcoolp-figshare GitHub tag version

.. |figshare_version| image:: https://img.shields.io/github/v/tag/UAL-RE/figshare?label=%20
   :alt: figshare GitHub tag version

.. |redata-commons_version| image:: https://img.shields.io/github/v/tag/UAL-RE/redata-commons?label=%20
   :alt: redata-commons GitHub tag version

.. |redata-docs_version| image:: https://img.shields.io/github/v/tag/UAL-RE/redata-docs?label=%20
   :alt: redata-docs GitHub tag version

.. |redata-iac_version| image:: https://img.shields.io/github/v/tag/UAL-RE/redata-iac?label=%20
   :alt: redata-iac GitHub tag version

.. __: https://github.com/UAL-RE/LD-Cool-P/blob/master/CHANGELOG.md

.. __: https://github.com/UAL-RE/LD-Cool-P/blob/master/README.md

.. __: https://github.com/UAL-RE/ReBACH/blob/main/README.md

.. __: https://github.com/UAL-RE/ReQUIAM/blob/master/README.md#changelog

.. __: https://github.com/UAL-RE/ReQUIAM/blob/master/README.md

.. __: https://github.com/UAL-RE/ldcoolp-figshare/blob/main/CHANGELOG.md

.. __: https://github.com/UAL-RE/redata-commons/blob/main/CHANGELOG.md