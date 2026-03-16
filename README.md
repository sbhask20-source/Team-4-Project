![My Image Description](Images/Logo.jpeg)

# Team-4-Project
1. Problem Statement
The user is any adult trying to manage work, personal, and social commitments more efficiently. Today, scheduling information is spread across emails, text messages, chat apps, and paper reminders. Because these details are scattered, users must manually enter events into their calendars, which is time-consuming and increases the chance of missed appointments or scheduling conflicts.
2. Why Now?
This problem will matter even more in the next 3–5 years as people rely on more communication platforms for scheduling. At the same time, recent advances in AI make this possible now. Vision and OCR tools can read screenshots and photos, while language models can interpret unstructured text and convert it into organized calendar details. As AI becomes more common in productivity tools, users will expect automation for repetitive tasks like calendar management.
3. Proposed AI-Powered Solution
Our product is an AI scheduling assistant that lets users upload a screenshot or photo containing scheduling information. The system extracts the event title, date, time, and location, then returns a structured calendar entry. For example, a user could upload a text conversation planning dinner or a photo of a dentist reminder card. AI adds value because scheduling details often appear in informal or inconsistent formats that rule-based systems cannot handle well.
4. Initial Technical Concept
The system would use screenshots, emails, text conversations, and scanned reminders as input data. Key fields include event title, date, time, location, and relevant notes. A vision or OCR model would read the content, a classifier would detect whether it contains calendar-related information, and a GPT-style model would convert it into a structured event. Access to the user’s calendar could help identify scheduling conflicts. Our nanoGPT work could support structured event generation and evaluation.
5. Scope for MVP
In about six weeks, the MVP could focus on one feature: a user uploads a screenshot of a text conversation planning an event, and the system returns the event title, date, time, and location. This keeps the project realistic while demonstrating its core value.

6. Risks and Open Questions
The main risks are accuracy, input ambiguity, and user interface design. Incorrectly extracted dates or times could create problems for users, and informal messages may be difficult to interpret. The team must also decide how users will review and confirm events before adding them to a calendar.
7. Planned Data Sources
Potential data sources include public OCR datasets, synthetic examples created by the team, sample screenshots of scheduling conversations, and calendar APIs. At minimum, the project needs reliable word recognition and event extraction data.
