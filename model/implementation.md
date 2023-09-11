# Introduction

With our [project plan](project-plan.md) in hand it's time for us to create an implementation that satisfies the project goals and requirements. This in a highly iterative process; not only within this phase but also involving revising the project plan.

The basis upon which we plan the implementation is the activity list in the project plan. In this document I describe the stages activities and milestones go through.

The following list outlines roughly the steps I take when doing implementation. More details of the individual steps can be found within this document.

1. While there are milestones left in the project plan…
   1. Pick the first milestone that has not been completed.
   2. While there are activities left in that milestone…
      1. Create a new feature branch from `main`. Small changes don't need a separate branch.
      2. Write unit tests that fits the requirements.
      3. While at least one test fail…
         1. Write code. Don't forget to also write comments.
      4. Make sure the code is properly documented and that the implementation truly satisfies the requirements.
      5. Update the changelog with a description of what I have done. If necessary, update the readme as well.
      6. Merge the branch back into `main`.
   3. Make sure the code is properly documented and that the implementation truly satisfies the requirements. Also, make sure that the changelog, the readme and other repository documents is up-to-date.
   4. Create delivery artefacts according to the delivery section in the project plan.
   5. Merge the `main` branch to `production` and create a new tag for the new version.
   6. Write a blog post about the new version. If the changes are big and the project is publicly available (either artefacts, code or both), I should probably also make a YouTube video showing the changes.

# Write tests

Before we start blasting away coding we should think about how we can test the implementation of the activity. Unit tests are the most straight-forward, but other types of tests are also useful. At the start, all unit tests will obviously fail, but that is expected. Once we start writing code we should regularly run these tests to see whether they pass or fail. As long as they are failing we know we're not done with the implementation.

The most important thing to keep in mind regarding tests is that their purpose is to determine whether the implementation conforms to the specification (the requirements). We have a picture in our minds on how the end project should be (the specification) and we have to test whether what we have built (the implementation) live up to that picture in our minds.

# Branching strategy

I use Git as version control and I make use of [GitLab Flow](https://docs.gitlab.com/ee/topics/gitlab_flow.html) as my branching strategy.

# Write documentation

How to document our code (and even whether we should do it all) is a hotly debated issue within the developer community. I am squarely in the camp that promotes ample documentation. Proper documentation will help us as developers (including the authors of the code, since we humans tend to forget things from time to time) as well as the users and other interested parties.

These are the different kinds of documentation I find valuable:

- Project and design documentation — the kind that I have written here, as well as documentation of how an entire product or part of it should function and present itself. This type of documentation might not be for public consumption, so it's best not to check this into version control together with the rest of the project if we're someday want to go open-source.
- Repository documents — readme, licenses, changelog, contributing information etc. Things that should be available in a repository, especially if it's open-source.
- User manuals and wikis — instructions for end-users as well as other developers who may use my API's or the like, on how to use the products I have created.
- API documentation — documenting classes, methods, functions etc. in such a way I can build documentation artefacts such as Javadoc.
- Inline comments in code — this can be of great benefit to quickly see what's going on. The least important in my opinion, but it can definitely be useful.
