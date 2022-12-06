# Product Overview

- [General](#product-general)
- [Payment Settings](#product-payment-settings)
- [Pricing](#product-pricing)
  - [Coupons](#product-coupons)
- [Testing](#product-testing)

<a name="product-general"></a>

## General

On the 'General' tab of your product you can give it a name, a short description, upload an image and set a product URL.

> **Warning**  
> Whenever you change the product URL, the previous URL will be immediately invalid.

<a name="product-payment-settings"></a>

## Payment Settings

In this section you can assign a merchant (payment gateway) to your product.
For more information on adding/managing merchants please see the [Merchants](/docs/{{version}}/merchants) section.

Once you added one or more merchant(s) to your outlet, you can enable them by toggling the 'Active' switch.

<a name="product-pricing"></a>

## Pricing

🚧 Work in progress.

<a name="product-coupons"></a>

### Coupons

🚧 Work in progress.

<a name="product-testing"></a>

## Testing

If you use Stripe as your product merchant we will automatically switch to Stripe's test mode.

> **Warning**  
> **Any other merchants will incur a fee charge even in test mode unless you use test credentials for your merchant!**

You can toggle testing on & off at any time using the `Status` bar to the top right:

<img class="my-4" width="261" height="48" src="https://raw.githubusercontent.com/nexusmerchants/docs-orderforms/2.x/assets/images/status-switch.png?raw=true" alt="Status Switch" />

| Status     | Description                                                                    |
|------------|--------------------------------------------------------------------------------|
| `Disabled` | No one, including the owning account, can view the product.                    |
| `Test`     | Only the owning account (logged-in) can view the product and create purchases. |
| `Live`     | Everyone can view the product and create purchases.                            |
