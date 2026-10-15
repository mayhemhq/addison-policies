---
title: Privacy Policy
effective_date: 2026-11-01
last_updated: 2026-11-01
---

Addison ("**Addison**", "**we**", "**us**" or "**our**") is a booking and practice management platform for mental health practitioners in New Zealand and Australia. Addison is owned and operated by **Mayhem Labs Limited** (NZBN 9429052645211), a company registered in New Zealand.

We protect personal information in line with the New Zealand Privacy Act 2020, the Health Information Privacy Code 2020 (HIPC), and the Australian Privacy Act 1988 (Cth), including the Australian Privacy Principles (APPs).

Client information held in Addison is health information. In New Zealand it is governed by the HIPC, which applies in place of the information privacy principles in the Privacy Act, and we handle it on that basis.

This policy explains how we collect, use, store and disclose personal information when you use Addison or visit our website.

## The short version

- **Your clients' information belongs to you.** We hold it on your behalf, as your agent, and use it only to run Addison for you.
- **We don't store clinical notes**, session recordings or diagnostic information.
- **Your data is hosted in Sydney, Australia.** The few exceptions are listed under [International data transfers](#international-data-transfers).
- **We never sell data** or use it for advertising.
- **We tell you about breaches early**, even ones that aren't legally notifiable.
- **You're responsible for retaining your health records.** Our retention periods don't meet your obligations, so export before you delete.

## Who is responsible for client information

**You are the agency in relation to your clients' information. Addison holds and processes that information on your behalf, as your agent.**

Under section 11 of the Privacy Act 2020, information held by an agent on behalf of another agency is treated as held by that agency. We have no direct relationship with your clients, we don't decide what is collected about them, and we use their information only to provide the Service to you and on your instructions.

In practice, the obligations owed to your clients under the HIPC (collection, notification, access, correction and retention) sit with you. If client information is compromised, you are generally the party who must assess and notify the breach, and we will give you what you need to do that.

The terms of this relationship are set out in our [Data Processing Agreement](/legal/data-processing).

## What information we collect

Addison is a scheduling and practice management tool. We do not store clinical notes, session recordings or diagnostic information.

In a mental health context, even scheduling data such as a client's name, contact details and appointment times can be sensitive, because it may show that a person is accessing mental health support. We treat all client information accordingly and collect only what is needed to run the platform.

### Practitioner account information

- Name, email address and contact details
- Professional registration details (for example, NZPB or AHPRA registration numbers)
- Billing information (processed by Stripe; we never store card details)
- Platform settings and preferences

### Client booking information

- Client names and contact details entered by you, or submitted by a client through your booking link
- Appointment scheduling data and session history
- ACC, EAP and private funding allocation records

### Usage and technical data

- Log data, IP addresses and browser or device information
- Feature usage patterns, used to improve the platform

### Website visitors

When you visit addison.nz or withaddison.com, we collect standard request data (such as IP address and browser type) through our hosting and security providers. If you submit an enquiry form or subscribe to our newsletter, we collect the details you provide.

## Why we collect it

- To provide and operate Addison
- To manage appointment scheduling and funding allocation tracking
- To process subscription payments through Stripe
- To provide support and respond to enquiries
- To improve the platform and develop new features
- To keep the platform secure and prevent fraud or unauthorised access
- To meet our legal and regulatory obligations

We do not sell personal information, and we do not use client information for advertising, marketing or to train AI models.

## How we collect it

- **Directly from you**, when you create an account, manage client profiles and appointments, or contact us.
- **From clients, on your behalf**, when they submit a booking request through your booking link.
- **Automatically**, through cookies and similar technologies that keep you signed in, keep the platform secure and help us understand how features are used.

## Calendar integrations

### Google Calendar

If you connect a Google Calendar, we request the read-only `https://www.googleapis.com/auth/calendar.readonly` scope, along with the standard `openid` and `email` scopes used to identify the connected Google account. The calendar scope only lets Addison see your calendar list and the events on it. It does not let Addison create, edit or delete anything on your Google Calendar.

We use this access only to check your availability. Addison reads the events on the calendars you opt in to and treats any event marked busy as a block on that time, so clients can't book an appointment that clashes with something already on your calendar.

Calendar data is not stored permanently. We keep a rolling cache of events inside the sync window (title, start and end time, and busy status) so availability can be checked without calling Google on every request. Each sync replaces that cache in full, so events are removed once they fall outside the window, and disconnecting a calendar deletes the cached data immediately.

Calendar data is never shared with third parties beyond what is needed to provide the Service, never used for advertising, and never sold.

Addison's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## How long we keep information

| Information | How long |
|---|---|
| Account information | For the life of your subscription. Deleted within 90 days of account closure, unless the law requires us to keep it. |
| Client booking records | While your account is active. Deleted 90 days after account closure. You can [request an export](/legal/data-requests) at any time, including after closure. |
| Usage and technical data | Up to 24 months, for platform improvement and security monitoring. |
| Application logs (Laravel Nightwatch) | 90 days. |

### Retaining health records is your responsibility

Appointment and session history is health information about your client, and forms part of the health record you're required to keep. Under the New Zealand Health (Retention of Health Information) Regulations 1996, a provider must generally retain health information for at least **10 years from the date of the most recent service**. Equivalent obligations apply under state and territory health records legislation in Australia.

Addison's retention periods are set for our own operation of the platform and are shorter than that. They do not satisfy your professional retention obligation, and our deletion of a record does not discharge it.

Before you delete a client record or close your account, [request an export](/legal/data-requests) of the records you need to keep and store them under your own control. Exports are currently prepared manually by our team, so allow a few working days rather than leaving it to the last day of the retention window.

Deleting a client record in Addison is permanent. Once it has been removed from our backups, we cannot recover it for you. If you need a record removed but are still within your retention period, export it first.

## Your rights

### New Zealand

Under the Privacy Act 2020 and the HIPC, you have the right to:

- Access personal information we hold about you
- Ask us to correct information that is inaccurate or incomplete
- Be told how your information is collected and used
- Complain to the Office of the Privacy Commissioner if you believe we have breached the Act

### Australia

Under the Privacy Act 1988 and the APPs, you have the right to:

- Access personal information we hold about you
- Ask us to correct information that is inaccurate, out of date, incomplete, irrelevant or misleading
- Opt out of direct marketing
- Complain to the Office of the Australian Information Commissioner (OAIC) if you believe we have breached the APPs

To use any of these rights, email [privacy@addison.nz](mailto:privacy@addison.nz). We will respond to New Zealand requests within 20 working days, and to Australian requests within 30 days.

**If you are a client of a practitioner who uses Addison**, please contact your practitioner directly. They hold your information and are responsible for responding to your request. If your request reaches us, we will pass it to them. See [Data requests](/legal/data-requests) for how this works.

## Data security

We use technical and organisational measures to protect personal information from unauthorised access, loss or disclosure, including:

- Encryption in transit (TLS) and at rest
- Application and database hosting in the Asia Pacific (Sydney) region
- Authentication for all access to the platform, with data isolated to your organisation
- Multi-factor authentication on the internal accounts and infrastructure we use to run Addison
- Staff and contractor access limited to what each role needs

Addison is run by a small team and we describe our security as it actually is. We don't currently hold a certification such as ISO 27001 or SOC 2, and we don't run a scheduled penetration testing programme. No system is completely secure.

Full detail, including how to report a vulnerability, is on our [Security](/legal/security) page.

### If there is a breach

If we confirm a privacy breach affecting information held in Addison, we will:

- **Send an initial notice** to affected practitioners without undue delay, and no later than **72 hours** after we confirm the breach.
- **Send a full report** within **10 working days** of the initial notice, setting out the cause, the information affected, what we did to contain it and what we are changing.
- **Tell you even if the breach isn't legally notifiable**, so you can make your own assessment as the agency responsible for your clients' information.
- **Notify the regulators** (the Office of the Privacy Commissioner, and the OAIC where Australian individuals are affected) where a breach is likely to cause serious harm.

Where a breach concerns client information, notifying the affected clients is generally your responsibility as the agency holding that information. We will give you the detail you need to do it.

## Who we share information with

We use a small number of service providers (subprocessors) to run Addison, including Laravel Cloud and AWS for hosting, Cloudflare for network security, Stripe for payments, Resend for email and Laravel Nightwatch for monitoring. Each is bound by a data processing agreement.

The full list, what each provider does, where it processes data and a link to each agreement is on our [Subprocessors](/legal/subprocessors) page.

We will email practitioners at least **30 days before** adding a new subprocessor that will process client or practitioner information, so you have time to review it and, if you object, export your data and close your account. In an emergency, for example where a provider fails or must be removed for security reasons, a replacement may happen faster, and we will tell you as soon as we can.

We may also disclose information where the law requires it, for example in response to a valid court order. Where we're legally able to, we will tell you first.

## International data transfers

The Addison application and database are hosted in the Asia Pacific (Sydney) region, so client booking records and practitioner account data are stored in Australia. Some data is processed elsewhere:

- **Network transit.** Requests to Addison pass through Cloudflare's global network and are normally handled at the location nearest the user, typically Auckland or Sydney. Cloudflare may route traffic through other locations. Data is encrypted in transit throughout.
- **Profile photos.** The only files Addison stores are practitioner profile photographs, held in Cloudflare R2. This storage isn't pinned to the Sydney region, so those images may be stored outside Australia and New Zealand. They are encrypted at rest and private. No client information leaves the Sydney region through file storage.
- **Supporting services.** Laravel Nightwatch, Resend, Stripe and Vercel operate globally and may process data in the United States and other countries.

Where information is transferred overseas, we rely on contractual protections with each provider to make sure it is protected to a standard comparable to New Zealand and Australian law.

## Artificial intelligence

AI features are currently disabled in production, and no client or practitioner data is sent to any AI provider. Before any client data is processed by an AI model, we will update this policy and notify practitioners at least 30 days in advance. Client data will never be used to train AI models.

## Practitioner responsibilities

As the practitioner, you are responsible for:

- **Consent.** Obtaining appropriate informed consent from clients for the use of digital booking and practice management tools. Our [Client Service Agreement template](/legal/client-service-agreement) gives you wording you can use.
- **Indirect collection notices.** Since **1 May 2026**, IPP 3A of the Privacy Act 2020 requires an agency that collects personal information about someone from a third party to tell that person who holds it, why it was collected, and their rights of access and correction. This applies to information you enter into Addison from a referrer, agency, funder or family member rather than from the client.
- **Record retention.** Keeping health records for the period required by the Health (Retention of Health Information) Regulations 1996 or equivalent Australian law, including exporting records from Addison before deleting them.
- **Professional obligations.** Making sure your use of Addison meets the codes of ethics and registration standards that apply to you.

## Information about young people

**Addison accounts are for practitioners.** The Service isn't directed to anyone under 18, and we don't knowingly allow anyone under 18 to hold an Addison account.

**Client records may relate to young people.** Practitioners see children and adolescents, and client records in Addison may include people under 18. That information is entered by the practitioner, who is responsible for holding the appropriate consent or authority and for meeting the obligations owed to that young person under the HIPC. We protect these records the same way as all other client information.

If a young person, parent, guardian or other representative wants to access or correct a record held in Addison, the request should go to the practitioner holding it. If a request reaches us directly, we will refer it to the practitioner rather than act on it ourselves.

## Changes to this policy

We may update this policy from time to time. When we do, we will update the date at the top of this page. For material changes, we will email the address associated with your account before the change takes effect.

Every change to this policy is publicly recorded in our [policy history on GitHub](https://github.com/mayhemhq/addison-policies).

## Our Privacy Officer

Under section 201 of the Privacy Act 2020, we have appointed a Privacy Officer, who is responsible for our compliance with the Act and the HIPC, handling privacy requests and complaints, and working with the Office of the Privacy Commissioner.

**Ashton Baker**, Privacy Officer
Mayhem Labs Limited
Email: [privacy@addison.nz](mailto:privacy@addison.nz)

## Contact us

For questions, concerns or requests about this policy or how we handle data:

**Addison** (Mayhem Labs Limited)
Email: [privacy@addison.nz](mailto:privacy@addison.nz)
Website: [addison.nz](https://addison.nz)

If you're not satisfied with our response, you can complain to the [Office of the Privacy Commissioner](https://www.privacy.org.nz) (New Zealand) or the [Office of the Australian Information Commissioner](https://www.oaic.gov.au) (Australia).