---
title: Common questions about billing
---

## Can I have a trial?

PostHog is usage-based and you can use it for free for as long as you want, no trial needed. See [our pricing page](/pricing) for free usage allowances.

If you have special circumstances where this doesn't work for you, contact our [sales team](/talk-to-a-human). 

## How do I estimate how much PostHog will cost?

You can check our doc on [estimating usage and costs](/docs/billing/estimating-usage-costs), or use the [pricing calculator](/pricing) to estimate costs. However, often the best way to estimate costs is to signup for free and go from there.

## How do I update billing information or see previous months' invoices or usage?

Go to your organization's [billing settings](https://app.posthog.com/organization/billing) and click **Manage card details and view past invoices** to be brought to Stripe where you can update your credit card, billing information, and see your invoice history.

You can also download invoices or receipts from here by clicking on them under **Invoice history**.

![Invoices](https://res.cloudinary.com/dmukukwp6/image/upload/Clean_Shot_2024_09_19_at_16_44_05_2x_1c2cc687c2.png)

## Can I set a billing limit?

Yes, you can set a billing limit for each of PostHog's products in your organization's [billing settings](https://app.posthog.com/organization/billing). Check out our doc on [billing limits and alerts](/docs/billing/estimating-usage-costs) for more information.

## Are events or replays dropped when I reach billing limits?

Yes, PostHog drops data after you go over your billing limit. To capture more during the current billing period, you need to raise your billing limits. For future billing periods, you can tune your PostHog implementation to limit the number of [events](/tutorials/fewer-unwanted-events) or [session replays](/tutorials/limit-session-recordings) you capture.

## I'm an early-stage startup or non-profit, can I get a discount?

Yes, early-stage startups can get $50,000 in credits, merch, and exclusive events. Find out more and apply on our [startup program page](/startups).

Non-profits can contact our [sales team](/talk-to-a-human) after signing up to discuss discount options.

## Can I change the email invoices or billing alerts are sent to?

We send billing emails to all owners and administrators in the organization. These are important emails, so we currently don't allow these notification settings to be configured.

If you'd like a specific email address to receive these communications, we recommend inviting that email to your organization and assigning them an administrator role.
