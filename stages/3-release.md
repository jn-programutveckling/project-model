# Release stage

This is the third stage of the project model. In this stage we prepare work we've already done to make a release of a new version, we make sure that all tests pass, we write final documentation and we advertise our release. As with all stages in the model, the release stage isn't meant to be visited just once. Each stage should be seen as part of one iteration of development, not just part of the whole project life cycle.

1. Each month after the project has started, and if there has been any releasable work done…
   1. Look at the completed work since last release and from that determine what version number the new release should have.
   2. Create a new branch from `develop`, called `release/v{new version number}`, for example *v1.0.3*.
   3. Make sure all unit tests pass.
   4. Make sure the code is documented, as well as read-me and other documents.
   5. Update the change-log with links to the new version and version history. See the [change-log template](../templates/tpl-CHANGELOG.md) for more information.
   6. Merge the *release* branch with the `master` branch, as well as with `develop`.
   7. Create a new git tag with the version number and a new GitHub release. In the release comment, copy the appropriate change-log notes.
   8. If the release is v1.0.0, decide whether to make the repository public or let it remain private.
2. Whenever a new release has been published on GitHub…
   1. Write a blog post about it on my website.
   2. If the new version signifies a big change, record a video where I show those changes to YouTube.