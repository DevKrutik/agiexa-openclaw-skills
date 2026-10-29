# Slack tools via Agiexa (159)

Preview only - these become available to the agent after Agiexa launches (November 2026) and the merchant connects Slack and turns the tools on. They cannot be called today.

Interactive explorer: https://agiexa.com/integrations/slack

| Tool | What it does |
| --- | --- |
| `SLACK_ADD_CALL_PARTICIPANTS` | Registers new participants added to a Slack call |
| `SLACK_ADD_EMOJI` | Adds a custom emoji to a Slack workspace given a unique name and an image URL; subject to workspace emoji limits |
| `SLACK_ADD_EMOJI_ALIAS` | Adds an alias for an existing custom emoji in a Slack Enterprise Grid organization |
| `SLACK_ADD_ENTERPRISE_USER_TO_WORKSPACE` | Adds an Enterprise user to a workspace |
| `SLACK_ADD_REACTION_TO_AN_ITEM` | Adds a specified emoji reaction to an existing message in a Slack channel, identified by its timestamp; does not remove or retrieve reactions |
| `SLACK_ADD_REMOTE_FILE` | Adds a reference to an external file (e.g., Google Drive, Dropbox) to Slack for discovery and sharing, requiring a unique `external_id` and an `extern |
| `SLACK_ADD_STAR` | Stars a channel, file, file comment, or a specific message in Slack |
| `SLACK_ADMIN_CONVERSATIONS_SEARCH` | Tool to search for public or private channels in an Enterprise organization |
| `SLACK_API_TEST` | Tool to check API calling code by testing connectivity and authentication to the Slack API |
| `SLACK_ARCHIVE_CONVERSATION` | Archives a Slack conversation by its ID, rendering it read-only and hidden while retaining history, ideal for cleaning up inactive channels; be aware |
| `SLACK_ASSISTANT_SEARCH_CONTEXT` | Search Slack messages, files, channels, and users via Real-time Search API |
| `SLACK_ASSISTANT_SEARCH_INFO` | Check if semantic (AI-powered) search is available on the Slack workspace |
| `SLACK_CLOSE_DM` | Closes a Slack direct message (DM) or multi-person direct message (MPDM) channel, removing it from the user's sidebar without deleting history; this a |
| `SLACK_CONVERT_CHANNEL_TO_PRIVATE` | Convert a public Slack channel to private using the Admin API |
| `SLACK_CREATE_A_REMINDER` | Creates a Slack reminder with specified text and time; time accepts Unix timestamps, seconds from now, or natural language (e.g., 'in 15 minutes', 'ev |
| `SLACK_CREATE_CANVAS` | Creates a new Slack Canvas with the specified title and optional content |
| `SLACK_LIST_WORKSPACE_USERS` | Retrieves a paginated list of admin users for a specified Slack workspace |
| `SLACK_CREATE_CHANNEL` | Initiates a public or private channel-based conversation in a Slack workspace |
| `SLACK_CREATE_CHANNEL_BASED_CONVERSATION` | Creates a new public or private Slack channel with a unique name; the channel can be org-wide, or team-specific if `team_id` is given (required if `or |
| `SLACK_CREATE_ENTERPRISE_TEAM` | Tool to create an Enterprise team in Slack |
| `SLACK_LOOKUP_CANVAS_SECTIONS` | Looks up section IDs in a Slack Canvas for use with targeted edit operations |
| `SLACK_REVOKE_FILE_PUBLIC_SHARING` | Revokes a Slack file's public URL, making it private; this is a no-op if not already public and is irreversible |
| `SLACK_RTM_CONNECT` | Starts a Real Time Messaging session and returns a WebSocket URL |
| `SLACK_SCHEDULE_MESSAGE` | Schedules a message to a Slack channel, DM, or private group for a future time (`post_at`), requiring `text`, `blocks`, or `attachments` for content; |
| `SLACK_CREATE_SLACK_LIST` | Creates a new Slack List via `slackLists.create` |
| `SLACK_CREATE_SLACK_LIST_ITEM` | Creates a new item (row) in a Slack List via `slackLists.items.create` |
| `SLACK_CREATE_USER_GROUP` | Creates a new User Group (often referred to as a subteam) in a Slack workspace |
| `SLACK_CUSTOMIZE_URL_UNFURL` | Customizes URL previews (unfurling) in a specific Slack message using a URL-encoded JSON in `unfurls` to define custom content or remove existing prev |
| `SLACK_DELETE_CANVAS` | Deletes a Slack Canvas permanently and irreversibly |
| `SLACK_DELETE_CHANNEL` | Permanently and irreversibly deletes a specified public or private channel, including all its messages and files, within a Slack Enterprise Grid organ |
| `SLACK_DELETE_FILE` | Permanently deletes an existing file from a Slack workspace using its unique file ID; this action is irreversible and also removes any associated comm |
| `SLACK_DELETE_FILE_COMMENT` | Deletes a specific comment from a file in Slack; this action is irreversible |
| `SLACK_DELETE_MULTIPLE_SLACK_LIST_ITEMS` | Deletes several items (rows) from a Slack List in one call via `slackLists.items.deleteMultiple` |
| `SLACK_DELETE_REMINDER` | Deletes an existing Slack reminder, typically when it is no longer relevant or a task is completed; this operation is irreversible |
| `SLACK_DELETES_A_MESSAGE_FROM_A_CHAT` | Deletes a message, identified by its channel ID and timestamp, from a Slack channel, private group, or direct message conversation; the authenticated |
| `SLACK_DELETE_SCHEDULED_MESSAGE` | Deletes a pending, unsent scheduled message from the specified Slack channel, identified by its `scheduled_message_id` |
| `SLACK_DELETE_SLACK_LIST_ACCESS` | Revokes sharing access on a Slack List via `slackLists.access.delete` |
| `SLACK_DELETE_SLACK_LIST_ITEM` | Deletes an item (row) from a Slack List via `slackLists.items.delete` |
| `SLACK_DELETE_USER_PROFILE_PHOTO` | Deletes the Slack profile photo for the user identified by the token, reverting them to the default avatar; this action is irreversible and succeeds e |
| `SLACK_DISABLE_USER_GROUP` | Disables a specified, currently enabled Slack User Group by its unique ID, effectively archiving it by setting its 'date_delete' timestamp; the group |
| `SLACK_DOWNLOAD_SLACK_FILE` | Tool to download Slack file content and convert it to a publicly accessible URL |
| `SLACK_EDIT_CANVAS` | Edits a Slack Canvas with granular control over content placement |
| `SLACK_ENABLE_PUBLIC_SHARING_OF_A_FILE` | Enables public sharing for an existing Slack file by generating a publicly accessible URL; this action does not create new files |
| `SLACK_ENABLE_USER_GROUP` | Enables a disabled User Group in Slack using its ID, reactivating it for mentions and permissions; this action only changes the enabled status and can |
| `SLACK_END_CALL` | Ends an ongoing Slack call, identified by its ID (obtained from `calls.add`), optionally specifying the call's duration |
| `SLACK_END_DND` | Ends the authenticated user's current Do Not Disturb (DND) session in Slack, affecting only DND status and making them available; if DND is not active |
| `SLACK_END_SNOOZE` | Ends the current user's snooze mode immediately |
| `SLACK_FETCH_CONVERSATION_HISTORY` | Fetches a chronological list of messages and events from a specified Slack conversation, accessible by the authenticated user/bot, with options for pa |
| `SLACK_FETCH_ITEM_REACTIONS` | Fetches reactions for a Slack message, file, or file comment |
| `SLACK_FETCH_MESSAGE_THREAD_FROM_A_CONVERSATION` | Retrieves replies to a specific parent message in a Slack conversation, using the channel ID and the parent message's timestamp (`ts`) |
| `SLACK_FETCH_TEAM_INFO` | Fetches comprehensive metadata about the current Slack team, or a specified team if the provided ID is accessible |
| `SLACK_FIND_CHANNELS` | Find channels in a Slack workspace by any criteria - name, topic, purpose, or description |
| `SLACK_FIND_USER_BY_EMAIL_ADDRESS` | Retrieves the Slack user object for an active user by their registered email address; requires the users:read.email OAuth scope |
| `SLACK_FIND_USERS` | Find users in a Slack workspace by any criteria - email, name, display name, or other text |
| `SLACK_GET_AUDIT_ACTION_TYPES` | Tool to retrieve information about action types available in the Slack Audit Logs API |
| `SLACK_GET_AUDIT_SCHEMAS` | Tool to retrieve object schema information from the Slack Audit Logs API |
| `SLACK_GET_BOT_USER` | Fetches information for a specified, existing Slack bot user; will not work for regular user accounts or other integration types |
| `SLACK_GET_CALL_INFO` | Retrieves a point-in-time snapshot of a specific Slack call's information |
| `SLACK_GET_CHANNEL_CONVERSATION_PREFERENCES` | Retrieves conversation preferences (e.g., who can post, who can thread) for a specified channel, primarily for use within Slack Enterprise Grid enviro |
| `SLACK_GET_REMINDER` | Retrieves detailed information for an existing Slack reminder specified by its ID; this is a read-only operation |
| `SLACK_GET_REMOTE_FILE` | Retrieve information about a remote file added to Slack via the files.remote API |
| `SLACK_GET_SLACK_LIST_ITEM` | Fetches a single item (row) from a Slack List via `slackLists.items.info` |
| `SLACK_GET_TEAM_PROFILE` | Retrieves all profile field definitions for a Slack team, optionally filtered by visibility, to understand the team's profile structure |
| `SLACK_LIST_USER_REACTIONS` | Lists all reactions added by a specific user to messages, files, or file comments in Slack, useful for engagement analysis when the item content itsel |
| `SLACK_GET_UNREAD_MESSAGES_FROM_USER` | Retrieves unread direct messages from a specific user by opening their DM conversation, checking for unread messages, and fetching message history sin |
| `SLACK_GET_USER_DND_STATUS` | Retrieves a user's current Do Not Disturb status |
| `SLACK_GET_USER_PRESENCE` | Retrieves a Slack user's current real-time presence (e.g., 'active', 'away') to determine their availability, noting this action does not provide hist |
| `SLACK_GET_WORKSPACE_CONNECTIONS_FOR_CHANNEL` | Tool to get all workspaces a channel is connected to within an Enterprise org |
| `SLACK_GET_WORKSPACE_SETTINGS` | Retrieves detailed settings for a specific Slack workspace, primarily for administrators in an Enterprise Grid organization to view or audit workspace |
| `SLACK_INVITE_USERS_TO_A_SLACK_CHANNEL` | Invites users to an existing Slack channel using their valid Slack User IDs |
| `SLACK_INVITE_USER_TO_CHANNEL` | Invites users to a specified Slack channel; this action is restricted to Enterprise Grid workspaces and requires the authenticated user to be a member |
| `SLACK_INVITE_USER_TO_WORKSPACE` | Invites a user to a Slack workspace and specified channels by email; use `resend=True` to re-process an existing invitation for a user not yet signed |
| `SLACK_JOIN_AN_EXISTING_CONVERSATION` | Joins an existing Slack conversation (public channel, private channel, or multi-person direct message) by its ID, if the authenticated user has permis |
| `SLACK_LEAVE_CONVERSATION` | Leaves a Slack conversation given its channel ID; fails if leaving as the last member of a private channel or if used on a Slack Connect channel |
| `SLACK_LIST_ADMIN_APPS_APPROVED` | Tool to list approved apps for an Enterprise Grid organization or workspace |
| `SLACK_LIST_ADMIN_APPS_REQUESTS` | Tool to list pending app installation requests for a team/workspace |
| `SLACK_LIST_ADMIN_EMOJI` | List custom emoji across an Enterprise Grid organization |
| `SLACK_LIST_ALL_CHANNELS` | Lists conversations available to the user with various filters and search options |
| `SLACK_LIST_ALL_USERS` | Retrieves a paginated list of all users with profile details, status, and team memberships in a Slack workspace; data may not be real-time |
| `SLACK_LIST_APPROVED_WORKSPACE_INVITE_REQUESTS` | List all approved workspace invite requests with pagination support |
| `SLACK_LIST_AUTH_TEAMS` | Obtains a paginated list of workspaces your org-wide app has been approved for |
| `SLACK_LIST_WORKSPACE_ADMINS` | Tool to list all admins on a given Slack workspace |
| `SLACK_LIST_AVAILABLE_WORKSPACES` | List Slack workspaces where both the connection and target user have access |
| `SLACK_LIST_CONVERSATIONS` | List conversations (channels/DMs) accessible to a specified user (or the authenticated user if no user ID is provided), respecting shared membership f |
| `SLACK_LIST_CUSTOM_EMOJIS` | Retrieves all custom emojis for the Slack workspace (image URLs or aliases), not standard Unicode emojis; does not include usage statistics or creatio |
| `SLACK_LIST_DENIED_WORKSPACE_INVITE_REQUESTS` | Tool to list all denied workspace invite requests with details about who denied them and when |
| `SLACK_LIST_ENTERPRISE_TEAMS` | List all teams (workspaces) in a Slack Enterprise Grid organization with pagination support |
| `SLACK_LIST_FILES_WITH_FILTERS_IN_SLACK` | Lists files and their metadata within a Slack workspace, filterable by user, channel, timestamp, or type; returns metadata only, not file content |
| `SLACK_LIST_IDP_GROUPS_LINKED_TO_CHANNEL` | Lists IDP groups that have restricted access to a private Slack channel |
| `SLACK_LIST_PENDING_WORKSPACE_INVITE_REQUESTS` | Tool to list all pending workspace invite requests |
| `SLACK_LIST_PINNED_ITEMS` | Retrieves all messages and files pinned to a specified channel; the caller must have access to this channel |
| `SLACK_LIST_REMINDERS` | Lists all reminders with their details for the authenticated Slack user; returns an empty array if no reminders exist (valid state, not an error) |
| `SLACK_LIST_REMOTE_FILES` | Retrieve information about a team's remote files |
| `SLACK_LIST_RESTRICTED_APPS` | Tool to list restricted apps for an org or workspace |
| `SLACK_LIST_SCHEDULED_MESSAGES` | Retrieves a list of pending (not yet delivered) messages scheduled in a specific Slack channel, or across all accessible channels if no channel ID is |
| `SLACK_LIST_SLACK_LIST_ITEMS` | Lists the rows (items) in a Slack List via `slackLists.items.list` |
| `SLACK_LIST_STARRED_ITEMS` | Lists items starred by a user |
| `SLACK_LIST_UNREAD_CHANNEL_MESSAGES` | Lists all unread messages in a specified Slack channel for the authenticated user |
| `SLACK_LIST_USER_GROUP_MEMBERS` | Retrieves a list of all user IDs within a specified Slack user group, with an option to include users from disabled groups |
| `SLACK_LIST_USER_GROUPS` | Lists user groups in a Slack workspace, including user-created and default groups; results for large workspaces may be paginated |
| `SLACK_LIST_WORKSPACE_OWNERS` | Tool to list all owners on a given Slack workspace |
| `SLACK_OPEN_DM` | Opens or resumes a Slack direct message (DM) or multi-person direct message (MPIM) by providing either user IDs or an existing channel ID |
| `SLACK_PIN_ITEM` | Pins a message to a specified Slack channel; the message must not already be pinned |
| `SLACK_READ_AUDIT_LOGS` | Read Slack Enterprise Grid Audit Logs (logins, admin changes, app installs, channel/privacy changes, etc.) with server-side filters and pagination |
| `SLACK_REMOVE_CALL_PARTICIPANTS` | Registers participants removed from a Slack call |
| `SLACK_REMOVE_EMOJI` | Tool to remove a custom emoji across an Enterprise Grid organization |
| `SLACK_REMOVE_REACTION_FROM_ITEM` | Removes an emoji reaction from a message, file, or file comment in Slack |
| `SLACK_REMOVE_REMOTE_FILE` | Removes the Slack reference to an external file (which must have been previously added via the remote files API), specified by either its `external_id |
| `SLACK_REMOVE_STAR` | Removes a star from a previously starred Slack item (message, file, file comment, channel, group, or DM), requiring identification via `file`, `file_c |
| `SLACK_REMOVE_USER_FROM_CONVERSATION` | Removes a specified user from a Slack conversation (channel); the caller must have permissions to remove users and cannot remove themselves using this |
| `SLACK_REMOVE_USER_FROM_WORKSPACE` | Tool to remove a user from a Slack workspace |
| `SLACK_RENAME_CONVERSATION` | Renames a Slack channel, automatically adjusting the new name to meet naming conventions (e.g., converting to lowercase), which may affect integration |
| `SLACK_RENAME_EMOJI` | Renames an existing custom emoji in a Slack workspace, updating all its instances |
| `SLACK_RESET_USER_SESSIONS` | Tool to wipe all valid sessions on all devices for a given user |
| `SLACK_RESTRICT_APP_INSTALLATION` | Restrict an app for installation on a workspace |
| `SLACK_RETRIEVE_A_USER_S_IDENTITY_DETAILS` | Retrieves the authenticated user's and their team's identity, with details varying based on OAuth scopes (e.g., `identity.basic`, `identity.email`, `i |
| `SLACK_RETRIEVE_CONVERSATION_INFORMATION` | Retrieves metadata for a Slack conversation by ID (e.g., name, purpose, creation date, with options for member count/locale), excluding message conten |
| `SLACK_RETRIEVE_CONVERSATION_MEMBERS_LIST` | Retrieves a paginated list of active member IDs (not names, emails, or presence) for a specified Slack public channel, private channel, DM, or MPIM |
| `SLACK_RETRIEVE_CURRENT_USER_DND_STATUS` | Retrieves a Slack user's current Do Not Disturb (DND) status to determine their availability before interaction; any specified user ID must be a valid |
| `SLACK_RETRIEVE_DETAILED_INFORMATION_ABOUT_A_FILE` | Retrieves detailed metadata and paginated comments for a specific Slack file ID; does not download file content |
| `SLACK_RETRIEVE_DETAILED_USER_INFORMATION` | Retrieves comprehensive information for a valid Slack user ID, excluding message history and channel memberships |
| `SLACK_RETRIEVE_MESSAGE_PERMALINK_URL` | Retrieves a permalink URL for a specific message in a Slack channel or conversation; the permalink respects Slack's privacy settings |
| `SLACK_RETRIEVE_USER_PROFILE_INFORMATION` | Retrieves profile information for a specified Slack user (defaults to the authenticated user if `user` ID is omitted); a provided `user` ID must be va |
| `SLACK_SCIM_GET_CONFIG` | Tool to retrieve SCIM service provider configuration from Slack |
| `SLACK_SEARCH_ALL` | Tool to search all messages and files |
| `SLACK_SEARCH_MESSAGES` | Workspace‑wide Slack message search with date ranges and filters |
| `SLACK_SEND_EPHEMERAL_MESSAGE` | Sends an ephemeral message visible only to the specified `user` in a channel; other channel members cannot see it |
| `SLACK_SEND_ME_MESSAGE` | Sends a 'me message' (e.g., '/me is typing') to a Slack channel, where it's displayed as a third-person user action; messages are plain text and the c |
| `SLACK_SEND_MESSAGE` | Posts a message to a Slack channel, DM, or private group |
| `SLACK_SET_ADMIN_USER` | Promotes an existing workspace member (guest, regular user, or owner) to admin status |
| `SLACK_SET_CONVERSATION_PREFS` | Sets the posting permissions for a public or private channel in Slack |
| `SLACK_SET_CONVERSATION_PURPOSE` | Sets the purpose (a short description of its topic/goal, displayed in the header) for a Slack conversation; the calling user must be a member |
| `SLACK_SET_DEFAULT_CHANNELS` | Tool to set the default channels of a workspace |
| `SLACK_SET_DND_DURATION` | Turns on Do Not Disturb mode for the current user, or changes its duration |
| `SLACK_SET_PROFILE_PHOTO` | This method allows the user to set their profile image |
| `SLACK_SET_READ_CURSOR_IN_A_CONVERSATION` | Marks a message, specified by its timestamp (`ts`), as the most recently read for the authenticated user in the given `channel`, provided the user is |
| `SLACK_SET_SLACK_LIST_ACCESS` | Grants or sets sharing access on a Slack List via `slackLists.access.set` |
| `SLACK_SET_THE_TOPIC_OF_A_CONVERSATION` | Sets or updates the topic for a specified Slack conversation |
| `SLACK_SET_USER_PRESENCE` | Manually sets a user's Slack presence, overriding automatic detection; this setting persists across connections but can be overridden by user actions |
| `SLACK_SET_USER_PROFILE` | Updates a Slack user's profile, setting either individual fields or multiple fields via a JSON object |
| `SLACK_SET_WORKSPACE_DESCRIPTION` | Set the description of a given workspace |
| `SLACK_SET_WORKSPACE_ICON` | Sets the icon of a workspace |
| `SLACK_SET_WORKSPACE_NAME` | Set the name of a given Slack workspace |
| `SLACK_SET_WORKSPACE_OWNER` | Set an existing guest, regular user, or admin user to be a workspace owner |
| `SLACK_SET_WORKSPACES_FOR_CHANNEL` | Set the workspaces in an Enterprise grid org that connect to a channel |
| `SLACK_SHARE_REMOTE_FILE` | Shares a remote file, which must already be registered with Slack, into specified Slack channels or direct message conversations |
| `SLACK_START_CALL` | Registers a new call in Slack using `calls.add` for third-party call integration; `created_by` is required if not using a user-specific token |
| `SLACK_TEST_AUTH` | Checks authentication and tells you who you are |
| `SLACK_UNARCHIVE_CHANNEL` | Reverses conversation archival |
| `SLACK_UNPIN_ITEM` | Unpins a message, identified by its timestamp, from a specified channel if the message is currently pinned there; this operation is destructive |
| `SLACK_UPDATE_CALL_INFO` | Updates the title, join URL, or desktop app join URL for an existing Slack call identified by its ID |
| `SLACK_UPDATE_REMOTE_FILE` | Updates metadata or content details for an existing remote file in Slack; this action cannot upload new files or change the fundamental file type |
| `SLACK_UPDATES_A_SLACK_MESSAGE` | Updates a Slack message by timestamp |
| `SLACK_UPDATE_SLACK_LIST` | Updates a Slack List's metadata via `slackLists.update` |
| `SLACK_UPDATE_SLACK_LIST_ITEM` | Updates one or more cells in an EXISTING Slack List row via `slackLists.items.update` |
| `SLACK_UPDATE_USER_GROUP` | Updates an existing Slack User Group, which must be specified by an existing `usergroup` ID, with new optional details such as its name, description, |
| `SLACK_UPDATE_USER_GROUP_MEMBERS` | Replaces all members of an existing Slack User Group with a new list of valid user IDs |
| `SLACK_UPLOAD_OR_CREATE_A_FILE_IN_SLACK` | Upload files, images, screenshots, documents, or any media to Slack channels or threads |
| `SLACK_WHO_AM_I` | Return the identity (user + workspace) of the connected Slack account |
