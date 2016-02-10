# Promotion

## Promotion Object

Field | Data Type | Mandatory | Description
------|-----------|-----------|-------------
id | string | Yes | Unique identifier, UUID v4.
subject | string | Yes | Promotion's subject.
startDate | long | Yes | Promotion's start date. Number of seconds since 1st Jan, 1970 00:00 UTC.
expiredDate | long | Yes | Promotion's end date. Number of seconds since 1st Jan, 1970 00:00 UTC.
imageURL | string | Yes |
targetURL | string | Yes | TBD.
actionURL | string | Yes | TBD.
merchant | object | Yes | Merchant whose this promotion belong to.
deleted | boolean | No | Default : `false`.
createdAt | long | Yes |
updatedAt | long | Yes |

