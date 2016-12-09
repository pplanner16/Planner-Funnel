# Planner-Funnel
The Planner Funnel is a tool which manages tasks, notes and schedules. Every item added to the funnel is called a 'node' and belongs to one of one of the above categories. These main node categories appear one level below the top node. For example, "check bank balance" may be both a task and schedule item.  In this case the node "check bank balance" would appear under both the task and a schedule item sub-trees. As a minimum, a node cointains a creation timestamp and description.
## Schedules
Schedules are either plans or logs. The plan's start timestamp will always be in the future and default the next hour or half-hour on the clock. The duraction is the expected time to complete the task. A log's start timestamp is always in the past.

## Tasks
During the life-time of a task, it is expected to be linked to a plan, log or both.
## Activities
Contains additional fields - start timestamp and duration. It has 2 child nodes - schedules and logs. The duraction defaults to 30 mins.

