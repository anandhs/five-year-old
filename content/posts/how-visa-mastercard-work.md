---
title: "How Do Visa and Mastercard Work?"
date: 2026-02-17
description: "A simple explanation of how card networks like Visa and Mastercard process payments."
tags: ["payments", "visa", "mastercard", "finance", "basics"]
categories: ["Learn"]
draft: false
image: "/images/diagrams/visa-mastercard-payment-flow.svg"
---

## What it is

Visa and Mastercard are global **card networks**. They are not banks.

Their main role is to move payment information between the businesses and banks involved in a card transaction.

When you pay with a card, several parties are involved:

- **Cardholder** (you)
- **Merchant** (the store)
- **Issuing bank** (the bank that gave you the card)
- **Acquiring bank / payment processor** (the merchant's side)
- **Card network** (Visa or Mastercard)

## Why

These networks matter because they make electronic payments fast, standardized, and trusted across countries.

They provide:

- common technical rules for payment processing
- fraud and risk controls
- global acceptance and interoperability
- settlement coordination between banks

Without card networks, each bank and merchant would need many direct integrations, which would be slow and expensive to scale.

## How does it work

A card payment usually has two phases:

1. **Authorization**: checks whether the payment can be approved.
2. **Clearing and settlement**: moves funds between financial institutions.

Typical flow:

1. You tap, insert, or enter your card details.
2. The merchant sends the request to its processor/acquirer.
3. The request is routed through Visa or Mastercard.
4. The issuing bank approves or declines based on balance/credit, fraud checks, and card status.
5. The decision returns to the merchant in seconds.
6. Later, batch clearing and settlement transfer funds from issuer side to acquirer side (minus fees).

![How a Visa/Mastercard card payment works](/images/diagrams/visa-mastercard-payment-flow.svg)

## More details (and references)

- [Visa: How Visa Works](https://usa.visa.com/run-your-business/small-business-tools/payment-technology/how-visa-works.html)
- [Mastercard: How payment processing works](https://www.mastercard.us/en-us/business/overview/support/payment-processing.html)
- [Federal Reserve: How modern payment card systems work](https://www.federalreserve.gov/paymentsystems.htm)
