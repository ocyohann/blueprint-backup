# Review

_Read first:_ [_Submission_](http://blueprint.openchannel.io/management/submission/) _| Read next:_ [_Approval and Rejection_](https://blueprint.openchannel.io/management/approval-rejection/)__

Before they are added to the marketplace, all apps should be reviewed against various quality, security, and other standards. The three most important concepts in managing a smooth review process are:

* Review Teams
* Review Interface
* Review Process

## Review Teams

Depending on the size of the app marketplace, there may be one or more teams responsible for reviewing apps. In smaller marketplaces, it's common to see a single team responsible for all areas of marketplace administration, including app review. In larger marketplaces, there are usually dedicated app review teams, which exclusively review and document submissions.

Larger app marketplaces may also choose to have a dedicated team for each stage of the review. For example, some marketplaces might have a security team for reviewing [app security](http://blueprint.openchannel.io/operations/app-security/). Other stages of the review process that might warrant a dedicated team include:

* Compliance (especially in heavily regulated industries)
* Functional testing
* Marketing
* Finance

{% hint style="info" %}
It's important to adapt as your marketplace scales. With OpenChannel Pipelines, marketplace administrators can add to, remove from, and modify the app review process — including who is responsible for each stage — at any time.
{% endhint %}

## Review Interface

The app review process is usually managed through a dedicated interface. This interface allows review teams to access the items provided in the submission, communicate with the developer, and change the [status of the app](http://blueprint.openchannel.io/management/app-statuses/).

![](<../.gitbook/assets/0 (5).png>)

_Marketplace administrators should have access to a list of all apps, including those Pending Review._

![](<../.gitbook/assets/1 (5).png>)

_By clicking on an app, marketplace administrators should be able to see what items were included in the submission._

Some platforms may instead choose to manage the review process through emails, spreadsheets, and/or various external project management tools. We don't recommend this, as the marketplace itself should be the single source of truth for app statuses.

## Review Process

When an app or app update is submitted, the review team should receive a notification, starting the review process. In larger marketplaces with a high volume of submissions, dedicated review teams may wish to customize their notifications and also check for new app submissions proactively (e.g. every morning).

Regardless of whether there is one or more review teams, the app review process usually consists of several distinct stages:

* **Asset review** — app assets and other metadata are reviewed
* **Functional test** — the app itself is tested to ensure it behaves as intended
* **Security checks** — various aspects of app security are tested

Depending on whether an app does or doesn't meet the marketplace's criteria, the review team (or one of the review teams) can approve or reject the app. If the app is [approved](https://blueprint.openchannel.io/management/approval-rejection/), it is automatically added to the marketplace. If it is rejected, the submission is sent back to the developer with feedback.

![](<../.gitbook/assets/2 (4).png>)

## What's Next?

We've discussed how the app review process works. On the next page — [Approval and Rejection](https://blueprint.openchannel.io/management/approval-rejection/) — we'll look at the three major actions a marketplace administrator can take on an app or app submission.
