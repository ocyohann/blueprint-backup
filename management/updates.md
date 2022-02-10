# Updates

_Read first:_ [_Approval and Rejection_](https://blueprint.openchannel.io/management/approval-rejection/) _| Read next:_ [_Onboarding_](https://blueprint.openchannel.io/developer/onboarding/)__

Sooner or later, third-party developers will want to update their apps. Thankfully, handling updates is similar to handling new [app submissions](http://blueprint.openchannel.io/management/submission/). On this page, we'll discuss:

* Taking Updates
* Reviewing Updates
* App Versioning

## Taking Updates

Developers should be able to submit an update for any of their apps through the developer dashboard. Usually, this option is located next to each app status on the _My Apps_ (or equivalent) page, but it may also be located on the settings page for each app.

![](<../.gitbook/assets/0 (7).png>)

Most app marketplaces collect updates through a dedicated form, which may be the same form used for new app submissions. The form is pre-populated with the app's existing metadata, which the developer modifies according to the changes they are making. The marketplace may also require the developer to submit a changelog, as reference for both review teams and users.

## Reviewing Updates

As with new app submissions, marketplace administrators should receive a notification when an update is submitted. In many ways, the [review process](http://blueprint.openchannel.io/management/review/) is the same, consisting of one or many teams depending on the size and preference of the app marketplace.

One major difference when reviewing app updates is that only the items which have changed should be reviewed. To this end, app marketplaces should automatically compare incoming updates to previous versions of an app, highlighting the [_diff_](https://en.wikipedia.org/wiki/Diff) to review teams.

In marketplaces where the review process consists of multiple stages, it may be possible to forego one or more stages if those aspects of the app remain unchanged. For example, if a developer updates the description of their app, a functional test is not necessary as part of the review process.

## App Versioning

The developer almost always has control over the naming and numbering of versions. However, when the developer makes a change to the behavior of the app itself (i.e. not just its assets), they should be required to increment the version number.

## What's Next?

We've discussed how to process app updates, including the update submission process and versioning policies. In the upcoming sections, we'll talk about optimizing the Developer Experience in app marketplaces, starting with [Onboarding](https://blueprint.openchannel.io/developer/onboarding/).
