---
title: Security
description: How we keep your practice data safe.
effective_date: 2026-11-01
last_updated: 2026-11-01
---

We understand that the information you manage in Addison requires careful handling: client names, contact details and appointment records. Security is built into how we operate, not bolted on as an afterthought.

## Where Your Data Lives

The Addison application and its database run in the Asia Pacific (Sydney) region, so your client records and appointment data stay within the ANZ jurisdiction.

Two things sit outside that boundary, and we would rather name them than let you discover them later:

- Practitioner profile photographs are held in Cloudflare R2 object storage, which is not pinned to the Sydney region.
- Supporting services for network delivery, email, logging and payments may process data in other regions.

No client information leaves the region through either. We do not store your data in countries with weaker data protection standards, and the full breakdown is set out in our [Privacy Policy](/legal/privacy#international-data-transfers).

## Encryption

Your data is encrypted in transit and at rest. This means information is protected both when it travels between your device and our servers, and when it is stored on our infrastructure.

## Access Controls

Access to production systems and customer data is strictly limited to personnel who need it to provide the Service. We use two-factor authentication (2FA) across our internal tooling and infrastructure.

## Backups

Your data is automatically backed up on a regular basis. In the event of a system failure, we can restore data from recent backups to minimise any disruption.

## What We Do Not Claim

Addison is built and operated by a small team, and we would rather tell you exactly where we stand than imply more than we do. We do not hold ISO 27001 or SOC 2 certification, and we do not run a scheduled penetration testing programme.

If you are evaluating Addison for a practice or completing a supplier assessment, ask us. We will answer straight.

## Incident Response

If we confirm a security incident affecting your data, we will tell you what we know within 72 hours, and follow up with a full report within 10 working days. We take immediate steps to contain and remediate the issue, and we will give you the detail about the information involved that you need to meet your own obligations to your clients.

Where required by law, we will also notify the relevant Privacy Commissioner. Full detail is in our [Privacy Policy](/legal/privacy#if-there-is-a-breach).

## Our Subprocessors

We work with a small number of trusted infrastructure providers, including Laravel Cloud, AWS, Stripe and Resend. Each one is bound by a data processing agreement and maintains its own rigorous security standards. You can find the full list on our [Subprocessors](/legal/subprocessors) page.

## Responsible Disclosure

If you discover a potential security vulnerability in Addison, please let us know responsibly before disclosing it publicly. Contact us at [security@addison.nz](mailto:security@addison.nz) and we will investigate promptly.

## Questions

If you have any questions about how we secure your data, we are happy to help. [Get in touch](mailto:hello@addison.nz).