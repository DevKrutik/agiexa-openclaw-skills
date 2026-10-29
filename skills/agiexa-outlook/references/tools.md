# Outlook tools via Agiexa (287)

Preview only - these become available to the agent after Agiexa launches (November 2026) and the merchant connects Outlook and turns the tools on. They cannot be called today.

Interactive explorer: https://agiexa.com/integrations/outlook

| Tool | What it does |
| --- | --- |
| `OUTLOOK_ACCEPT_EVENT` | Accepts or tentatively accepts a calendar meeting invite on behalf of a user |
| `OUTLOOK_ADD_EVENT_ATTACHMENT` | Adds an attachment to a specific Outlook calendar event |
| `OUTLOOK_ADD_MAIL_ATTACHMENT` | Tool to add an attachment to an email message |
| `OUTLOOK_BATCH_MOVE_MESSAGES` | Batch-move up to 20 Outlook messages to a destination folder in a single Microsoft Graph $batch call |
| `OUTLOOK_BATCH_UPDATE_MESSAGES` | Batch-update up to 20 Outlook messages per call using Microsoft Graph JSON batching |
| `OUTLOOK_CALENDAR_CREATE_EVENT` | Creates a new Outlook calendar event, ensuring `start_datetime` is chronologically before `end_datetime` |
| `OUTLOOK_CANCEL_CALENDAR_EVENT` | Tool to cancel an event in a specific calendar for a specified user and send cancellation notifications to all attendees |
| `OUTLOOK_CANCEL_CALENDAR_GROUP_CALENDAR_EVENT` | Tool to cancel an event in a user's calendar within a calendar group and send cancellation notifications to all attendees |
| `OUTLOOK_CANCEL_EVENT` | Tool to cancel a calendar event for a specified user and send cancellation notifications to all attendees |
| `OUTLOOK_COPY_MAIL_FOLDER` | Tool to copy a user's mail folder and its contents to another folder |
| `OUTLOOK_COPY_ME_MAIL_FOLDER` | Tool to copy a child mail folder to a destination folder |
| `OUTLOOK_COPY_MESSAGE` | Tool to copy an email message to another folder within the user's mailbox |
| `OUTLOOK_COPY_MESSAGE_FROM_CHILD_FOLDER` | Tool to copy an email message from a child folder (nested folder) to another folder within the user's mailbox |
| `OUTLOOK_COPY_MESSAGE_FROM_MAIL_FOLDER` | Tool to copy a message from a specific user's mail folder to another folder |
| `OUTLOOK_CREATE_ATTACHMENT_UPLOAD_SESSION` | Tool to create an upload session for large (>3 MB) message attachments |
| `OUTLOOK_CREATE_ATTACHMENT_UPLOAD_SESSION_IN_CHILD_FOLDER` | Tool to create an upload session for large (>3 MB) message attachments in child mail folders |
| `OUTLOOK_CREATE_CALENDAR` | Tool to create a new calendar in the signed-in user's mailbox |
| `OUTLOOK_CREATE_CALENDAR_EVENT_ATTACHMENT` | Tool to create a new attachment for an event in a specific calendar |
| `OUTLOOK_CREATE_CALENDAR_EVENT_ATTACHMENT_UPLOAD_SESSION` | Tool to create an upload session for large calendar event attachments in a specific calendar |
| `OUTLOOK_CREATE_CALENDAR_EVENT_IN_CALENDAR` | Tool to create a new event in a specific calendar for a user |
| `OUTLOOK_CREATE_CALENDAR_GROUP` | Tool to create a new calendar group for a user |
| `OUTLOOK_CREATE_CALENDAR_GROUP_CALENDAR_EVENT_ATTACHMENT` | Tool to create a new attachment for an event in a calendar within a calendar group for a specific user |
| `OUTLOOK_CREATE_CALENDAR_GROUP_CALENDAR_EVENT_EXTENSION` | Tool to create a new open extension on a calendar event within a specific calendar group and calendar |
| `OUTLOOK_CREATE_CALENDAR_PERMISSION` | Tool to create a calendar permission for a specific calendar in a calendar group |
| `OUTLOOK_CREATE_CAL_GROUP_EVENT_ATTACH_UPLOAD` | Tool to create an upload session for large calendar group event attachments |
| `OUTLOOK_CREATE_CONTACT` | Creates a new contact in a Microsoft Outlook user's contacts folder |
| `OUTLOOK_CREATE_CONTACT_FOLDER` | Tool to create a new contact folder in the user's mailbox |
| `OUTLOOK_CREATE_CONTACT_FOLDER_CHILD_FOLDER` | Tool to create a child contact folder within a parent contact folder for a specific user |
| `OUTLOOK_CREATE_DRAFT` | Creates a new Outlook email draft with subject, body, recipients, and an optional attachment |
| `OUTLOOK_CREATE_DRAFT_REPLY` | Creates a draft reply in the specified user's Outlook mailbox to an existing message (identified by a valid `message_id`), optionally including a `com |
| `OUTLOOK_CREATE_EMAIL_RULE` | Create email rule filter with conditions and actions |
| `OUTLOOK_CREATE_EVENT_ATTACHMENT` | Tool to create a new attachment for a user's calendar event |
| `OUTLOOK_CREATE_EVENT_ATTACHMENT_UPLOAD_SESSION` | Tool to create an upload session for large calendar event attachments |
| `OUTLOOK_CREATE_FORWARD_DRAFT` | Tool to create a forward draft of an Outlook message for a specific user |
| `OUTLOOK_CREATE_MAIL_FOLDER` | Tool to create a new mail folder |
| `OUTLOOK_CREATE_MAIL_FOLDER_MESSAGE` | Tool to create a new message in a specific mail folder |
| `OUTLOOK_CREATE_MAIL_FOLDER_MESSAGE_ATTACHMENT` | Tool to add an attachment to a message in a specific mail folder |
| `OUTLOOK_CREATE_MAIL_FOLDER_MESSAGE_ATTACHMENT_UPLOAD_SESSION` | Tool to create an upload session for large (>3 MB) message attachments in a specific mail folder |
| `OUTLOOK_CREATE_MAIL_FOLDER_MESSAGE_RULE` | Tool to create a message rule in a user's mail folder |
| `OUTLOOK_DELETE_ME_MESSAGES_ATTACHMENTS` | Tool to delete an attachment from a message |
| `OUTLOOK_CREATE_ME_CALENDAR_EVENT_EXTENSION` | Tool to create a new open extension on a calendar event for a specific user |
| `OUTLOOK_CREATE_ME_CALENDAR_PERMISSION` | Tool to create a new calendar permission for a specific user's calendar |
| `OUTLOOK_CREATE_ME_CHILD_FOLDER_MESSAGE` | Tool to create a new draft message in a child folder within a user's mail folder |
| `OUTLOOK_CREATE_ME_CONTACT_FOLDERS_CONTACTS` | Tool to create a new contact in a specific user's contact folder |
| `OUTLOOK_CREATE_ME_CONTACT_FOLDERS_CONTACTS_EXTENSIONS` | Tool to create a new open extension on a contact within a user's contact folder |
| `OUTLOOK_CREATE_ME_CONTACT_FOLDERS_EXTENSIONS` | Tool to create a new open extension on a contact within a child folder |
| `OUTLOOK_CREATE_ME_CONTACT_IN_CHILD_FOLDER` | Tool to create a new contact in a child folder within a contact folder |
| `OUTLOOK_CREATE_ME_EVENT` | Tool to create a new calendar event for a specific user |
| `OUTLOOK_CREATE_ME_EVENT_ATTACHMENT_UPLOAD_SESSION` | Tool to create an upload session for large event attachments |
| `OUTLOOK_CREATE_ME_FORWARD_DRAFT` | Tool to create a draft forward of an existing message |
| `OUTLOOK_CREATE_ME_INFERENCE_CLASSIFICATION_OVERRIDE` | Tool to create a Focused Inbox override for a sender identified by SMTP address for a specific user |
| `OUTLOOK_CREATE_ME_MESSAGE_REPLY_ALL_DRAFT` | Tool to create a draft reply-all to a user's message |
| `OUTLOOK_CREATE_ME_REPLY_ALL_DRAFT` | Tool to create a draft reply-all to a message in a child folder |
| `OUTLOOK_CREATE_MESSAGE_ATTACHMENT` | Tool to create an attachment for a message |
| `OUTLOOK_CREATE_REPLY_ALL_DRAFT` | Tool to create a reply-all draft for a message in a mail folder |
| `OUTLOOK_CREATE_TASK` | Tool to create a new task in Microsoft To Do within a specified task list |
| `OUTLOOK_CREATE_USER_CALENDAR_EVENT_ATTACHMENT` | Tool to create a new attachment for an event in a specific user's calendar |
| `OUTLOOK_CREATE_USER_CALENDAR_GROUP_CALENDAR` | Tool to create a new calendar in a calendar group for a specific user |
| `OUTLOOK_CREATE_USER_CALENDAR_GROUP_EVENT` | Tool to create a new calendar event in a specific user's calendar within a calendar group |
| `OUTLOOK_CREATE_USER_CONTACTS_EXTENSIONS` | Tool to create a new open extension on a specific user's contact |
| `OUTLOOK_CREATE_USER_EVENT_CALENDAR_PERMISSION` | Tool to create a calendar permission via an event's calendar |
| `OUTLOOK_CREATE_USER_MAIL_CHILD_FOLDER_MSG_EXT` | Tool to create a new open extension on a message in a child mail folder for any user |
| `OUTLOOK_CREATE_USER_MAIL_FOLDER_MESSAGE_EXTENSION` | Tool to create a new open extension on a message in a user's mail folder |
| `OUTLOOK_CREATE_USER_MAIL_FOLDER_MESSAGE_REPLY_DRAFT` | Tool to create a reply draft for a message in a user's mail folder |
| `OUTLOOK_CREATE_USER_MAIL_FOLDERS_CHILD_FOLDERS` | Tool to create a new child folder under a specified mail folder for a user |
| `OUTLOOK_CREATE_USER_MASTER_CATEGORY` | Tool to create a new category in a user's master category list |
| `OUTLOOK_CREATE_USER_MESSAGE` | Tool to create a new draft message in a user's mailbox |
| `OUTLOOK_CREATE_USER_MESSAGE_ATTACHMENT` | Tool to create an attachment on a message in a user's mail folder |
| `OUTLOOK_DECLINE_EVENT` | Tool to decline an invitation to a calendar event |
| `OUTLOOK_DELETE_CALENDAR` | Tool to delete a calendar other than the default calendar from a user's mailbox |
| `OUTLOOK_DELETE_CALENDAR_EVENT` | Tool to delete a calendar event from a user's Outlook calendar |
| `OUTLOOK_DELETE_CALENDAR_EVENT_ATTACHMENT` | Tool to delete an attachment from an event in a specific user's calendar |
| `OUTLOOK_DELETE_CALENDAR_EVENT_FROM_SPECIFIC_CALENDAR` | Tool to delete an event from a specific calendar in Outlook |
| `OUTLOOK_DELETE_CALENDAR_FROM_GROUP` | Tool to delete a calendar from a specific user's calendar group in Microsoft Outlook |
| `OUTLOOK_DELETE_CALENDAR_GROUP` | Tool to delete a calendar group other than the default calendar group |
| `OUTLOOK_DELETE_CALENDAR_GROUP_CALENDAR_EVENT` | Tool to delete a calendar event from a specific user's calendar within a calendar group |
| `OUTLOOK_DELETE_CALENDAR_GROUP_EVENT_ATTACHMENT` | Tool to delete an attachment from an event in a calendar within a calendar group |
| `OUTLOOK_DELETE_CALENDAR_GROUP_EVENT_PERMANENTLY` | Tool to permanently delete a calendar event from a calendar within a calendar group |
| `OUTLOOK_DELETE_CALENDAR_PERMANENTLY` | Permanently deletes a calendar from a user's mailbox |
| `OUTLOOK_DELETE_CALENDAR_PERMISSION` | Tool to delete a calendar permission from a user's calendar within a calendar group |
| `OUTLOOK_DELETE_CHILD_CONTACT_FOLDER_PERMANENTLY` | Permanently deletes a child contact folder |
| `OUTLOOK_DELETE_CHILD_FOLDER_MESSAGE` | Tool to delete a message from a child mail folder in Outlook |
| `OUTLOOK_DELETE_CONTACT` | Permanently deletes an existing contact, using its `contact_id` (obtainable via 'List User Contacts' or 'Get Contact'), from the Outlook contacts of t |
| `OUTLOOK_DELETE_CONTACT_FOLDER` | Tool to delete a contact folder from the user's mailbox |
| `OUTLOOK_DELETE_CONTACT_FOLDER_CHILD_FOLDER` | Tool to delete a child contact folder from a parent contact folder for a specific user |
| `OUTLOOK_DELETE_CONTACT_FOLDER_CONTACT` | Tool to permanently delete a contact from a specific contact folder |
| `OUTLOOK_DELETE_CONTACT_FOLDER_PERMANENTLY` | Permanently deletes a contact folder |
| `OUTLOOK_DELETE_CONTACT_FROM_CHILD_FOLDER_PERMANENTLY` | Tool to permanently delete a contact from a child folder for a specific user |
| `OUTLOOK_DELETE_CONTACT_FROM_FOLDER_PERMANENTLY` | Permanently deletes a contact from a specific contact folder |
| `OUTLOOK_DELETE_CONTACT_PERMANENTLY` | Permanently deletes a contact |
| `OUTLOOK_DELETE_CONTACTS_EXTENSIONS` | Tool to delete a navigation property extension from a contact within a child folder |
| `OUTLOOK_DELETE_EMAIL_RULE` | Delete an email rule permanently; deletion is irreversible |
| `OUTLOOK_DELETE_EVENT_ATTACHMENT` | Tool to delete an attachment from an Outlook calendar event |
| `OUTLOOK_DELETE_EVENT_EXTENSION` | Tool to delete an open extension from a calendar event in a calendar group |
| `OUTLOOK_DELETE_EVENT_PERMANENTLY` | Permanently deletes a calendar event |
| `OUTLOOK_DELETE_MAIL_FOLDER` | Delete a mail folder from the user's mailbox |
| `OUTLOOK_DELETE_MAIL_FOLDER_MESSAGE` | Tool to delete a message from a specific mail folder in Outlook |
| `OUTLOOK_DELETE_MASTER_CATEGORY` | Tool to delete a category from the user's master category list |
| `OUTLOOK_DELETE_ME_CALENDAR_PERMISSION` | Tool to delete a calendar permission from a specific user's calendar |
| `OUTLOOK_DELETE_ME_CONTACT_EXTENSION` | Tool to delete an open extension from a contact |
| `OUTLOOK_DELETE_ME_CONTACT_FOLDER_CONTACT_EXTENSION` | Tool to delete an extension from a contact in a user's contact folder |
| `OUTLOOK_DELETE_ME_EVENT_EXTENSION` | Tool to delete an open extension from a user's calendar event |
| `OUTLOOK_DELETE_ME_EVENTS_ATTACHMENTS` | Tool to delete an attachment from a user's Outlook event |
| `OUTLOOK_DELETE_ME_INFERENCE_CLASSIFICATION_OVERRIDE` | Tool to delete an inference classification override for a specific sender |
| `OUTLOOK_DELETE_ME_MAIL_FOLDER_CHILD_FOLDER` | Tool to delete a child mail folder from a parent mail folder |
| `OUTLOOK_DELETE_ME_MAIL_FOLDER_CHILD_FOLDER_PERMANENTLY` | Permanently deletes a child mail folder from a parent mail folder |
| `OUTLOOK_DELETE_ME_MAIL_FOLDER_MESSAGE_RULE` | Tool to delete a message rule from a specific mail folder |
| `OUTLOOK_DELETE_ME_MAIL_FOLDERS_CHILD_FOLDERS_MESSAGES_EXTENS` | Delete user message extension |
| `OUTLOOK_DELETE_ME_MAIL_FOLDERS_MESSAGES_EXTENSIONS` | Tool to delete a navigation property extension from a message within a mail folder |
| `OUTLOOK_DELETE_MESSAGE` | Tool to permanently delete an Outlook email message by its message_id |
| `OUTLOOK_DELETE_MESSAGE_ATTACHMENT` | Tool to delete an attachment from a message in a nested mail folder structure |
| `OUTLOOK_DELETE_MESSAGE_EXTENSION` | Tool to delete an open extension from an Outlook message |
| `OUTLOOK_DELETE_PRIMARY_CALENDAR_PERMISSION` | Tool to delete a calendar permission from a specific user's calendar |
| `OUTLOOK_DELETE_TODO_TASK` | Tool to permanently delete a task from a Microsoft To Do task list |
| `OUTLOOK_DELETE_USER_CALENDAR_EVENT_PERMANENTLY` | Tool to permanently delete a calendar event from a specific user's calendar |
| `OUTLOOK_DELETE_USER_CHILD_FOLDER_CONTACT` | Tool to delete a contact from a child folder in a user's contact folder |
| `OUTLOOK_DELETE_USER_CHILD_FOLDER_MESSAGE_PERMANENTLY` | Tool to permanently delete a message from a user's child mail folder in Outlook |
| `OUTLOOK_DELETE_USER_EVENT_PERMANENTLY` | Tool to permanently delete a calendar event for a specified user |
| `OUTLOOK_DELETE_USER_MAIL_FOLDER_PERMANENTLY` | Permanently deletes a mail folder for a specific user |
| `OUTLOOK_DISMISS_CALENDAR_EVENT_REMINDER` | Tool to dismiss a reminder for a specific event in a user's calendar |
| `OUTLOOK_DISMISS_EVENT_REMINDER` | Tool to dismiss a reminder for a specific calendar event |
| `OUTLOOK_DISMISS_EVENT_REMINDER_FROM_GROUP` | Tool to dismiss a reminder for an event in a user's calendar within a calendar group |
| `OUTLOOK_DISMISS_USER_EVENT_REMINDER` | Tool to dismiss a reminder for a specific user's calendar event |
| `OUTLOOK_DOWNLOAD_OUTLOOK_ATTACHMENT` | Downloads a specific file attachment from an email message in a Microsoft Outlook mailbox; the attachment must contain 'contentBytes' (binary data) an |
| `OUTLOOK_FIND_MEETING_TIMES` | Suggests meeting times based on organizer and attendee availability, time constraints, and duration requirements |
| `OUTLOOK_FORWARD_MESSAGE` | Tool to forward a message |
| `OUTLOOK_FORWARD_USER_CALENDAR_EVENT` | Tool to forward a calendar event from a specific user's calendar to new recipients |
| `OUTLOOK_GET_CALENDAR_EVENT` | Tool to retrieve a specific event from a specified calendar |
| `OUTLOOK_GET_CALENDAR_EVENT_ATTACHMENT` | Tool to retrieve a specific attachment from an event within a calendar |
| `OUTLOOK_GET_CALENDAR_FROM_EVENT` | Tool to retrieve the parent calendar that contains a specific event |
| `OUTLOOK_GET_CALENDAR_FROM_GROUP` | Tool to retrieve a specific calendar from a calendar group in Microsoft Outlook |
| `OUTLOOK_GET_CALENDAR_GROUP` | Tool to retrieve the properties and relationships of a calendar group object |
| `OUTLOOK_GET_CALENDAR_GROUP_CALENDAR_EVENT_EXTENSION` | Tool to retrieve an open extension from a calendar event within a specific calendar group and calendar |
| `OUTLOOK_GET_CALENDAR_GROUP_SCHEDULE` | Tool to retrieve free/busy schedule information for a specific user's calendar within a calendar group |
| `OUTLOOK_GET_CALENDAR_PERMISSION` | Tool to retrieve a specific calendar permission for a user's calendar |
| `OUTLOOK_GET_CALENDAR_PERMISSION_FROM_CALENDAR` | Tool to retrieve a specific calendar permission from a user's calendar |
| `OUTLOOK_GET_CALENDAR_SCHEDULE` | Tool to get free/busy schedule information for users, distribution lists, or resources |
| `OUTLOOK_GET_CALENDAR_VIEW` | Get events ACTIVE during a time window (includes multi-day events) |
| `OUTLOOK_GET_CHILD_FOLDER_MESSAGE` | Tool to retrieve a specific email message from a child mail folder |
| `OUTLOOK_GET_CHILD_FOLDER_MESSAGE_CONTENT` | Tool to get the MIME content of a message from a child mail folder |
| `OUTLOOK_GET_CHILD_MAIL_FOLDER` | Tool to retrieve a specific child mail folder from a parent mail folder |
| `OUTLOOK_GET_CONTACT_EXTENSION` | Tool to retrieve an open extension from a contact in Microsoft Graph |
| `OUTLOOK_GET_CONTACT_FOLDER` | Tool to retrieve a specific contact folder by ID |
| `OUTLOOK_GET_CONTACT_FOLDERS` | Tool to retrieve contact folders from a specific user's mailbox |
| `OUTLOOK_GET_CONTACT_FROM_FOLDER` | Tool to retrieve a specific contact from a contact folder by its ID |
| `OUTLOOK_GET_DRAFTS_MAIL_FOLDER` | Tool to get the drafts mail folder |
| `OUTLOOK_GET_EVENT` | Retrieves the full details of a specific calendar event by its ID from a user's Outlook calendar, provided the event exists |
| `OUTLOOK_GET_EVENT_ATTACHMENT` | Tool to retrieve a specific attachment from an Outlook calendar event by attachment ID |
| `OUTLOOK_GET_EVENT_CALENDAR_FROM_GROUP` | Tool to retrieve the calendar that contains a specific event within a calendar group |
| `OUTLOOK_GET_INFERENCE_CLASSIFICATION` | Tool to get inference classification settings for the authenticated user |
| `OUTLOOK_GET_MAILBOX_SETTINGS` | Tool to retrieve mailbox settings |
| `OUTLOOK_GET_MAIL_DELTA` | Retrieve incremental changes (delta) of messages in a mailbox |
| `OUTLOOK_GET_MAIL_FOLDER` | Retrieve one Outlook mail folder by opaque ID or well-known name, optionally selecting only needed metadata such as display name and item counts |
| `OUTLOOK_GET_MAIL_FOLDER_MESSAGE` | Tool to retrieve a specific message from a mail folder by its ID |
| `OUTLOOK_GET_MAIL_FOLDER_MESSAGE_RULE` | Tool to retrieve a specific message rule from a user's mail folder |
| `OUTLOOK_GET_MAIL_TIPS` | Tool to retrieve mail tips such as automatic replies and mailbox full status |
| `OUTLOOK_GET_MASTER_CATEGORIES` | Tool to retrieve the user's master category list |
| `OUTLOOK_GET_MASTER_CATEGORY` | Tool to retrieve properties of a specific category from the user's master category list |
| `OUTLOOK_GET_ME_CALENDAR` | Tool to get the properties and relationships of the signed-in user's default calendar |
| `OUTLOOK_GET_ME_CONTACT_FOLDERS_CHILD_FOLDER` | Tool to retrieve a specific child contact folder for a user by ID |
| `OUTLOOK_GET_ME_CONTACT_FROM_CHILD_FOLDER` | Tool to retrieve a specific contact from a nested child folder within a contact folder |
| `OUTLOOK_GET_ME_CONTACT_PHOTO` | Tool to get the binary media content of a contact's profile photo |
| `OUTLOOK_GET_ME_CONTACTS` | Retrieves a specific Outlook contact by its `contact_id` from the contacts of a specified `user_id` (defaults to 'me' for the authenticated user) |
| `OUTLOOK_GET_ME_CONTACTS_EXTENSIONS` | Tool to retrieve a specific open extension from a user's contact |
| `OUTLOOK_GET_ME_EVENT_ATTACHMENT` | Tool to retrieve a specific attachment from a user's calendar event |
| `OUTLOOK_GET_ME_EVENT_CALENDAR` | Tool to retrieve the calendar that contains a specific event |
| `OUTLOOK_GET_ME_MAIL_FOLDERS_MESSAGES_EXTENSIONS` | Tool to retrieve a specific extension from a message in a user's mailbox |
| `OUTLOOK_GET_ME_MESSAGE_MIME_CONTENT` | Tool to get the MIME content of a message |
| `OUTLOOK_GET_ME_OUTLOOK` | Tool to retrieve the outlookUser object for a specified user |
| `OUTLOOK_GET_MESSAGE` | Retrieves a specific email message by its ID from the specified user's Outlook mailbox |
| `OUTLOOK_GET_MESSAGE_EXTENSION` | Tool to retrieve a specific extension from a user's message |
| `OUTLOOK_GET_NESTED_FOLDER_MESSAGE_ATTACHMENT` | Tool to retrieve a specific attachment from a message located in a nested mail folder structure |
| `OUTLOOK_GET_PROFILE` | Retrieves the Microsoft Outlook profile for a specified user |
| `OUTLOOK_GET_SCHEDULE` | Retrieves free/busy schedule information for specified email addresses within a defined time window |
| `OUTLOOK_GET_SUPPORTED_LANGUAGES` | Tool to retrieve supported languages in the user's mailbox |
| `OUTLOOK_GET_SUPPORTED_TIME_ZONES` | Tool to get the list of time zones supported for a user as configured on their mailbox server |
| `OUTLOOK_GET_USER_BY_EMAIL` | Retrieves user details from Microsoft Graph by email address (userPrincipalName) |
| `OUTLOOK_GET_USER_CALENDAR` | Tool to get the properties and relationships of a specific calendar for a user |
| `OUTLOOK_GET_USER_CALENDAR_ALLOWED_SHARING_ROLES` | Tool to retrieve allowed calendar sharing roles for a specific user on a given calendar |
| `OUTLOOK_GET_USER_CALENDAR_EVENT` | Tool to retrieve a specific calendar event from a user's primary calendar |
| `OUTLOOK_GET_USER_CALENDAR_GROUP_CALENDAR_PERMISSION` | Tool to retrieve a specific calendar permission for a user's calendar within a calendar group |
| `OUTLOOK_GET_USER_CALENDAR_GROUP_EVENT` | Tool to retrieve a specific event from a user's calendar within a calendar group |
| `OUTLOOK_GET_USER_CALENDAR_GROUP_EVENT_ATTACHMENT` | Tool to retrieve a specific attachment from an event within a calendar group for a user |
| `OUTLOOK_GET_USER_CHILD_FOLDER_MESSAGE` | Tool to retrieve a specific message from a child folder within a user's mail folder hierarchy |
| `OUTLOOK_GET_USER_EVENT_EXTENSION` | Tool to retrieve a specific open type extension from a user's calendar event by its extension ID or name |
| `OUTLOOK_GET_USER_MESSAGES_ATTACHMENTS` | Tool to retrieve a specific attachment from a message in a mail folder hierarchy |
| `OUTLOOK_LIST_CALENDAR_EVENT_ATTACHMENTS` | Tool to list attachments for a calendar event within a specific calendar for a user |
| `OUTLOOK_LIST_CALENDAR_GROUP_CALENDAR_EVENTS` | Tool to list events from a specific calendar within a calendar group for a user |
| `OUTLOOK_LIST_CALENDAR_GROUP_CALENDARS` | Tool to retrieve calendars belonging to a specific calendar group |
| `OUTLOOK_LIST_CALENDAR_GROUP_EVENT_ATTACHMENTS` | Tool to list attachments for a calendar event within a specific calendar group for a user |
| `OUTLOOK_LIST_CALENDAR_GROUPS` | Tool to list calendar groups in the signed-in user's mailbox |
| `OUTLOOK_LIST_CALENDAR_PERMISSIONS` | Tool to list calendar permissions for a specific calendar within a calendar group |
| `OUTLOOK_LIST_CALENDARS` | Tool to list calendars in the signed-in user's mailbox |
| `OUTLOOK_LIST_CALENDAR_VIEW_DELTA` | Tool to get calendar events that have been added, deleted, or updated in a calendar view |
| `OUTLOOK_LIST_CHAT_MESSAGES` | Tool to list messages in a Teams chat |
| `OUTLOOK_LIST_CHATS` | Tool to list Teams chats |
| `OUTLOOK_LIST_CHILD_FOLDER_CONTACTS` | Tool to retrieve contacts from a user's child contact folder |
| `OUTLOOK_LIST_CHILD_FOLDER_MESSAGES` | Tool to list messages from a child folder within a parent mail folder |
| `OUTLOOK_LIST_CHILD_MAIL_FOLDERS` | List a mail folder's immediate child folders, with property projection and paging controls |
| `OUTLOOK_LIST_CONTACT_FOLDER_CHILD_FOLDERS` | Tool to list child folders under a specified contact folder |
| `OUTLOOK_LIST_CONTACT_FOLDERS_DELTA` | Tool to get contact folders that have been added, deleted, or updated |
| `OUTLOOK_LIST_CONTACTS_DELTA` | Retrieve incremental changes (delta) of contacts in a specified folder |
| `OUTLOOK_LIST_EMAIL_RULES` | List all email rules from inbox |
| `OUTLOOK_LIST_EVENT_ATTACHMENTS` | Tool to list attachments for a specific Outlook calendar event |
| `OUTLOOK_LIST_EVENT_CALENDAR_CALENDAR_PERMISSIONS` | Tool to list calendar permissions for the calendar containing a specific event |
| `OUTLOOK_LIST_EVENT_INSTANCES` | Tool to retrieve individual occurrences of a recurring calendar event within a specified time range |
| `OUTLOOK_LIST_EVENTS` | Retrieves events from a user's Outlook calendar via Microsoft Graph API |
| `OUTLOOK_LIST_INFERENCE_CLASSIFICATION_OVERRIDES` | Tool to list inference classification overrides that control Focused Inbox sender rules |
| `OUTLOOK_LIST_MAIL_FOLDER_MESSAGE_ATTACHMENTS` | Tool to get attachments from a message in a specific mail folder |
| `OUTLOOK_LIST_MAIL_FOLDER_MESSAGE_RULES` | Tool to list message rules for a specific mail folder |
| `OUTLOOK_LIST_MAIL_FOLDER_MESSAGES` | Compatibility action that lists messages directly contained in one specified mail folder |
| `OUTLOOK_LIST_MAIL_FOLDERS` | List a user's top-level Outlook mail folders with property projection, hidden-folder control, and paging |
| `OUTLOOK_LIST_MAIL_FOLDERS_DELTA` | Tool to get incremental changes to mail folders |
| `OUTLOOK_LIST_ME_CALENDAR_PERMISSIONS` | Tool to list calendar permissions for a specific user's calendar |
| `OUTLOOK_LIST_MESSAGE_ATTACHMENTS_FROM_CHILD_FOLDER` | Tool to list attachments from a message in a nested child mail folder |
| `OUTLOOK_LIST_MESSAGES` | List or query Outlook messages from one folder (Inbox by default) or mailbox-wide with folder='allfolders' |
| `OUTLOOK_LIST_OUTLOOK_ATTACHMENTS` | List attachments for one Outlook email message |
| `OUTLOOK_LIST_PLACES` | Retrieves a collection of place objects defined in a tenant by type |
| `OUTLOOK_LIST_PRIMARY_CALENDAR_PERMISSIONS` | Tool to list calendar permissions from a user's primary calendar |
| `OUTLOOK_LIST_REMINDERS` | Tool to retrieve reminders for events occurring within a specified time range |
| `OUTLOOK_LIST_SENT_ITEMS_MESSAGES` | Tool to list all messages in the SentItems mail folder of the signed-in user's mailbox |
| `OUTLOOK_LIST_TO_DO_LISTS` | Tool to list Microsoft To Do task lists for the signed-in user |
| `OUTLOOK_LIST_TODO_TASKS` | Tool to list tasks within a specified Microsoft To Do task list, including status and due dates |
| `OUTLOOK_LIST_USER_CALENDAR_EVENT_INSTANCES` | Tool to retrieve instances (occurrences) of a recurring event from a specific calendar within a date range |
| `OUTLOOK_LIST_USER_CALENDAR_EVENTS_ATTACHMENTS` | Tool to list attachments for a user's calendar event |
| `OUTLOOK_LIST_USER_CALENDAR_GROUP_EVENT_INSTANCES` | Tool to list instances (occurrences) of a recurring event within a specified date range from a user's calendar in a calendar group |
| `OUTLOOK_LIST_USER_CALENDAR_GROUPS_CALENDAR_VIEW` | Tool to get calendar view from a specific calendar within a calendar group for a user |
| `OUTLOOK_LIST_USER_CALENDARS_CALENDAR_PERMISSIONS` | Tool to list calendar permissions for a specific user's specific calendar |
| `OUTLOOK_LIST_USER_CALENDARS_EVENTS` | Tool to retrieve events from a specific calendar for a user |
| `OUTLOOK_LIST_USER_CALENDAR_VIEW` | Tool to get calendar view from a specific user's calendar |
| `OUTLOOK_LIST_USER_CONTACTS` | Tool to retrieve contacts from a specific user's mailbox |
| `OUTLOOK_LIST_USERS` | Tool to list users in Microsoft Entra ID |
| `OUTLOOK_MOVE_MAIL_FOLDER` | Tool to move a mail folder and its contents to another mail folder |
| `OUTLOOK_MOVE_ME_MAIL_FOLDER` | Tool to move a child mail folder to a different parent folder |
| `OUTLOOK_MOVE_MESSAGE` | Move a message to another folder within the specified user's mailbox |
| `OUTLOOK_MOVE_MESSAGE_FROM_CHILD_FOLDER` | Tool to move a message from a child folder to another destination folder |
| `OUTLOOK_MOVE_MESSAGE_FROM_FOLDER` | Tool to move a message from a specific mail folder to another destination folder |
| `OUTLOOK_PERMANENT_DELETE_MESSAGE` | Permanently deletes an Outlook message by moving it to the Purges folder in the dumpster |
| `OUTLOOK_PIN_MESSAGE` | Tool to pin a message in an Outlook chat |
| `OUTLOOK_QUERY_EMAILS` | Query one Outlook mail folder with a validated raw OData filter |
| `OUTLOOK_REPLY_EMAIL` | Sends a reply to an Outlook email message with optional HTML formatting, attachments, CC, and BCC recipients |
| `OUTLOOK_SEARCH_EVENTS` | Searches for calendar events in the authenticated user's primary calendar using the Microsoft Graph Search API |
| `OUTLOOK_SEARCH_MESSAGES` | Search Outlook messages using powerful KQL syntax |
| `OUTLOOK_SEND_DRAFT` | Tool to send an existing draft message |
| `OUTLOOK_SEND_EMAIL` | Sends an email with subject, body, recipients, and optional attachments via Microsoft Graph API |
| `OUTLOOK_SNOOZE_CALENDAR_GROUP_EVENT_REMINDER` | Tool to snooze a reminder for a user's calendar event within a calendar group to a new time |
| `OUTLOOK_SNOOZE_EVENT_REMINDER` | Tool to postpone an event reminder until a new time |
| `OUTLOOK_SNOOZE_USER_CALENDAR_EVENT_REMINDER` | Tool to snooze a reminder for a calendar event in a specific user calendar to a new time |
| `OUTLOOK_SNOOZE_USER_EVENT_REMINDER` | Tool to snooze a reminder for a user's calendar event to a new time |
| `OUTLOOK_UPDATE_CALENDAR_EVENT` | Updates specified fields of an existing Outlook calendar event |
| `OUTLOOK_UPDATE_CALENDAR_EVENT_IN_CALENDAR` | Tool to update an event in a specific Outlook calendar |
| `OUTLOOK_UPDATE_CALENDAR_GROUP` | Tool to update the properties of a calendar group object |
| `OUTLOOK_UPDATE_CALENDAR_GROUP_CALENDAR_PERMISSION` | Tool to update a calendar permission within a calendar group |
| `OUTLOOK_UPDATE_CALENDAR_GROUPS_CALENDARS` | Tool to update a calendar within a calendar group in a user's mailbox |
| `OUTLOOK_UPDATE_CALENDAR_GROUPS_CALENDARS_EVENTS` | Tool to update an event in a calendar within a calendar group for a specific user |
| `OUTLOOK_UPDATE_CALENDAR_PERMISSION` | Tool to update calendar permission levels for share recipients or delegates |
| `OUTLOOK_UPDATE_CHILD_FOLDER_CONTACT` | Tool to update a contact in a child contact folder within a parent contact folder |
| `OUTLOOK_UPDATE_CONTACT` | Updates an existing Outlook contact, identified by `contact_id` for the specified `user_id`, requiring at least one other field to be modified |
| `OUTLOOK_UPDATE_CONTACT_FOLDER` | Tool to update the properties of a contact folder for a specific user |
| `OUTLOOK_UPDATE_CONTACT_FOLDER_CHILD_FOLDER` | Tool to update a child folder within a contact folder for a specific user |
| `OUTLOOK_UPDATE_CONTACT_FOLDERS_CONTACTS` | Tool to update a contact within a specific contact folder |
| `OUTLOOK_UPDATE_EMAIL` | Updates specified properties of an existing email message; `message_id` must identify a valid message within the specified `user_id`'s mailbox |
| `OUTLOOK_UPDATE_EMAIL_RULE` | Update an existing email rule |
| `OUTLOOK_UPDATE_EVENT_EXTENSION` | Tool to update an open extension on a calendar event in Microsoft Graph |
| `OUTLOOK_UPDATE_EVENT_EXTENSION_IN_CALENDAR_GROUP` | Tool to update an open extension on a calendar event within a calendar group |
| `OUTLOOK_UPDATE_INFERENCE_CLASSIFICATION` | Tool to update the inferenceClassification resource for a user |
| `OUTLOOK_UPDATE_MAILBOX_SETTINGS` | Tool to update mailbox settings for the signed-in user |
| `OUTLOOK_UPDATE_MAIL_FOLDER` | Tool to update the display name of a mail folder |
| `OUTLOOK_UPDATE_MASTER_CATEGORY` | Tool to update the color of a category in the user's master category list |
| `OUTLOOK_UPDATE_ME_CONTACTS_EXTENSIONS` | Tool to update an open extension on a contact in a contact folder |
| `OUTLOOK_UPDATE_TODO_TASK` | Tool to update an existing task in Microsoft To Do |
| `OUTLOOK_UPDATE_USER_CALENDAR` | Tool to update the properties of a user's calendar |
| `OUTLOOK_UPDATE_USER_CALENDAR_EVENT` | Tool to update an event in a specific user's calendar |
| `OUTLOOK_UPDATE_USER_CALENDAR_PERMISSION` | Tool to update calendar permission levels for a specific user's calendar |
| `OUTLOOK_UPDATE_USER_CALENDARS` | Tool to update properties of a specific calendar by ID for a specific user |
| `OUTLOOK_UPDATE_USER_CHILD_FOLDER_MESSAGE` | Tool to update a message in a child folder within a user's mailbox |
| `OUTLOOK_UPDATE_USER_CONTACT_EXTENSION` | Tool to update an open extension on a contact in a user's contact folder |
| `OUTLOOK_UPDATE_USER_CONTACTS_EXTENSIONS` | Tool to update an open extension on a contact in a user's contact folder |
| `OUTLOOK_UPDATE_USER_CONTACTS_EXTENSIONS_DIRECT` | Tool to update an open extension on a contact directly under a user's contacts collection |
| `OUTLOOK_UPDATE_USER_EVENTS_EXTENSIONS` | Tool to update an open extension on a user's calendar event |
| `OUTLOOK_UPDATE_USER_INFERENCE_CLASSIFICATION_OVERRIDE` | Tool to update the classification of messages from a specific sender in a user's Focused Inbox |
| `OUTLOOK_UPDATE_USER_MAIL_FOLDER_MESSAGE` | Tool to update properties of a message in a specific mail folder for a user |
| `OUTLOOK_UPDATE_USER_MAIL_FOLDER_MESSAGE_EXTENSION` | Tool to update an open extension on a message within a specific user's mail folder |
| `OUTLOOK_UPDATE_USER_MAIL_FOLDER_MESSAGE_RULE` | Tool to update a message rule in a user's mail folder |
| `OUTLOOK_UPDATE_USER_MAIL_FOLDERS_CHILD_FOLDERS` | Tool to update a child folder within a mail folder for a specific user |
| `OUTLOOK_UPDATE_USER_MESSAGE_EXTENSION` | Tool to update an open extension on a user's message |
| `OUTLOOK_WHO_AM_I` | Return the identity (email, name) of the connected Outlook account |
