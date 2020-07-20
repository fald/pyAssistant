# pyAssistant

A personal assistant program written in Python


Inspired by eagle (https://github.com/im-n1/eagle)

Current goals:
- A simple ToDo application on command line that supports due dates, recurrence and grouping.
	- Daily, today, tomorrow, x Monday of the month etc.
	- Support prioritising.
	- Support duration (per task and per session).
	- Support time chunks (Free time, work time) and allowable activities (groups, sorta?)
- Database schema (and choice thereof)
	
Future goals:
- Local users, then remote users
- Behavior on skipping/missing an item - recurr, wait until completion, strict time/day, just skip?
- Support basic command-line usage and data persistence using an XML file
- Ping user for input, or when a task is due (configurable when entering item)
- Sub-tasks
- Reminders
- Varying command-line functionality, either via python script or bash for *nix
- GUI version
- Android version
- Task auto-ordering; topological sort?
- Track % completion, +Suggestions based on this
- Remote data storing; requires security, naturally. Also users and such.
- Shopping list functionality, including sharing list with other people (ie family)
- Goals lists - long term, short term. Grouped.
- Make use of Decision tactics.
- Mood info gathering and updating for a running total of mood and why/what causes it.
- Preset goals/todo sections, such as fitness + meal prep, including all steps and durations
