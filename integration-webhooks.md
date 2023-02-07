# Webhooks

- [Order & Customer Data](#full-order-data)
- [Order Data](#order-data)
- [Customer Data](#customer-data)

<a name="introduction"></a>

## Introduction

Webhooks allow you to send order and/or customer data to a specified URL.

<a name="full-order-data"></a>

## Order & Customer Data

Example of a complete order data payload:

<pre class="language-json"><code style="padding:0 1rem">
{
    "uuid": "fb292cb1-ee35-405f-8409-cef723e3xxxx",
    "hashid": "RkR",
    "amount": 2500,
    "currency": "usd",
    "status": "succeeded",
    "timestamp": 1672807227,
    "created_at": "2023-01-04T10:22:24+00:00",
    "product":
    {
        "uuid": "3d319e29-250e-4972-8d95-837396b8xxxx",
        "name": "Expensive Soda Pack"
    },
    "price":
    {
        "uuid": "e7d769d9-e104-47e2-a2ae-2cecc7f6xxxx",
        "name": "One Time ($25.00)",
        "type": "single",
        "frequency": 1,
        "frequency_unit": "month",
        "cycles": 0,
        "price": 2500,
        "subscription_price": 0,
        "trial_days": 0
    },
    "customer":
    {
        "uuid": "d4d7a634-887f-4c80-87ba-f5b404aaxxxx",
        "first_name": "John",
        "middle_name": null,
        "last_name": "Doe",
        "email": "jdoe@example.com",
        "phone": null,
        "company_name": null,
        "address_1": "High Trail",
        "address_2": null,
        "city": "Square Rock Corner",
        "state": "Texas",
        "postal_code": "12345",
        "country": "USA",
        "shipping_phone": null,
        "shipping_address_1": null,
        "shipping_address_2": null,
        "shipping_city": null,
        "shipping_state": null,
        "shipping_postal_code": null,
        "shipping_country": null
    },
    "merchant":
    {
        "type": "Stripe",
        "account_id": "acct_1CA...",
        "name": "My Stripe Account"
    }
}
</code></pre>

<a name="order-data"></a>

## Order Data

Example of a order data payload:

<pre class="language-json"><code style="padding:0 1rem">
{
    "uuid": "fb292cb1-ee35-405f-8409-cef723e3xxxx",
    "hashid": "RkR",
    "amount": 2500,
    "currency": "usd",
    "status": "succeeded",
    "timestamp": 1672807227,
    "created_at": "2023-01-04T10:22:24+00:00",
    "product":
    {
        "uuid": "3d319e29-250e-4972-8d95-837396b8xxxx",
        "name": "Expensive Soda Pack"
    },
    "price":
    {
        "uuid": "e7d769d9-e104-47e2-a2ae-2cecc7f6xxxx",
        "name": "One Time ($25.00)",
        "type": "single",
        "frequency": 1,
        "frequency_unit": "month",
        "cycles": 0,
        "price": 2500,
        "subscription_price": 0,
        "trial_days": 0
    },
    "merchant":
    {
        "type": "Stripe",
        "account_id": "acct_1CA...",
        "name": "My Stripe Account"
    }
}
</code></pre>

<a name="customer-data"></a>

## Customer Data

Example of a customer data payload:

<pre class="language-json"><code style="padding:0 1rem">
{
    "uuid": "d4d7a634-887f-4c80-87ba-f5b404aaxxxx",
    "first_name": "John",
    "middle_name": null,
    "last_name": "Doe",
    "email": "jdoe@example.com",
    "phone": null,
    "company_name": null,
    "address_1": "High Trail",
    "address_2": null,
    "city": "Square Rock Corner",
    "state": "Texas",
    "postal_code": "12345",
    "country": "USA",
    "shipping_phone": null,
    "shipping_address_1": null,
    "shipping_address_2": null,
    "shipping_city": null,
    "shipping_state": null,
    "shipping_postal_code": null,
    "shipping_country": null
    "timestamp": 1672807227,
    "created_at": "2023-01-04T10:22:24+00:00"
}
</code></pre>
