# Background

Explain why there is a need for the project and describe the original idea behind it. Tie that to the project purpose and perhaps also how the project can contribute to overall business benefit.

# Purpose

For what effects will the project aim? Describe what the outcome will be when the project is finished, for example:

> This racing game will be a short and relaxing distraction while commuting.

> This budgeting software will help small businesses and households to keep track of their vacation money.

# Budget

Define the budget parameters and constraints in terms of money and time. Not so important with my own projects, but useful when it comes to contract work.

# Requirements

Most projects have requirements. Depending on what the budget allows, we should make a list of both functional requirements (the resulting end product) and project requirements (how the work should be performed), and sort them by priority. This is mostly important for contract work or projects with budget constraints, because it helps us to define which scope we can realistically achieve. In projects without money or time constraints, it makes little sense to cut off requirements and not do them all.

For priorities, use MoSCoW (must have, should have, could have and won't have). Give each requirement an ID, so they can be referenced in other parts of the planning process.

# Activities

When planning what to do and when to do it, normally one would first create a work breakdown structure, WBS for short, to list everything that needs to be done to meet the project goals and requirements, regardless of the order in which they need to be done. Then with the WBS in hand, one would construct a network map, in which the time line of when to do each thing and in which order is made visible.

However, because I work alone, I feel that this process is too cumbersome to do in multiple steps. Therefore these steps are merged into one in my project model. I still go through the aforementioned steps, but only implicitly. I don't maintain separate documents for the WBS and network map; instead I keep everything in a [TaskCoach](https://www.taskcoach.org/) tree.

Don't forget that documentation and design are also important activities to include. This is more important in larger or complex projects, for example in game development, a game design document is very important and should absolutely be part of the activities.

The list of activities can, and should, be revisited many times throughout the lifetime of the project, whether it is to add new items, remove finished items or something else.

If there is a budget in place, the activities should also take into account duration (how many time units I expect to work on this activity) and cost (how much this activity is expected to cost).

# Limitations

It's a good idea to make any limitations to the scope explicit in the project plan. Doing that reduces the risk of so-called scope creep, a situation where one slowly and often without noticing expands the scope of a project beyond what was initially planned and budgeted for. These limitations can both be defined on the project level or feature level. An example of limitations on a feature can be as follows:

> We will not implement the ability to login via physical pass cards.

# Delivery or integration

Describe how the end product should be delivered or integrated into a target environment. Where the product should be made available, at which price etc. 

Also describe how any intermediary deliveries will be handled in this regard. Software is rarely really finished, so it's fair to say that all but abandonware is in an intermediary stage.

# SWOT analysis

The purpose of a SWOT analysis is to capture the current situation and environment of both within the project organisation and in the society outside of it, and identify strengths, weaknesses, opportunities and threats that may have an impact on the project.

Strengths are factors within our control that increases the likelihood of project success. Example:

> Domain knowledge of the podcasting field.

Weaknesses are factors within our control that decreases the likelihood of project success. Example:

> Lack of experience building machine learning models.

Opportunities are factors outside of our control that increases the likelihood of project success. Example:

> Public interest and adoption rate is high for accessible mobile apps.

Threats are factors outside of our control that decreases the likelihood of project success. Example:

> The market for computer zombie survival games is very saturated.

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
