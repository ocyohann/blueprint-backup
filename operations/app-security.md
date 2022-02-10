# App Security

_Read first:_ [_Metrics and KPIs_](https://blueprint.openchannel.io/success/metrics/) _| Read next:_ [_OAuth Activation_](http://blueprint.openchannel.io/operations/oauth-activation/)__

Although the responsibility of app security ultimately lies with the developer, platform owners can and should take steps to ensure their app marketplace is safe and can be used with confidence by users. On this page, we'll discuss:

* App Security Lifecycle
* Security by App type
* Best Practices

## App Security Lifecycle

Maintaining app security often begins before any apps are submitted. For example, platform owners can mandate all new developers hold a security certification like ISO 27001. Additionally, platform owners can outline security requirements during the onboarding process (usually in the developer agreement) and in the platform's developer portal.

![](https://lh3.googleusercontent.com/9WyEvMsEA-JtLyRN-sxvjSSDyQ7pnBdsmWePi6Sos13Oa71otQ5d5OrXdCTko4VLMPadoe2qAoQe2Bnr5-xNY4RGkEsv\_H54ul85xxfC4UkR1x3piA8IZONbo7TuBTDK79xyDVpm)

During submission, platform owners can require developers to declare that they have taken appropriate steps to ensure their apps meet the platform's security requirements. As part of this, platform owners may wish to create automatic security checks, which developers run against their apps prior to submission.

Once an app has been submitted, its security should always be reviewed individually. For this, platform owners can conduct or outsource various app security checks, such as functional tests or automated code scans.

## Security by App Type

There are certain security considerations to keep in mind for each type of app.

### Web Integrations

Since web integrations make use of a platform's APIs, the security of those APIs is paramount. Access to APIs should be controlled using API secrets, and trusted processes like OAuth 2.0 should be used wherever possible. Of course, all API traffic should be encrypted, using HTTPS as a bare minimum.

Regardless of API security, web integrations should still be tested on an app-by-app basis. What's more, usage monitoring can be used to identify behind-the-scenes API abuse.

### Downloadable Files

To ensure the security of downloadable files, verifications like [MIME type](https://www.metadata2go.com/file-info/mime-type) should be used to check the app is a suitable file type. Additionally, virus scanning tools of some kind should be used to scan for any viruses.

It's also important to distribute downloadable files in a secure way. Ideally, apps should be served through signed download URLs, which can only be used for a limited period of time.

### Containers and Charts

Tools like container scanning tools and smoke tests should be used to check whether containers and charts are secure and that they work as intended.

Additionally, a process like container signing can be used to help users to verify the integrity of the app they are accessing.

## Best Practices

Here are two best practices for securing your app marketplace:

* **Know your users.** When developing a security strategy, consider who your users are and what they would expect from you. For large enterprises or financial institutions, you may wish to implement additional security measures and standards, such as penetration tests or SOC I/II certifications.
* **Help developers help you.** As the number of apps on your marketplace grows, so does the risk of a vulnerability. Before you strive to test each app rigorously, invest in creating a clear, actionable list of security guidelines for developers.

{% hint style="success" %}
For more best practices on app security, see the guidelines the Atlassian Marketplace sets for its developers in the [Security Self-Assessment Program](https://developer.atlassian.com/platform/marketplace/security-self-assessment-program/#applying-to-the-security-self-assessment-program).
{% endhint %}

## What's Next

We've discussed how and when to check for app security. On the next page — [OAuth Activation](http://blueprint.openchannel.io/operations/oauth-activation/) — we'll look at how OAuth 2.0 is often used to activate apps such as web integrations.
