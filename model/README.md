# Introduction

Project management is hard. Although I have taken university courses in project management and worked in the software development industry for a long time, structuring my own work as a sole developer has proved to be difficult. 

Most literature is aimed at groups of people, which makes sense because the more people working together, the bigger the need for a methodical approach to how the work should be performed. One would think that when working alone, and especially for oneself on one's own projects, there is no need for a formalised project model. I guess some people can handle working in such an ad-hoc fashion, but I'm not like that.

Of course, many of the documents and processes needed for managing a large project involving perhaps hundreds of people over several years are completely irrelevant for one-person team projects. This is where this project model comes in.

Modern software development favours agile and scrum over waterfall, due to the high demand of quick adaptations and iterative development modern software have. I've worked with agile project workflows and they are very good when working in teams, because of the collaborative nature of that methodology. However, I have found that when trying to use the same workflow I'm used to when working with other developers when working alone on my own projects (and without real deadlines), agile and scrum doesn't work as well.

In this project model I make use of both the older waterfall methodology and agile where it makes sense to use either.

# Write a project plan

The first thing we should do in a project is to write a project plan. It will help us to know what should be done, why, when, in which order and by whom.

## Background

Explain why there is a need for the project and describe the original idea behind it. Tie that to the project goals and perhaps also how the project can contribute to overall business benefit.

## Purpose

For what effects will the project aim? Describe what the outcome will be when the project is finished, for example:

> This racing game will be a short and relaxing distraction while commuting.

> This budgeting software will help small businesses and households to keep track of their vacation money.

## Goal

Describe what should have been achieved when the project is finished. Goals should preferably be specific, measurable, attainable, realistic and timely (SMART). I don't care so much about time constraints, but if that is important, the goals should reflect that.

There are two types of goals: product goals and process goals. Product goals are tied to the product in which this project will result. Process goals are tied to the project process itself. Product goals are the most common, but sometimes a project is important in and of itself, outside the resulting product.

## Budget

Define the budget parameters and constraints in terms of money and time. Not so important with my own projects, but useful when it comes to contract work.

## Requirements

Depending 

## Scope

Now it's time to create a work breakdown structure (WBS). This is a hierarchical structure of all the work needed to be done for the project goals to be met. It can be difficult to capture everything in the beginning before anything has been implemented, but it's important to try capturing as much as possible. We can always revisit this WBS at a later stage, so if we miss something here it's not a huge deal. Try to be thorough, though. If there is a budget in place, it can guide us on the scope.

While writing the WBS, we shouldn't concern ourselves with order of execution or interdependencies between work units. Just put it all in there. Order of execution is dealt with later.

How granular a WBS should be can be a difficult decision. It's easy to go overboard with this, so I will try to limit myself to at most three levels:

| Level | Name    | Description and examples                                     |
| ----- | ------- | ------------------------------------------------------------ |
| 1     | Feature | High-level features of the project, e.g. a login system, a level in a video game, or configuration options. |
| 2     | Module  | Modules involved in the feature, e.g. a login system would involve at least UI, database and I/O; a level in a video game would involve a large number of modules, e.g. music, graphics, animation and UI. |
| 3     | Task    | The actual work needed to be done in each module to achieve the intended result of the feature, e.g. for a login system, the UI module would have tasks for creating the login form and menu items to reach it, while the database module woud have tasks for retrieving user data from the database. |

The WBS should be written in a hierarchical list format, for example:

> 1. Login system
>    1. UI
>       1. Login form.
>       2. Menu items to reach the login form.
>       3. …
>    2. Database
>       1. Match login credentials to user table row.
>       2. Retrieve user data on successful login.
>       3. …
>    3. I/O
>       1. …
>    4. …
> 2. …

## Limitations

It's a good idea to make any limitations to the scope explicit in the project plan. Doing that reduces the risk of so-called scope creep, a situation where one slowly and often without noticing expands the scope of a project beyond what was initially planned and budgeted for. These limitations can both be defined on the project level or feature level. An example of limitations on a feature can be as follows:

> We will not implement the ability to login via physical pass cards.

## 
