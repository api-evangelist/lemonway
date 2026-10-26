# Lemonway

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Lemonway is a European payment institution regulated by the French ACPR (registration 16568) since 2012, providing REST APIs for marketplace payments. The platform is trusted by over 1,400 marketplaces and 200 crowdfunding platforms across Europe.

## Overview

Lemonway provides a modular, feature-rich payment infrastructure API enabling marketplace operators to offer pay-in, wallet management, KYC/KYB onboarding, P2P transfers, and pay-out capabilities—all under a single regulated payment institution umbrella.

**Key metrics:** 99.9% uptime, 150 million API calls/month capacity, 678 ms average response time, PCI-DSS certified.

## APIs

- **Lemonway API** — Core REST API for payments, wallets, KYC, transfers, and payouts
- **Lemonway Onboarding API** — Online KYC/KYB onboarding flows for individual and legal entity account holders

## Supported Payment Methods

- Card payments (Visa, Mastercard, CB) with 3D Secure v2
- SEPA bank transfers and direct debit
- Virtual IBAN
- PayPal
- Apple Pay and Google Pay
- Buy Now Pay Later (BNPL)
- Pay by Bank and Pay by Link
- Multibanco and MBWay
- Cheques

## Key Capabilities

- IBAN wallet creation and management
- KYC/KYB identity verification and document upload
- P2P wallet-to-wallet transfers
- Pre-authorization, multi-capture, and recurring payments
- Refunds and dispute management
- Webhook notifications
- Magento and Mirakl connectors
- Hosted card payment fields (React, Vue.js, Angular SDKs)

## Marketplace Models

Lemonway supports B2B, B2C, and C2C marketplace payment flows.

## Developer Resources

- [Documentation](https://documentation.lemonway.com/)
- [API Reference](https://documentation.lemonway.com/reference/lemonway-api)
- [Developer Hub](https://www.lemonway.com/en/developers)
- [Sandbox Access](https://documentation.lemonway.com/docs/how-to-access-lemonway-tools-and-services)
- [API Status](https://documentation.lemonway.com/page/api-status)
- [Support](https://support.lemonway.com/hc/en-us)
- [Pricing](https://www.lemonway.com/en/pricing)
- [GitHub (official SDKs)](https://github.com/lemonwaysas)

## Regulatory

Regulated European Payment Institution under French ACPR supervision since 2012 (registration 16568). Compliant with PSD2/PSD3 and AML/CFT requirements.
