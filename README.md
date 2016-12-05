# Planner-Funnel
The Planner Funnel is a tool which manages tasks, notes and schedules. Schedules are either plans or logs. These node categories appear one level below the top node. A node can be any of these basic types or a combination. For example, "check bank balance" may be both a task and plan item.  In this case the node "check bank balance" would a child of both the highest level task node and a plan item. As a minimum, a node cointains a creation timestamp and description.
## Tasks
During the life-time of a task, it is expected to be linked to a plan, log or both.
## Activities
Contains additional fields - start timestamp and duration. It has 2 child nodes - schedules and logs. The duraction defaults to 30 mins.
## Schedules
The scedule's start timestamp will always be in the future and default the next hour or half-hour on the clock. The duraction is the expected time to complete the task.


