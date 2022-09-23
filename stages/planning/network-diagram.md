# How to work with the network diagram

A network diagram is a project planning tool used to visualise what needs to be done and in which order, from the project's start to its finish. In this project model, we're using a simplified network diagram. Also, we skip over the step of creating a [work breakdown structure](https://en.wikipedia.org/wiki/Work_breakdown_structure); we jump straight onto the network diagram.

## Simplifications

Normally, a network diagram features milestones where the project team can take stock of the progress so far, and to make changes as necessary. It can also act as points throughout the project where deliverables are produced. Usually, time estimates are added to each node or task. This is done to better be able to plan resources, the total time for the so called critical path and to see which tasks that can be moved in time.

In this project model, neither milestones nor time estimates are used.

## No work breakdown structure

Normally, one would create a work breakdown structure before creating a network diagram. The purpose of a work breakdown structure is among other things to capture everything that needs to be done in a project, without caring about order, timing etc. 

What I mean with skipping over the work breakdown structure is not that this total capturing of tasks isn't necessary; I mean that we don't need a *separate document* for it. We can do both that and the network diagram in the network diagram. Work breakdown structures are best in large projects, and especially in teams larger than one person.

## Starting out

Since we aren't using a work breakdown structure, we have to use the network diagram for writing down every task necessary for completing the project. This is a very hard thing to do in software development, so we'll aim for writing down tasks for the next few weeks of development (or as far ahead as possible). The following list describes how to start out with a network diagram.

1.   For each new task…
     1.   Write it down on a new line in the network diagram (really a table). Don't worry about getting the order right. We'll deal with that later.
     2.   Choose a priority based on the [labels](labels.md). Just a number will do; no need for writing the whole word.
     3.   Add it as a new GitHub issue. Write down the issue number it's given, in the network diagram.
2.   When every conceivable task have been written down, take a look at them and find any dependencies and write them down on each line that have them.
3.   Reorder the list of tasks first by priority, then by issue number in such a way to not break any dependencies. For example, if a priority 1 task depends on a priority 2 task, the priority 1 task should come *after* the priority 2 task, despite it having higher priority.

## Continue working

Whenever a new idea or thing that needs to be done comes up, add it to the network diagram so it isn't forgotten. If you're in a hurry, it's okay to just write it down at the end. Otherwise, it's a good thing to perform the same steps as when starting out.

After a task has been completed, remove that row from the network diagram. Also, make sure to remove any mentions of the task in the dependencies of other tasks.