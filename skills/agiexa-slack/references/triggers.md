# Slack triggers via Agiexa (9)

Preview only - events that will be able to start an agent run after Agiexa launches (November 2026).

| Trigger | When it fires |
| --- | --- |
| `SLACK_CHANNEL_CREATED` | Triggered when a new channel is created in Slack |
| `SLACK_CHANNEL_MESSAGE_RECEIVED` | Triggered when a message is posted in a Slack channel (public, private, or multi-party IM) |
| `SLACK_DIRECT_MESSAGE_RECEIVED` | Triggered when a new direct message (DM) is sent to a user in Slack |
| `SLACK_MESSAGE_REACTION_REMOVED` | Triggered when a reaction is removed from a message in Slack |
| `SLACK_REACTION_ADDED` | DEPRECATED: use `SLACK_MESSAGE_REACTION_ADDED` instead |
| `SLACK_REACTION_REMOVED` | DEPRECATED: use `SLACK_MESSAGE_REACTION_REMOVED` instead |
| `SLACK_RECEIVE_MESSAGE` | DEPRECATED: use `SLACK_CHANNEL_MESSAGE_RECEIVED` instead |
| `SLACK_MESSAGE_REACTION_ADDED` | Triggered when a reaction is added to a message in Slack |
| `SLACK_RECEIVE_BOT_MESSAGE` | DEPRECATED: use `SLACK_CHANNEL_MESSAGE_RECEIVED` with `is_bot_message=true` instead |
