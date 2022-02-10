# Invoicing and Billing

_Read first:_ [_Payments_](http://blueprint.openchannel.io/operations/payments/)__

Depending on the platform owner's preferences, they can either invoice for app sales themselves or have developers do so. If the platform owner chooses to invoice, there is also the option of consolidated invoicing, where the user organization receives a single invoice for the platform's core offering and any app purchases. On this page, we'll discuss:

* Developer Invoicing
* Marketplace Invoicing
* Consolidated Invoicing

## Developer Invoicing

For some app marketplaces, it may be easiest to leave invoicing to the developer. If apps are purchased on the marketplace itself, this entails the following two steps:

1. The platform owner automatically notifies the developer whenever one of their apps is sold, providing the billing details of the purchasing user.
2. Then, then developer organization makes out an invoice directly to the user, per whatever internal procedure.

Developer invoicing can be particularly useful for app marketplaces where apps are _not_ purchased on the marketplace, meaning that the user must contact the developer before they can purchase the app. In this case, the platform owner simply passes a lead onto the developer organization, who makes out an invoice to the user if and when a sale is made.

## Marketplace Invoicing

Generally speaking, the alternative to developer invoicing is marketplace invoicing, which is when the platform owner invoices users. Typically, the platform owner will invoice users on a sale-by-sale basis, providing a separate invoice for each purchase.

## Consolidated Invoicing

For platforms with a paid core offering, a popular variation on marketplace invoicing is consolidated invoicing. This entails the platform owner sending a single invoice — usually on a monthly basis — for the core offering together with any app purchases.

Consolidated invoicing has benefits for both the user and platform owner. In particular, since there are fewer invoices to manage, there is less accounting workload for both parties. For the user, this adds considerable simplicity.

### Implementation

The main downside to consolidated invoicing is the complex implementation. In order to automatically include all app purchases in a single invoice (together with the fee for the platform's core product), the platform owner would need to programmatically integrate marketplace records with an existing invoicing solution.

{% hint style="info" %}
Consolidated invoicing can be complicated. To make things easier, OpenChannel offers the APIs and webhooks you need to programatically read, write, and manage marketplace records.
{% endhint %}
