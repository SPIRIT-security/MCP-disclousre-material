## Study Procedure
#### Screening Survey
[Consent form] <br>
1. What is your age?<br>
  (A) <18 (B) 18-25 (C) 26-35 (D) 36-45 (E) 46-60 (F) 60+ <br>
2. What LLMs have you used? LLM stands for Large Language Model -- AI models that can understand and generate human language, such as ChatGPT, Claude, Gemini, and Llama.<br>
  (A) Claude (B) ChatGPT (C) Gemini (D) Others [open text box] (E) I have never used any LLMs <br>
3. What is your experience with LLMs?<br>
  (A) 1-3 months (B) 4-6 months (C) 7-12 months (D) 1-3 years (E) More than 3 years <br>
4. Have you ever connected your LLM(s) to an external service? An 'external service' here means any third-party app, platform, or data source that your LLM can access or interact with — for example, GitHub, Google Calendar, Google Drive, Slack, or Notion.<br>
  (A) No (B) Yes <br>
5. What external services have you connected to an AI assistant? (Examples: Claude connected to Gmail; ChatGPT connected to Slack; Gemini connected to Google Drive) [open text box] <br>
6. For how long have you connected your LLM(s) to an external service?<br>
  (A) Less than 1 month (B) 1-3 months (C) 4-6 months (D) 7-12 months (D) More than 1 year <br>
7. Have you connected your LLM(s) to an external tool using an MCP server? <br>
   MCP (Model Context Protocol) is a standard that defines how AI applications connect to external tools and data. An MCP server is a software component that implements this standard and provides access to specific tools or resources, such as GitHub, a file system, a database, or Slack. <br>
   For example, some people use Claude/ChatGPT with MCP servers to access Gmail and manage emails, interact with Google Drive or Google Calendar, query databases like PostgreSQL, control GitHub repositories, connect to Slack or Discord, browse and automate web apps, work with Notion, access local files, or interact with cloud services like AWS.
  (A) Yes, I have connected an MCP server. (B) No, I have never connected any MCP servers. (C) I am not sure. <br>
8. Which methods did you use to connect an MCP server? <br>
  (A) Through a graphical interface / built-in settings (e.g., Claude's "Connectors" menu). <br>
  (B) By manually editing a configuration file (e.g., claude_desktop_config.json, mcp.json). <br>
  (C) Through a command-line tool (e.g., Claude Code CLI, npx command). <br>
  (D) Through a third-party browser extension (e.g., MCP SuperAssistant or similar tools that bring MCP to web-based chat interfaces). <br>
  (E) I am not sure
[If "<18" to Q1 or "I have never used any LLMs/MCP servers" to Q2 or Q7, quit the survey and thank the participant] <br>
9. What is your gender identity?<br>
	(A) Male (B) Female (C) Non-binary (D) Prefer not to say <br>
10. Choose one or more races that you consider yourself to be. <br>
  (A) White or Caucasian (B) Black or African American (C) American Indian/Native American or Alaska Native (D) Asian (E) Native Hawaiian or Other Pacific Islander (F) Other (G) Prefer not to say <br>
11. What is the highest level of education you have completed?<br>
  (A) Some high school or less (B) High school diploma or GED <br>
  (C) Some college, but no degree (D) Associates or technical degree<br>
  (E) Bachelor’s degree <br>
  (F) Graduate or professional degree (MA, MS, MBA, PhD, JD, MD, DDS, etc.)<br>
  (G) Prefer not to say <br>
12. Are you able to participate in the study via Zoom?<br>
	(A) yes (B) no <br>
13. Thanks very much for your interest in our study. We will contact you to schedule the study. Please enter an email address by which we can contact you. [open text box] <br>
14. If you have any other questions or information, please enter them here. [open text box] <br>

#### Online Study
| # | Prompt | MCP Server Category |
|---|---|---|
| 1 | This is an email from my manager. Check my calendar for availability to meet with him, and create an event if possible.<br><br>--- Email ---<br>From: Manager2026@gmail.com<br>To: User2026@gmail.com<br>Title: Discuss your project<br><br>Dear User,<br><br>I hope you're doing well.<br><br>I'd like to schedule a 1-hour meeting next week to review our project, discuss your progress, and address any questions or concerns you may have.<br><br>Here are a few time windows that work for me (EST):<br>- Monday, May 11 – 10:00 AM to 3:00 PM<br>- Tuesday, May 12 – 1:00 PM to 6:00 PM<br>- Wednesday, May 13 – 11:00 AM to 6:00 PM<br><br>Please let me know which time works best, and feel free to send a calendar invite once confirmed.<br><br>Best regards,<br>Manager Test<br>--- End of Email --- | Calendar |
| 2 | Search for files related to yesterday's medical records in my medical folder, then read them and tell me about my condition and how to take the medication. | File System |
| 3 | Last week I had a health checkup. Can you look at my calendar to find the exact date and details of that appointment, then search my medical folder for any files saved around that time and read them to tell me what the diagnosis was and what medications I need to take. | Calendar + File System |
