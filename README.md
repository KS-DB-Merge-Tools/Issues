# Issues

This is the issue tracker for KS DB Merge Tools. It is for reporting bugs/issues only, not for feature requests. You can write to support@ksdbmerge.tools to discuss feature requests/suggestions or any other technical questions. You can report issues by email as well.

You can [check the list of existing issues](https://github.com/KS-DB-Merge-Tools/Issues/issues) or [report a new one](https://github.com/KS-DB-Merge-Tools/Issues/issues/new/choose)

## Issue titles

To have a quick understanding of what is the issue about, please use the following title format:

[**product-char**] **app-mode** **location**: **description**

where:

[**product-char**] is one of the following:
- [A] - for Access, aka AccdbMerge
- [S] - for SQL Server, aka MssqlMerge
- [M] - for MySQL and MariaDB
- [L] - for SQLite
- [P] - for PostgreSQL
- [O] - for Oracle
- [Х] - for Cross-DBMS

**app-mode** is Free/Pro/Trial/All

**location** is a name of tab, dialog, or other place or event where you observe the issue (for example "App start"). You can use the following names and abbreviations:
- Home - Home tab
- OL - Object list tab
- DD - Data diff tab
- TD - Text diff tab
- TSD - Table structure diff tab
- BDD - Batch data diff tab
- QRD - Query result diff tab
- OpenDB - Open database(s) dialog

**description** is a short but specific description.

[Here](https://github.com/KS-DB-Merge-Tools/Issues/issues/1) is an example of issue which has title according to these rules:

_[S] Pro TSD: Merge unexpected error, invalid cast DBNull to ITableConstraint_

where
- **[S]** - relates to SQL Server / MssqlMerge
- **Pro** - occured in Pro version
- **TSD** - on Table structure diff tab

## Other useful information

Please describe the steps to reproduce and what you think should be an **expected result**. Screenshots, database scripts or files would be helpful but we understand that they may contain sensitive information that should not be accessible pulicitely.
