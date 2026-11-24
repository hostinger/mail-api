## v1.4.0 - 2026-11-24

# API Changelog 1.3.0 vs. 1.4.0


## API Changes

### GET /api/v1/mailboxes/{mailboxResourceId}/calendars
-  endpoint added


### POST /api/v1/mailboxes/{mailboxResourceId}/calendars
-  endpoint added


### DELETE /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}
-  endpoint added


### GET /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}
-  endpoint added


### PUT /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}
-  endpoint added


### GET /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events
-  endpoint added


### POST /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events
-  endpoint added


### DELETE /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events/{eventUuid}
-  endpoint added


### GET /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events/{eventUuid}
-  endpoint added


### PUT /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events/{eventUuid}
-  endpoint added


### POST /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events/{eventUuid}/reply
-  endpoint added


### PUT /api/v1/mailboxes/{mailboxResourceId}/calendars/{calendarUuid}/events/{eventUuid}/reschedule
-  endpoint added


### POST /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/search
-  added the non-success response with the status `504`


### GET /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/{uid}/attachments/{attachmentId}
-  added the non-success response with the status `504`


### GET /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/{uid}/source
-  added the non-success response with the status `504`







## v1.3.0 - 2026-10-22

# API Changelog 1.2.2 vs. 1.3.0


## API Changes

### GET /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages
- :warning: added `subschema #2` to the `data/items/from` response property `oneOf` list for the response status `200`
-  the response property `data/items/from` became not nullable for the status `200`


### POST /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/search
- :warning: added `subschema #2` to the `data/items/from` response property `oneOf` list for the response status `200`
-  the response property `data/items/from` became not nullable for the status `200`


### GET /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/{uid}
- :warning: added `subschema #2` to the `data/from` response property `oneOf` list for the response status `200`
-  the response property `data/from` became not nullable for the status `200`


### PATCH /api/v1/mailboxes/{mailboxResourceId}/folders/{folder}/messages/{uid}
- :warning: added `subschema #2` to the `data/from` response property `oneOf` list for the response status `200`
-  the response property `data/from` became not nullable for the status `200`


### POST /api/v1/mailboxes/{mailboxResourceId}/send
- :warning: removed `subschema #1, subschema #2, subschema #3` from the request body `anyOf` list




## Info
-  a breaking change was detected but the major version did not increase, from `1.2.2` to `1.3.0`





## v1.2.2 - 2026-10-09

# API Changelog 1.2.1 vs. 1.2.2

No changes to report, but the specs are different



## v1.2.1 - 2026-10-09

# API Changelog 1.1.0 vs. 1.2.1


## API Changes

### POST /api/v1/mailboxes/{mailboxResourceId}/feedback
-  endpoint added


### POST /api/v1/mailboxes/{mailboxResourceId}/send
-  added the non-success response with the status `504`







## v1.1.0 - 2026-07-21

# API Changelog 1.0.3 vs. 1.1.0


## API Changes

### POST /api/v1/mailboxes/{mailboxResourceId}/send
-  added the new optional request property `forwardOf`
-  added the new optional request property `inReplyTo`







## v1.0.3 - 2026-07-16

# API Changelog 1.0.2 vs. 1.0.3

No changes to report, but the specs are different



## v1.0.2 - 2026-07-09

# API Changelog 1.0.0 vs. 1.0.2

No changes to report, but the specs are different



## v1.0.0 - 2026-07-02

Initial release.

