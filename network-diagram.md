# Network diagram

This file shows a simplified [network diagram](https://project-management.info/project-schedule-network-diagram/) in table form. Each row is tied to one issue. The network diagram is for figuring out the best order to work on issues, taking into account priority and dependent issues. Since I don't use a time-fixed release schedule, milestones typically in network diagrams are to be considered new versions of this project.

| Issue | Name                                 | Priority[^1] | Dependent upon |
| ----: | ------------------------------------ | -----------: | -------------: |
|     1 | Create basic repo docs               |            3 |                |
|     2 | Create templates for basic repo docs |            4 |                |
|     4 | Initial planning                     |            4 |                |
|     5 | Working                              |            4 |                |
|     6 | Release                              |            4 |                |
|     7 | Further planning                     |            4 |                |
|     3 | Project stages                       |            4 |     4, 5, 6, 7 |

[^1]: Priorities are based on GitHub labels, in the following descending order: 1 bug, 2 improvement, 3 docs, 4 new feature