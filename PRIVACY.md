# Privacy Policy

_Last updated: 2026-09-18_

This policy covers **rclone-drive**, a personal Google OAuth client used with
[rclone](https://rclone.org/) to synchronise files between its owner's own computer and
its owner's own Google Drive.

## Who uses it

Only its owner. The client is not distributed, not offered as a service, and no other
person can sign in to it.

## What data is accessed

When the owner runs rclone, the client uses the Google Drive API to read and write files
in the owner's own Google Drive, and only at the owner's explicit direction.

## What data is collected

None. This client:

- does not collect, store, transmit, sell, or share personal data;
- has no server, no backend, and no database — rclone runs locally on the owner's machine;
- performs no analytics and no tracking.

## Credentials

OAuth tokens issued to this client are stored locally, in rclone's configuration file on
the owner's own machine, readable only by the owner's user account. They are never
transmitted anywhere except to Google, as part of normal API authentication.

## Data retention and deletion

No data is retained by this client, so there is nothing to delete. Access can be revoked
at any time from the owner's [Google Account permissions page](https://myaccount.google.com/permissions),
which immediately invalidates the stored tokens.

## Third parties

No data is shared with any third party. The only service contacted is Google, to perform
the file operations the owner requests.

## Contact

Open an issue on this repository, or contact [@Exinatiny](https://github.com/Exinatiny) on GitHub.
