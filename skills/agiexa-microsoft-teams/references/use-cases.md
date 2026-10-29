# Microsoft Teams use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/microsoft-teams

## Summarize Important Team Discussions

Turn lengthy conversations into concise summaries of decisions, blockers, and important updates.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_TEAMS_LIST_CHANNEL_MESSAGES`, `MICROSOFT_TEAMS_SEARCH_MESSAGES`, `MICROSOFT_TEAMS_LIST_MESSAGE_REPLIES`

> Review the accessible Microsoft Teams channels and conversations from the last seven days. Summarize the most important discussions, decisions, risks, blockers, and unresolved questions. Organize the findings by project or business area. For each decision, include the relevant context and source message when identifiable. Separate confirmed decisions from suggestions, assumptions, and inferred conclusions. Highlight conflicting statements, missing information, and topics that need follow-up. Avoid treating every message as a commitment, and do not invent decisions, owners, or deadlines. Provide a concise executive summary followed by detailed findings and recommended next steps. Do not post messages or modify Teams content.

## Extract Action Items and Deadlines

Identify tasks hidden across conversations and organize them into a practical follow-up list.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_SEARCH_MESSAGES`, `MICROSOFT_TEAMS_LIST_MESSAGE_REPLIES`

> Search the accessible Microsoft Teams messages and replies from the last seven days for action items, commitments, follow-ups, blockers, and deadlines. Create a table containing the task, source discussion, explicitly assigned owner, stated deadline, current status if known, and any dependencies. Clearly label owners or deadlines that are inferred or missing rather than presenting them as confirmed facts. Group tasks by project and urgency. Highlight overdue items only when the stated deadline and current date support that conclusion. Recommend which tasks need clarification or escalation. Do not assign tasks, send reminders, or post updates on behalf of the team without my approval.

## Prepare Project Status Reports Automatically

Consolidate project discussions into a clear report covering progress, risks, and upcoming milestones.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_TEAMS_LIST_CHANNEL_MESSAGES`, `MICROSOFT_TEAMS_LIST_MEETING_TRANSCRIPTS`, `MICROSOFT_TEAMS_SEARCH_MESSAGES`

> Prepare a project status report using the relevant Microsoft Teams channels, messages, replies, and available meeting transcripts. Include project objectives, completed work, work in progress, upcoming milestones, blockers, decisions, dependencies, and unresolved questions. Organize the report using Green, Amber, and Red status labels only when the available evidence supports those assessments. For each major finding, include the supporting discussion or meeting context. Distinguish actual progress from planned work and flag stale or contradictory updates. End with the five most important next actions and any decisions needed from management. Do not create or send a report in Teams until I approve the final content and destination.

## Search Historical Messages and Files

Find previous decisions, project documents, and discussions without manually searching multiple channels.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_SEARCH_MESSAGES`, `MICROSOFT_TEAMS_SEARCH_FILES`

> Search the accessible Microsoft Teams messages and files for information about a topic or project I specify. Look for relevant keywords, related discussions, shared documents, and replies. Return the most relevant results with the team or channel, message or file details, available timestamps, and a short explanation of relevance. Prioritize direct evidence over assumptions. If multiple messages contradict each other, present the conflicting information and identify which appears most recent without automatically treating it as authoritative. If no reliable result is found, explain what was searched and what remains unavailable. Do not invent filenames, links, messages, or conclusions.

## Generate Meeting Agendas from Discussions

Convert unresolved questions and team priorities into a focused meeting agenda.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_SEARCH_MESSAGES`, `MICROSOFT_TEAMS_TEAMS_LIST_CHANNEL_MESSAGES`

> Review the recent Microsoft Teams discussions for the project or business area I specify and prepare a 30-minute meeting agenda. Identify unresolved decisions, blockers, dependencies, and action items that require discussion. For each agenda item, include the objective, supporting context, desired outcome, and suggested time allocation. Ensure the total duration is 30 minutes. Prioritize decisions that are blocking progress and avoid spending meeting time on topics that can be resolved through a simple written update. Provide a proposed meeting title and attendee roles based on explicit context where possible. Do not assume attendee availability or schedule the meeting. Present the agenda for approval first.

## Review Meeting Transcripts and Recordings

Extract key takeaways and commitments from available meeting transcripts and recordings.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_LIST_MEETING_TRANSCRIPTS`, `MICROSOFT_TEAMS_GET_MEETING_TRANSCRIPT_CONTENT`, `MICROSOFT_TEAMS_LIST_MEETING_RECORDINGS`

> Review the available Microsoft Teams meeting transcripts for the meeting name or date I specify. Summarize the purpose, key discussion points, decisions, open questions, risks, and action items. Attribute statements to speakers when speaker information is available and reliable. Distinguish what participants explicitly agreed on from ideas that were merely discussed. Include timestamps or identifiable transcript context where available. If a recording or transcript is unavailable, say so instead of assuming what happened. Create a concise meeting summary followed by a task table with confirmed owners and deadlines. Do not send the summary to participants or create tasks without approval.

## Coordinate Teams and Channel Membership

Review team structures and prepare membership changes for projects or departments.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_LIST_TEAM_MEMBERS`, `MICROSOFT_TEAMS_TEAMS_LIST_CHANNELS`, `MICROSOFT_TEAMS_ADD_TEAM_MEMBER`, `MICROSOFT_TEAMS_REMOVE_TEAM_MEMBER`

> Review the accessible Microsoft Teams teams, channels, and member lists for the project or department I specify. Help me determine whether the current structure supports the intended collaboration. Identify potential gaps, duplicate team structures, unclear channel purposes, or membership questions that require review. Prepare a proposed change list containing the team or channel, intended action, affected members, reason, and potential impact. Use only identities and membership details that can be verified from the available workspace. Do not add or remove members, create or delete teams, change roles, or archive channels until I explicitly approve each proposed change. Flag any action that could affect access to sensitive information.

## Coordinate Staff Shifts and Time Off

Review team schedules, shift requests, and staffing gaps to help managers plan coverage.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_LIST_SHIFTS`, `MICROSOFT_TEAMS_LIST_OPEN_SHIFTS`, `MICROSOFT_TEAMS_LIST_TIME_OFF_REQUESTS`, `MICROSOFT_TEAMS_LIST_OFFER_SHIFT_REQUESTS`

> Review the available Microsoft Teams schedule information for the team and date range I specify. Summarize scheduled shifts, open shifts, shift-change requests, time-off requests, and potential staffing gaps. Include relevant dates, times, scheduling groups, and request statuses where available. Flag overlapping assignments, uncovered periods, and requests that may require manager attention. Do not assume a request has been approved merely because it appears in the schedule. Recommend possible coverage options based on the available information, while respecting existing assignments and approval requirements. Do not create, modify, approve, or delete shifts or time-off records without my explicit approval.

## Create and Coordinate Team Meetings

Prepare meeting invitations and coordinate participants around a specific business objective.

- Apps: Microsoft Teams, Google Calendar
- Tools: `MICROSOFT_TEAMS_CREATE_OR_GET_ONLINE_MEETING`, `MICROSOFT_TEAMS_CREATE_MEETING`, `MICROSOFT_TEAMS_LIST_ONLINE_MEETINGS`

> Help me arrange a Microsoft Teams meeting about the topic and participants I specify. First, prepare a proposed meeting title, agenda, duration, required attendees, optional attendees, and desired outcomes. Ask for a date, time, and time zone if they are not specified. If calendar availability is accessible through an authorized integration, check for conflicts before recommending a slot. Avoid duplicating an existing meeting for the same purpose. Clearly distinguish a proposed time from a confirmed booking. Before creating the meeting, confirm the final time, duration, attendees, and agenda with me. Do not invite participants, change existing meetings, or cancel meetings without approval.

## Draft Team Announcements and Updates

Prepare clear internal messages for launches, incidents, policy changes, and important project milestones.

- Apps: Microsoft Teams
- Tools: `MICROSOFT_TEAMS_TEAMS_POST_CHANNEL_MESSAGE`, `MICROSOFT_TEAMS_PIN_MESSAGE`, `MICROSOFT_TEAMS_SEND_ACTIVITY_NOTIFICATION`

> Draft a Microsoft Teams announcement about the topic I specify for the team or channel I choose. Use the relevant accessible discussions and documents to establish the facts. Structure the message with a clear headline, concise context, important updates, required actions, confirmed owners and deadlines, and a contact or escalation path where known. Match the tone to the situation: direct and practical for operational updates, calm and factual for incidents, and positive for milestones. Do not invent approvals, promises, deadlines, or completed work. Provide a polished message ready for review and identify any missing details that could make it misleading. Do not post it, send activity notifications, pin messages, or edit existing messages until I approve the exact content and destination.
