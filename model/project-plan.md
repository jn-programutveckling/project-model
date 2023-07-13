# Background

Explain why there is a need for the project and describe the original idea behind it. Tie that to the project goals and perhaps also how the project can contribute to overall business benefit.

# Purpose

For what effects will the project aim? Describe what the outcome will be when the project is finished, for example:

> This racing game will be a short and relaxing distraction while commuting.

> This budgeting software will help small businesses and households to keep track of their vacation money.

# Goal

Describe what should have been achieved when the project is finished. Goals should preferably be specific, measurable, attainable, realistic and timely (SMART). I don't care so much about time constraints, but if that is important, the goals should reflect that.

There are two types of goals: product goals and process goals. Product goals are tied to the product in which this project will result. Process goals are tied to the project process itself. Product goals are the most common, but sometimes a project is important in and of itself, outside the resulting product.

# Budget

Define the budget parameters and constraints in terms of money and time. Not so important with my own projects, but useful when it comes to contract work.

# Requirements

Most projects have requirements. Depending on what the budget allows, we should make a list of both functional requirements (the resulting end product) and project requirements (how the work should be performed), and sort them by priority. This is mostly important for contract work or projects with budget constraints, because it helps us to define which scope we can realistically achieve. In projects without money or time constraints, it makes little sense to cut off requirements and not do them all.

For priorities, use MoSCoW (must have, should have, could have and won't have),

# Scope

Now it's time to create a work breakdown structure (WBS). This is a hierarchical structure of all the work needed to be done for the project goals and requirements to be met. It can be difficult to capture everything in the beginning before anything has been implemented, but it's important to try capturing as much as possible. We can always revisit this WBS at a later stage, so if we miss something here it's not a huge deal. Try to be thorough, though. If there is a budget in place, it can guide us on the scope.

While writing the WBS, we shouldn't concern ourselves with order of execution or interdependencies between work units. Just put it all in there. Order of execution is dealt with later.

How granular a WBS should be can be a difficult decision. It's easy to go overboard with this, so I will try to limit myself to at most three levels:

| Level | Name                | Description and examples                                     |
| ----- | ------------------- | ------------------------------------------------------------ |
| 1     | Feature             | High-level features of the project, e.g. a login system, a level in a video game, or configuration options. |
| 2     | Stage of refinement | A feature is divided in multiple stages of refinement for iterative development purposes. For example a login system could have a pure username/login prompt as its first stage, a "reset password" link as its second, and a "remember me" option as its third. |
| 3     | Task                | The actual work needed to be done in each module to achieve the intended result of the feature, e.g. for a login system, the UI module would have tasks for creating the login form and menu items to reach it, while the database module would have tasks for retrieving user data from the database. |

The WBS should be written in a hierarchical list format, for example:

> 1. Login system
>    1. Simple username/password prompt
>       1. Login form
>       2. Menu items to reach the login form
>       3. Match login credentials to user table row
>       4. …
>    2. Ability to reset one's password
>       1. E-mail a link to a reset password page
>       2. …
>    3. …
>       1. …
>    4. …
> 2. …

Don't forget that documentation and design are also important "features", thus they should be added to the WBS. This is more important in larger or complex projects, for example in game development, a game design document is very important and should absolutely be part of the WBS.

# Limitations

It's a good idea to make any limitations to the scope explicit in the project plan. Doing that reduces the risk of so-called scope creep, a situation where one slowly and often without noticing expands the scope of a project beyond what was initially planned and budgeted for. These limitations can both be defined on the project level or feature level. An example of limitations on a feature can be as follows:

> We will not implement the ability to login via physical pass cards.

# Milestones

Milestones are natural points in the project life cycle where a delivery can be made or an important business decision has to be made, for example to evaluate the current state and decide on future development. In contrast to the WBS, milestones are ordered in time. Milestone 1 should normally be done before milestone 2.

A piece of software can often be delivered in multiple steps. One way to do is to deliver one fully functional module or part after another, but a more common way is to deliver a bare-bones version of the whole project and over several iterations deliver more refined versions until it's the project is complete. Each of those steps are perfect candidates for a milestone. Example:

> **Note taking app**
>
> Milestone 1: Ability to write unformatted text and save it to the file system.
>
> Milestone 2: Common formatting options, such as bold, italic, underline and bullet lists.
>
> Milestone 3: Ability to print the document.
>
> Milestone 4: Sharing options to external applications and services.

When listing the milestones, think about how they map to the WBS, because we're about to order each task in the upcoming section.

# Activities

Now it's time to list activities and milestones in order. An activity is a feature divided into a stage of refinement, that is level 1 and 2 of the WBS combined. Construct a table with the following columns:

- **ID.** A simple sequential number.
- **Name.** A description of level 1 and 2 of the WBS.
- **Dependencies.** Any activities that have to be completed before starting this one.
- If we have a budget, **Duration**. How many time units (hours, days, weeks) this activity is expected to take.
- If we have a budget, **Cost**. How much this activity will cost.

Milestones are activities, too, with their own dependencies.

# Delivery or integration

Describe how the end product should be delivered or integrated into a target environment. Where the product should be made available, at which price etc.

# SWOT analysis

The purpose of a SWOT analysis is to capture the current situation and environment of both within the project organisation and in the society outside of it, and identify strengths, weaknesses, opportunities and threats that may have an impact on the project.

Strengths are factors within our control that increases the likelihood of project success. Example:

> Domain knowledge of the podcasting field.

Weaknesses are factors within our control that decreases the likelihood of project success. Example:

> Lack of experience building machine learning models.

Opportunities are factors outside of our control that increases the likelihood of project success. Example:

> Public interest and adoption rate is high for accessible mobile apps.

Threats are factors outside of our control that decreases the likelihood of project success. Example:

> The market for computer zombie survival games are very saturated.

## Strategies

Now that we have identified strengths, weaknesses, opportunities and threats it's time to combine them to create strategies.

Growth strategies aims to make use of strengths to capitalise on opportunities. Example:

> Because public interest is high for accessible mobile apps, I should make sure this mobile app is very accessible.

Internal development strategies aims to convert weaknesses into strengths, so that they can be matched to opportunities. Example:

> I could get a nice contract with a big client if I hired one more programmer.

External development strategies aims to make use of our strengths to convert threats into opportunities. Example:

> If I advertise my skills and previous experience, I will get more contract work and make more money.

Survival strategies aims to avoid threats, especially those with a matching weakness. To do this, we must execute both internal and external development strategies. Example:

> Because most gamers react negatively to games with cryptocurrency integration, I should avoid developing such games.

# Risk analysis

The first step in risk analysis is to identify possible risks to the project's success. Risks can be internal as well an external to the project organisation. List each risk together with its probability, consequences and risk value. In order to simplify the quantification of risk probability, consequences and risk value, the following categories shall be used:

- Probability
  - High
  - Medium
  - Low
- Impact
  - Severe
  - Moderate
  - Minor


This gives us a matrix of nine possible risk values. If we plot severe risks with high probability in the top left, and minor risks with low probability in the bottom right, we want to try to move risks further down and right. That is, either reduce the likelihood that or limit the consequences of the risk occurs (or preferably both).

When we have identified all risks and their risk value (probability x consequences) we have to assign a mitigation strategy for each risk. Mitigation strategies can be categorised into the following:

- Reducing the likelihood of the risk occurring. In the extreme case, we can avoid the activity that introduces the risk, thus effectively reducing the likelihood to zero. This may not always be possible or desirable, but in the face of catastrophic consequences, perhaps even a negligent probability is unacceptable.
- Limiting the consequences if the risk were to occur. Some risks are an inextricable part of what we're trying to accomplish and thus it can't be reduced. In those cases, perhaps we can try to limit the damage such a risk would make. 

See the following matrix where H is high risk value, M is moderate risk value and L is low risk value. Risks with a high risk value are the most important ones to try to mitigate, so they move down to moderate risk value or lower.

|                     | High probability | Medium prob. | Low prob. |
| ------------------- | ---------------- | ------------ | --------- |
| **Severe impact**   | H                | H            | M         |
| **Moderate impact** | H                | M            | L         |
| **Minor impact**    | M                | L            | L         |

The following example shows a risk with a medium risk value. After mitigation, we can lower the risk value to low by lowering the probability. With this particular risk, the impact couldn't be lowered.

> The hired artist will be more expensive than expected.
>
> Likelihood before mitigation: Medium
>
> Impact before mitigation: Moderate
>
> Risk value before mitigation: High
>
> Mitigation strategy: Negotiate a maximum price for the artists services.
>
> Likelihood after mitigation: Low
>
> Impact after mitigation: Moderate
>
> Risk value after mitigation: Medium
