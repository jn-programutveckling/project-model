# Work breakdown structure

The purpose of a work breakdown structure is to capture and organise all necessary work within a project. Order and priority isn't important at this stage.

A work breakdown structure is hierarchical, meaning that the tasks are grouped together with different granularity. A rule-of-thumb when deciding how granular one should make it is that each task without sub-tasks can be completed within one unit of work (that might be one workday, one sprint, one week or whatever one chooses). Another rule-of-thumb is that if the task involves multiple distinct actions, it should be divided into sub-tasks. 

Be aware though not to go overboard with this. Dividing the task *Email my spouse regarding the trip* doesn't have to be divided into *Start Gmail*, *Write the email* and *Send the email*. That would be very cumbersome. If several tasks need to be executed sequentially, they might be better suited as a singular task.

When a task has sub-tasks, that task should be seen as a heading for a group, not a task itself. Thus, that task should be considered complete when all of its sub-tasks are complete. In the example below, the task *1 Build a house* isn't a task do be done; it should be seen as the house is built when all of its sub-tasks have been completed.

## Priority

bug, docs, improvement, new feature

## Example

| Index   | Task                                         | Dependencies |
| ------- | -------------------------------------------- | ------------ |
| 1       | Build a house                                |              |
| 1.1     | Design the house                             |              |
| 1.1.1   | Decide on which needs the house have to meet |              |
| 1.1.2   | Hire an architect                            | 1.1.1        |
| 1.1.2.1 | Take in offers from three architects         |              |
| 1.1.2.2 | Decide on the most suitable one              | 1.1.2.1      |
| 1.1.2.3 | Formalise the agreement                      | 1.1.2.2      |
| 1.1.3   | Accept the architect's building schematics   | 1.1.2        |
| 1.2     | Acquire materials and permits                | 1.1          |
| 1.2.1   | Seek building permits                        |              |
| 1.2.2   | Calculate how much material to buy           | 1.2.1        |
| 1.2.3   | Buy cement                                   | 1.2.2        |
| 1.2.4   | Buy wood                                     | 1.2.2        |
| 1.2.5   | Buy nails                                    | 1.2.2        |
| 1.2.6   | Buy windows and doors                        | 1.2.2        |
| 1.3     | Build the house                              | 1.2          |
| 1.3.1   | Build the foundation                         |              |
| 1.3.2   | Build the ground floor                       | 1.3.1        |
| 1.3.3   | Build the first floor                        | 1.3.2        |
| 1.3.4   | Build the roof                               | 1.3.3        |
| 1.3.5   | Pain the exterior walls                      | 1.3.2, 1.3.3 |
| 1.4     | Interior design                              |              |
| 1.4.1   | Build the kitchen                            | 1.3.4        |
| 1.4.1.1 | Buy an oven                                  |              |
| 1.4.2   | Build the bathroom                           | 1.3.4        |
| 1.4.3   | Build the bedroom                            | 1.3.4        |

Obviously, this isn't a complete breakdown of all tasks necessary to build a house, but the preceding table serves as a general outline how one may create a work breakdown structure. 