# Network diagram

This file shows a simplified [network diagram](https://project-management.info/project-schedule-network-diagram/) in table form. Each row is tied to one issue. The network diagram is for figuring out the best order to work on issues, taking into account priority and dependent issues. Since I don't use a time-fixed release schedule, milestones typically in network diagrams are to be considered new versions of this project.

|        Issue | Name             | Priority[^1] |                                               Dependent upon |
| -----------: | ---------------- | -----------: | -----------------------------------------------------------: |
| issue number | issue name       |     priority | list of other issues that must be completed before starting on this one |
|              | *version number* |              |                                                              |
| issue number | issue name       |     priority |                                                              |
| issue number | issue name       |     priority |                                                              |
|              | *version number* |              |                                                              |

# Instructions

1.   Change everything in the table according to your own issues and planned releases.
1.   Remove the *Instructions* section. :smile:

[^1]: Priorities are based on GitHub labels, in the following descending order: 1 bug, 2 improvement, 3 docs, 4 new feature