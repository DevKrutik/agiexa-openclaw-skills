# Outlook use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/outlook

## Prioritize Important Emails Every Morning

Identify urgent messages, pending replies, and important follow-ups to start each day with clear priorities.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_MESSAGES`, `OUTLOOK_QUERY_EMAILS`, `OUTLOOK_LIST_SENT_ITEMS_MESSAGES`

> Review my Outlook inbox and relevant recent sent messages. Identify the emails that need my attention today. Categorize messages into urgent, important, waiting for my reply, follow-up required, and informational. Consider explicit deadlines, sender requests, business impact, and whether a message is blocking another person. For each important email, summarize the request, relevant context, deadline if explicitly stated, and recommended next action. Distinguish confirmed urgency from inferred priority and avoid treating promotional messages as important merely because they use urgent language. Provide a prioritized action list and draft replies for the most important messages where useful. Do not send emails, move messages, or mark items as read without my approval.

## Summarize Long Email Conversations Quickly

Turn lengthy email threads into concise summaries of decisions, requests, and outstanding questions.

- Apps: Outlook
- Tools: `OUTLOOK_SEARCH_MESSAGES`, `OUTLOOK_GET_MESSAGE`, `OUTLOOK_LIST_MESSAGES`

> Find and summarize the email conversation about the topic, sender, or subject I specify. Review the relevant messages in chronological context. Extract the main discussion points, decisions, commitments, questions, deadlines, and unresolved issues. Identify who requested each action and distinguish confirmed commitments from suggestions. If participants have provided conflicting information, explain the disagreement and reference the relevant messages. Do not assume that the latest message automatically resolves every earlier issue. Finish with a short executive summary and a list of next steps. If a response is needed, draft one using the actual conversation context. Do not send the reply or forward the thread without approval.

## Draft Context-Aware Email Replies

Prepare professional replies based on the original message, prior correspondence, and the intended outcome.

- Apps: Outlook
- Tools: `OUTLOOK_GET_MESSAGE`, `OUTLOOK_CREATE_DRAFT_REPLY`, `OUTLOOK_CREATE_DRAFT`, `OUTLOOK_REPLY_EMAIL`

> Review the Outlook email from the sender or subject I specify and the relevant conversation history. Draft a reply that addresses the sender's actual questions and requests. Use a professional, concise tone. Preserve any commitments, deadlines, prices, or technical details only when supported by the correspondence or information I provide. If critical information is missing, ask me for clarification or use a clearly marked placeholder. Provide the proposed subject, recipient, reply body, and any recommended attachments if relevant. Explain briefly if there are unresolved questions that should be addressed before responding. Save a draft only when I explicitly request it. Never send the email, add recipients, or attach sensitive files without my approval.

## Find Meeting Times Across Attendees

Identify suitable meeting slots based on calendar availability, duration, and participant requirements.

- Apps: Outlook
- Tools: `OUTLOOK_FIND_MEETING_TIMES`, `OUTLOOK_GET_CALENDAR_SCHEDULE`, `OUTLOOK_CALENDAR_CREATE_EVENT`

> Help me schedule a meeting about the topic and attendees I specify, for the duration and date range I give. Review my calendar and the available free/busy schedules for the required attendees. Respect the specified time zone, working hours, meeting duration, and any preferred days or times. Recommend the best available slots and list the start time, end time, time zone, and any known conflicts. Distinguish confirmed availability from information that could not be retrieved. Do not infer that an attendee is free merely because no event was returned. Prepare a meeting title, agenda, and invitation draft. Do not create the event or send invitations until I approve the final time, attendees, and content.

## Prepare for Upcoming Meetings

Gather relevant emails, meeting details, and open tasks before scheduled discussions.

- Apps: Outlook
- Tools: `OUTLOOK_GET_CALENDAR_VIEW`, `OUTLOOK_GET_EVENT`, `OUTLOOK_SEARCH_MESSAGES`

> Review my upcoming Outlook calendar events for the date range I specify and help me prepare for the most important meetings. For each relevant meeting, retrieve its available title, time, attendees, description, and attachments. Search related email conversations for background, previous commitments, unresolved questions, and decisions that may affect the meeting. Prepare a short briefing with the meeting objective, important context, proposed agenda, open questions, and actions I should complete beforehand. Do not invent meeting outcomes or assume that an agenda exists when none is available. Highlight schedule conflicts or missing preparation materials. Do not modify meetings, attach documents, or send briefing notes to participants without my approval.

## Manage Follow-Ups and Outstanding Replies

Identify unanswered requests and prepare timely follow-ups without sending duplicate messages.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_MESSAGES`, `OUTLOOK_LIST_SENT_ITEMS_MESSAGES`, `OUTLOOK_CREATE_DRAFT`

> Review my recent Outlook conversations and sent messages to identify follow-ups that may be overdue or still pending. Look for requests awaiting a response, proposals awaiting approval, client questions, promised updates, and messages that appear to require action. Check for subsequent replies before marking a conversation as unanswered. Create a table with the contact, subject, last relevant message date, outstanding request, explicit deadline if available, and suggested follow-up action. Separate confirmed overdue items from those that simply have no recorded response. Draft personalized follow-up emails where appropriate. Do not send reminders or messages automatically, and do not assume that silence means the recipient has ignored the previous email.

## Organize Inbox with Email Rules

Propose rules for organizing recurring emails and reducing inbox clutter.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_EMAIL_RULES`, `OUTLOOK_CREATE_EMAIL_RULE`, `OUTLOOK_UPDATE_EMAIL_RULE`, `OUTLOOK_DELETE_EMAIL_RULE`

> Analyze my Outlook inbox patterns and existing email rules to suggest ways to organize incoming messages. Identify recurring senders, newsletters, automated notifications, project correspondence, invoices, and other recognizable message categories. Recommend rules that could move messages into folders or apply suitable categories without hiding important communications. For each proposed rule, specify the matching conditions, action, intended benefit, and possible false-positive risks. Check existing rules to avoid duplicate or conflicting behavior. Present a proposed rule list and recommend which ones are safe to test first. Do not create, update, or delete rules, and do not permanently delete messages, without my explicit approval.

## Convert Emails into Actionable Tasks

Extract commitments and deadlines from emails and prepare a structured task list.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_MESSAGES`, `OUTLOOK_LIST_TODO_TASKS`, `OUTLOOK_CREATE_TASK`

> Review my recent Outlook emails and identify tasks, commitments, approvals, and follow-ups that require action from me. Extract the task description, source email, requester, confirmed owner, explicit deadline, dependencies, and current status where known. Separate tasks assigned to me from tasks assigned to other people. Prioritize tasks based on actual deadlines and business impact. If a deadline, owner, or status is missing, mark it as unknown rather than inventing one. Organize the results into a practical action list and recommend which tasks should be added to Microsoft To Do. Do not create, update, or delete tasks until I approve the proposed task details.

## Manage Contacts and Business Relationships

Find relevant contacts and maintain accurate contact records for clients, partners, and colleagues.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_USER_CONTACTS`, `OUTLOOK_UPDATE_CONTACT`, `OUTLOOK_CREATE_CONTACT`

> Review my Outlook contacts for the person, company, or business relationship I specify and retrieve the relevant available contact details. Identify existing records that match the search and distinguish exact matches from possible duplicates. Summarize relevant information such as name, email, company, and other available fields needed for the intended business task. If a contact needs updating, prepare a proposed change list and explain the source of each new value. Do not assume an email signature or an old message always contains current contact information. Do not create, update, merge, or delete contacts until I approve the exact changes. Avoid exposing personal information that is not necessary for the task.

## Automate Email and Calendar Follow-Ups

Use available Outlook triggers to prepare timely actions when new messages, sent emails, contacts, or calendar events appear.

- Apps: Outlook
- Tools: `OUTLOOK_LIST_MESSAGES`, `OUTLOOK_LIST_EVENTS`, `OUTLOOK_GET_MAILBOX_SETTINGS`, `OUTLOOK_CREATE_EMAIL_RULE`

> Help me design an Outlook workflow for the business process I specify, such as preparing a response when a client email arrives or creating a briefing when a meeting is scheduled. Review the available email and calendar capabilities and identify an appropriate trigger, required conditions, intended action, and any data dependencies. Consider received messages, sent messages, new contacts, and calendar event changes where relevant. Define safeguards to prevent duplicate processing, incorrect recipients, unintended replies, and repeated actions when an event is updated. Explain which steps can be automated safely and which should require human approval. Provide a clear workflow with trigger conditions, processing steps, exception handling, and a sample outcome. Do not activate rules, send emails, create meetings, or modify mailbox settings until I approve the workflow and its permissions.
