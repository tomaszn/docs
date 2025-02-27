.. _bulk-loading:

Bulk loading data
=================

Large quantities of data can be imported from a `JSONL <https://jsonlines.org>`__ file into Mattermost at the command line using the bulk loading feature. This feature is most suitable for migrating data from an existing system, or for pre-populating a new installation with data.

You can import the following data types:

- Teams
- Channels (public and private)
- Users
- Users' team memberships
- Users' channel memberships
- Users' notification preferences
- Posts (regular, non-reply posts)
- Posts' replies
- Posts' reactions
- Posts' file attachments
- Direct message and group message channels
- Direct messages and group messages
- Direct messages from a user to themselves
- Permissions schemes
- Custom emoji

Importing additional types of posts is not yet supported.

.. contents:: Contents
  :backlinks: top
  :local:
  :depth: 2

.. include:: bulk-loading-about.rst
.. include:: run-bulk-loading-command.rst
.. include:: bulk-loading-data-format.rst
.. include:: bulk-loading-common-issues.rst
.. include:: bulk-loading-troubleshooting.rst
