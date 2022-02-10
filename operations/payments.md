# Payments

_Read first:_ [_Program Agreements_](http://blueprint.openchannel.io/operations/agreements/) _| Read next:_ [_Invoicing and Billing_](http://blueprint.openchannel.io/operations/invoicing/)__

On marketplaces with paid apps, the platform owner is usually responsible for handling payments, especially if they choose to implement [revenue sharing](http://blueprint.openchannel.io/success/monetization/). There are two basic models for handling payments, both of which often involve the use of a dedicated payment processor. On this page, we'll discuss:

* Payment Models
* Payment Processors

## Payment Models

When it comes to payments, platform owners have two basic models to choose from. With on-marketplace payments, users pay for apps on the marketplace itself, upon activating them. With through-marketplace payments, users pay for apps externally, usually at a later date.

### On-Marketplace

An on-marketplace payment is when the user pays for an app while activating it. In this case, the user fills out a purchase form — which contains information such as the chosen plan and/or number of licenses — before making the payment immediately, as they would any other online purchase.

If a platform owner chooses this approach, they are likely to integrate with a dedicated payment processor. Depending on the payment processor chosen, a range of payment methods (almost always including payment cards) may be supported and it may be possible to automatically distribute developer payouts.

![](<../.gitbook/assets/image (10).png>)

__[_Stripe Connect_](https://stripe.com/en-gb/connect) _is a popular payment process for on-marketplace payments._

### Through-Marketplace

A through-marketplace payment is when the user does not pay for an app while activating it. Instead, purchase information is forwarded to the platform owner's invoicing system, which generates an invoice for the user at a later date.

This invoice may include a single app, multiple apps, or both apps and other platform fees (as in [consolidated invoicing](https://blueprint.openchannel.io/operations/invoicing#consolidated-invoicing)). Depending on the platform owner's preference, the invoice may be payable by a dedicated payment processor, wire transfer, or other payment method.

Through-marketplace payments are most common for higher cost apps, especially in in B2B environments and highly-regulated industries, where users often pay a sizable subscription fee for the core product/platform itself.

## Payment Processors

Most platform owners will choose to integrate a dedicated payment processor to handle app purchases. Popular payment processors for app marketplaces include:

* [Stripe Connect  ](https://stripe.com/connect)
* [Braintree Marketplace  ](https://www.braintreepayments.com/products/braintree-marketplace)
* [PayPal for Marketplaces  ](https://www.paypal.com/us/webapps/mpp/partner-marketplaces)
* [Ayden Marketplace  ](https://www.adyen.com/our-solution/online-payments/marketplaces)
* [Bluesnap Marketplaces  ](https://home.bluesnap.com/payments-for-marketplaces/)
* [WorldPay](https://online.worldpay.com)
* [Dwolla](https://www.dwolla.com)
* [WePay](https://go.wepay.com)

When choosing from this list, important considerations are how easy it will be to integrate the payment processor and whether automatic distribution of developer payouts (as in revenue sharing agreements) is supported.

{% hint style="info" %}
For more information on choosing a payment processor, see [this blog post](https://openchannel.io/blog/marketplace-payments-paypal-stripe/).
{% endhint %}

## What's Next?

We've discussed how to process payments on an app marketplace. On the next page —[Invoicing and Billing ](http://blueprint.openchannel.io/operations/invoicing/)— we'll look at the most popular models for invoicing users for their app purchases.
