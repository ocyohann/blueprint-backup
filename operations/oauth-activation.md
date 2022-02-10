# OAuth Activation

_Read first:_ [_App Security_](http://blueprint.openchannel.io/operations/app-security/) _| Read next:_ [_Program Agreements_](http://blueprint.openchannel.io/operations/agreements/)__

When activating an app, there are several different processes that can take place behind the scenes, depending on the type of app. For web integrations, a popular authorization protocol called [OAuth 2.0](https://nordicapis.com/the-difference-between-http-auth-api-keys-and-oauth/) is often used to grant apps controlled access to user accounts. On this page, we'll discuss:

* Authorization
* Scopes
* Examples

## Authorization

Authorization is when an app requests access to a user's account, since it needs various information and functionality in order to function. Authorization takes place when a user goes to activate an app: the app redirects the user to a special authorization URL on the platform owner's servers.

At this URL, the user will see a list of permissions the app is requesting:

![](<../.gitbook/assets/image (15).png>)

&#x20;If the user agrees to grant these permissions, they will be sent back to the app along with a temporary authorization code. By now, the app can be considered activated.

## Scopes

In OAuth 2.0, the permissions an app requests are called scopes. Platform owners should provide a list of scopes in their API documentation, as they often vary between platforms.

It's important that apps request only the scopes they need to function, so as to minimize security risks and increase user confidence.

## Examples

Many app marketplaces use OAuth 2.0 as the means to activate apps. To better understand how these platforms handle activation, look no further than [Slack](https://api.slack.com/authentication/oauth-v2) and [GitHub](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/) as great examples.

## What's Next?

We've discussed how OAuth 2.0 can be used to manage app activation. On the next page — [Program Agreements](http://blueprint.openchannel.io/operations/agreements/) — we'll look at why and how you should use various program agreements.
