# Introduction

Project management is hard. Although I have taken university courses in project management and worked in the software development industry for a long time, structuring my own work as a sole developer has proved to be difficult. 

Most literature is aimed at groups of people, which makes sense because the more people working together, the bigger the need for a methodical approach to how the work should be performed. One would think that when working alone, and especially for oneself on one's own projects, there is no need for a formalised project model. I guess some people can handle working in such an ad-hoc fashion, but I'm not like that.

Of course, many of the documents and processes needed for managing a large project involving perhaps hundreds of people over several years are completely irrelevant for one-person team projects. This is where this project model comes in.

Modern software development favours agile and scrum over waterfall, due to the high demand of quick adaptations and iterative development modern software have. I've worked with agile project workflows and they are very good when working in teams, because of the collaborative nature of that methodology. However, I have found that when trying to use the same workflow I'm used to when working with other developers when working alone on my own projects (and without real deadlines), agile and scrum doesn't work as well.

In this project model I make use of both the older waterfall methodology and agile where it makes sense to use either.

The following steps should not be performed just once, but iterated on when there is need for it, for example going back to the project plan from the implementation phase if the WBS needs to expand or be altered.

# Write a project plan

The first thing we should do in a project is to write a project plan. It will help us to know what should be done, why, when, in which order and by whom. 

[Read more about the project plan.](project-plan.md)

# Implementation

After we have made the project plan it's time to start implementing the solution. We will probably have to go back and revise the project plan many times during the implementation phase.

[Read more about implementation.](implementation.md)

# Delivery

Depending on what we have decided in the delivery section in our project plan, we will make one or more deliveries. We will do this in parallel with implementation.

[Read more about delivery.](delivery.md)

# Input from users

When people have used our software for a while, they will discover bugs and security issues. They could also come up with ideas and requests for new features or changes in existing features. We should create easy paths for those users to come in contact with us regarding this. GitHub's issue tracker is a good place for letting users file bug reports as well as feature requests. If we aren't using GitHub (for example if the project is closed-source with no plans of making it open-source), we could set up an e-mail address for that purpose.

If the project is open-source, some users are even so kind as to propose source code in the form of what GitHub calls pull requests. This should be encouraged, along with bug reports, security reports and feature requests. We as developers can only bug test so much and work so fast, so extra help should be both encouraged and rewarded. Please don't be a jerk to users!

Given the sensitive nature of discovered security vulnerabilities, security reports should not be treated as bug reports which can normally be publicly available without issues. Security reports from users should always be treated confidentially. [GitHub has tools for this](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability "GitHub on reporting security vulnerabilities").
