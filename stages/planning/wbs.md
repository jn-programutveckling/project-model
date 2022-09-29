# Work breakdown structure

The purpose of a work breakdown structure is to capture and organise all necessary work within a project. Order and priority isn't important at this stage.

A work breakdown structure is hierarchical, meaning that the tasks are grouped together with different granularity. A rule-of-thumb when deciding how granular one should make it is that each task without sub-tasks can be completed within one unit of work (that might be one workday, one sprint, one week or whatever one chooses). Another rule-of-thumb is that if the task involves multiple distinct actions, it should be divided into sub-tasks. 

Be aware though not to go overboard with this. Dividing the task *Email my spouse regarding the trip* doesn't have to be divided into *Start Gmail*, *Write the email* and *Send the email*. That would be very cumbersome. If several tasks need to be executed sequentially, they might be better suited as a singular task.

When a task has sub-tasks, that task should be seen as a heading for a group, not a task itself. Thus, that task should be considered complete when all of its sub-tasks are complete. In the example below, the task *1 Build a house* isn't a task do be worked on; it should be seen as the house is built when all of its sub-tasks have been completed.

## Priority

Each task without sub-tasks shall be given a priority, according to what's described in the [labels file](labels.md). Don't manually give parent tasks a priority; priorities of sub-tasks "bubble up" to their parent tasks.

## Example

| Index   | Task                                         | Priority | Dependencies |
| ------- | -------------------------------------------- | -------- | ------------ |
| 1       | *Build a house*                              | *2*      |              |
| 1.1     | *Design the house*                           | *2*      |              |
| 1.1.1   | Decide on which needs the house have to meet | 2        |              |
| 1.1.2   | *Hire an architect*                          | *2*      | 1.1.1        |
| 1.1.2.1 | Take in offers from three architects         | 4        |              |
| 1.1.2.2 | Decide on the most suitable one              | 2        | 1.1.2.1      |
| 1.1.2.3 | Formalise the agreement                      | 4        | 1.1.2.2      |
| 1.1.3   | Accept the architect's building schematics   | 4        | 1.1.2        |
| 1.2     | *Acquire materials and permits*              | *4*      | 1.1          |
| 1.2.1   | Seek building permits                        | 4        |              |
| 1.2.2   | Calculate how much material to buy           | 4        | 1.2.1        |
| 1.2.3   | Buy cement                                   | 4        | 1.2.2        |
| 1.2.4   | Buy wood                                     | 4        | 1.2.2        |
| 1.2.5   | Buy nails                                    | 4        | 1.2.2        |
| 1.2.6   | Buy windows and doors                        | 4        | 1.2.2        |
| 1.3     | *Build the house*                            | *4*      | 1.2          |
| 1.3.1   | Build the foundation                         | 4        |              |
| 1.3.2   | Build the ground floor                       | 4        | 1.3.1        |
| 1.3.3   | Build the first floor                        | 4        | 1.3.2        |
| 1.3.4   | Build the roof                               | 4        | 1.3.3        |
| 1.3.5   | Pain the exterior walls                      | 4        | 1.3.2, 1.3.3 |
| 1.4     | *Interior design*                            | *4*      |              |
| 1.4.1   | *Build the kitchen*                          | *4*      | 1.3.4        |
| 1.4.1.1 | Buy an oven                                  | 4        |              |
| 1.4.2   | Build the bathroom                           | 4        | 1.3.4        |
| 1.4.3   | Build the bedroom                            | 4        | 1.3.4        |

Obviously, this isn't a complete breakdown of all tasks necessary to build a house, but the preceding table serves as a general outline how one may create a work breakdown structure. 

Rarely will a work breakdown structure be as tidy as this example. Here, every task is somewhat in order, but after the initial planning stage, one will eventually add tasks with various dependencies and priorities, "messing up" the order. When using Task Coach, this won't be a problem. Keeping a manual table like in the example would be more difficult. In this case, care must be taken to honour priority without breaking dependencies.