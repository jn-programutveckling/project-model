# Open source or closed source?

The first thing we probably should be thinking about is whether the project should be open or closed source. There are pros and cons with either choice.

Open-source software builds trust because users can inspect the code for themselves. It's also easier for users to file good bug reports and also contribute with fixes themselves. The major downside of open-source software is that it's much harder to make money on it, because users could just download the source and build the software themselves instead of buying it from us. Developers of commercial open-source software usually solve this problem by having two versions, one free and open-source and one paid and closed-source, where the paid version offers more features and also support.

It's always easier to turn a closed-source project into an open-source one than the other way around. My recommendation is to always start out with closed source if there is no compelling reason to do otherwise, for example use of third-party libraries which licenses require us to have our code open-source (for example the [GPL](https://choosealicense.com/licenses/gpl-3.0/)).

# Licensing

Dealing with licenses can be very hard. This is especially true if we're using third-party open-source code. There is a myriad open-source licenses and combining them can often be a hassle, especially for people who aren't lawyers.

Similar to what I wrote in the previous section about how it's easier to turn a closed-source project into an open-source one than the other way around, it's always easier to start with a more restrictive license and make it more permissive as time goes on, than the other way around. For example it's preferable to go from not permitting commercial usage to permitting it, than the other way around. Giving people more rights is always easier than taking rights away. It can be done, but it's not very popular and depending on license terms, it might not even be legal.

## Choosing a license for our project

The first step in choosing the proper license for our project is to look at the license terms of all third-party libraries we are using, and find the most permissive terms that would satisfy all of them. Example:

> Library A permits commercial use but requires that the source code is made public.
>
> Library B does not permit commercial use but also permits its use in closed-source software.
>
> To satisfy both libraries' license terms, we must not make our project commercial and we must make the source code public.

In some cases, two licenses are mutually incompatible. Then our only recourse is to try to find some other libraries that aren't incompatible. We could also choose to write our own code, but that may be too expensive or otherwise undesirable.

When we have our baseline of what required of us by third-party licenses, it's time to decide upon how we want our project to be used. Both [Choosealicense](https://choosealicense.com/appendix/) and [Creative Commons](https://creativecommons.org/share-your-work/) are good resources on how to think about which license one might want or need. My recommendation is to treat any license we choose as final and unchangeable. Which permissions are we comfortable giving users five years from now? Would we feel snubbed to see someone making money off a slight modification of our work? Then, we should write a license that doesn't permit such behaviour.

## Release schedule

When deciding on how and when to make releases of our projects, we can go one or two routes: either based on work done, or based on periodic time intervals.

The first method relies on us having created a network map together with a set of milestones. Each milestone will then be a deliverable, a natural candidate for release. The benefit of this method is that we know in advance what each of our releases will contain, so we can prepare the people who'll use our project what they can expect. The drawback is that it can be difficult to plan for when a particular release is going to happen. It's easy to plan too much in one milestone, resulting in crunch to have it all ready on the planned release date.

With the other method, we decide a schedule, for example once a month, when we're going to make a new release of our project. Depending on how much work we've managed to complete during that time period, and what type, we decide on version numbers or similar tracking system. The benefit of this method is that we don't have to worry about whether we have the right amount of work planned for each release, because it doesn't matter. We release what's done, no more, no less. The drawback is that if our schedule is too frequent, we burden the users of our project with potentially many smaller and inconsequential updates; or if the schedule is too _infrequent_, our users will have to wait for long periods of time on updates that have been made a while ago, but are just sitting in wait for release. However, those types of problems can easily be remedied by having a treshold for making a new release (for example, if only a typo in the readme has been fixed, perhaps that shouldn't warrant a new release); and making sure that important updates, such as security issues and major bugs, are always released as soon as possible, regardless of when in the release schedule they occur.

I have chosen the latter method for my projects.