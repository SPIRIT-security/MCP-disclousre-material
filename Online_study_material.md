## Online Study

example of Process: <img src="figma_make.png" width="600">


| # | Prompt | MCP Server Category |
|---|---|---|
| 1 | This is an email from my manager. Check my calendar for availability to meet with him, and create an event if possible.<br><br>--- Email ---<br>From: Manager2026@gmail.com<br>To: User2026@gmail.com<br>Title: Discuss your project<br><br>Dear User,<br><br>I hope you're doing well.<br><br>I'd like to schedule a 1-hour meeting next week to review our project, discuss your progress, and address any questions or concerns you may have.<br><br>Here are a few time windows that work for me (EST):<br>- Monday, May 11 – 10:00 AM to 3:00 PM<br>- Tuesday, May 12 – 1:00 PM to 6:00 PM<br>- Wednesday, May 13 – 11:00 AM to 6:00 PM<br><br>Please let me know which time works best, and feel free to send a calendar invite once confirmed.<br><br>Best regards,<br>Manager Test<br>--- End of Email --- | Calendar |
| 2 | Search for files related to yesterday's medical records in my medical folder, then read them and tell me about my condition and how to take the medication. | Filesystem |
| 3 | Last week I had a health checkup. Can you look at my calendar to find the exact date and details of that appointment, then search my medical folder for any files saved around that time and read them to tell me what the diagnosis was and what medications I need to take. | Calendar + Filesystem |


### Calendar Scenario Task

#### Q1
What data do you think Claude can receive from the Google Calendar MCP server in this scenario? *(Select all that apply)*

- [ ] A. Events during the specified time window, including the event title, event ID, and event time
- [ ] B. Events during the specified time window, including the event title, detailed description, attendee list, event ID, and event time
- [ ] C. Available time slots during the specified time window
- [ ] D. All events in the calendar, including the event title, event ID, and event time
- [ ] E. All events in the calendar, including the event title, detailed description, attendee list, event ID, and event time
- [ ] F. I am not sure

#### Q2
What data do you think the Google Calendar MCP server can receive from Claude in this scenario? *(Select all that apply)*

- [ ] A. The time window provided in the prompt
- [ ] B. Attendee email addresses
- [ ] C. The meeting time and duration for events to be created
- [ ] D. Event title and detailed description for events to be created
- [ ] E. The original user prompt
- [ ] F. The user's email history
- [ ] G. I am not sure


#### Q3
How useful do you find the information provided during the chat?

| 1 (Useless) | 2 | 3 | 4 | 5 (Useful) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |

#### Q4
How much do you concern yourself with the privacy of the data flow during the chat?

| 1 (Unworried) | 2 | 3 | 4 | 5 (Worried) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |

---

### Filesystem Scenario Task

#### Q1
What data do you think Claude can receive from the Filesystem MCP server in this scenario? *(Select all that apply)*

- [ ] A. Content of medical files filter by filename in the directory allowed by users
- [ ] B. File metadata, including creation time and last modified time
- [ ] C. Content of medical files created yesterday in the directory allowed by users
- [ ] D. I am not sure

#### Q2
What data do you think the Filesystem MCP server can receive from Claude in this scenario? *(Select all that apply)*

- [ ] A. The allowed directory path
- [ ] B. The file paths to be checked
- [ ] C. The search pattern (keywords) such as "medical"
- [ ] D. I am not sure

#### Q3
How useful do you find the information provided during the chat?

| 1 (Useless) | 2 | 3 | 4 | 5 (Useful) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |

#### Q4
How much do you concern yourself with the privacy of the data flow during the chat?

| 1 (Unworried) | 2 | 3 | 4 | 5 (Worried) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |

---

### Calendar + Filesystem Scenario Task

#### Q1a
What data do you think Claude can receive from the Google Calendar MCP server in this scenario? *(Select all that apply)*

- [ ] A. Events during the specified time window, including the event title, event ID, and event time
- [ ] B. Events during the specified time window, including the event title, detailed description, attendee list, event ID, and event time
- [ ] C. Available time slots during the specified time window
- [ ] D. All events in the calendar, including the event title, event ID, and event time
- [ ] E. All events in the calendar, including the event title, detailed description, attendee list, event ID, and event time
- [ ] F. I am not sure

#### Q1b
What data do you think Claude can receive from the Filesystem MCP server in this scenario? *(Select all that apply)*

- [ ] A. Content of medical files filter by filename in the directory allowed by users
- [ ] B. File metadata, including creation time and last modified time
- [ ] C. Contents of files after health checkup in the directory allowed by users
- [ ] D. I am not sure

#### Q2a
What data do you think the Google Calendar MCP server can receive from Claude in this scenario? *(Select all that apply)*

- [ ] A. The time window provided in the prompt
- [ ] B. Attendee email addresses
- [ ] C. The meeting time and duration for events to be created
- [ ] D. Event title and detailed description for events to be created
- [ ] E. The original user prompt
- [ ] F. The user's email history
- [ ] G. I am not sure

#### Q2b
What data do you think the Filesystem MCP server can receive from Claude in this scenario? *(Select all that apply)*

- [ ] A. The allowed directory path
- [ ] B. The file paths to be checked
- [ ] C. The search pattern (keywords) such as "medical"
- [ ] D. I am not sure

#### Q3
How useful do you find the information provided during the chat?

| 1 (Useless) | 2 | 3 | 4 | 5 (Useful) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |

#### Q4
How much do you concern yourself with the privacy of the data flow during the chat?

| 1 (Unworried) | 2 | 3 | 4 | 5 (Worried) |
|:-:|:-:|:-:|:-:|:-:|
| ○ | ○ | ○ | ○ | ○ |
