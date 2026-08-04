# ClickSend (clicksend)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ClickSend is a cloud communications company providing a single REST API for business messaging across SMS, MMS, voice / text-to-speech, transactional email, and physical post - letters and postcards printed and mailed globally. The v3 API (rest.clicksend.com/v3) uses HTTP Basic authentication with a username and API key and covers sending, delivery receipts, inbound handling, contacts and lists, and account balance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clicksend/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clicksend/refs/heads/main/apis.yml)

## Tags

- Communications
- SMS
- MMS
- Voice
- Email
- Post
- Messaging
- CPaaS

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### ClickSend SMS API

Send single or bulk SMS worldwide, price a message before sending, view outbound history, cancel queued messages, and manage reusable SMS templates via POST /sms/send, /sms/price, /sms/history, /sms/{message_id}/cancel and /sms/templates.

- **Human URL:** [https://developers.clicksend.com/docs/messaging/sms](https://developers.clicksend.com/docs/messaging/sms)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- SMS
- Messaging
- Text

#### Properties

- [Documentation](https://developers.clicksend.com/docs/messaging/sms)
- [API Reference](https://developers.clicksend.com/docs/rest/v3/)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend MMS API

Send multimedia messages with an image or media file and subject line, price MMS, and pull MMS history via POST /mms/send, /mms/price and GET /mms/history. Media is referenced from an uploaded file URL.

- **Human URL:** [https://developers.clicksend.com/docs/messaging/mms](https://developers.clicksend.com/docs/messaging/mms)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- MMS
- Multimedia
- Messaging

#### Properties

- [Documentation](https://developers.clicksend.com/docs/messaging/mms)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Voice / Text-to-Speech API

Place automated voice calls that read text aloud via text-to-speech in a chosen language and voice, price the call, list supported languages, and cancel calls via POST /voice/send, /voice/price, GET /voice/lang and /voice/{message_id}/cancel.

- **Human URL:** [https://developers.clicksend.com/docs/messaging/voice-messaging](https://developers.clicksend.com/docs/messaging/voice-messaging)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Voice
- Text to Speech
- TTS

#### Properties

- [Documentation](https://developers.clicksend.com/docs/messaging/voice-messaging)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Transactional Email API

Send transactional email from verified sender addresses, price and view email history, and manage verified from-addresses via POST /email/send, /email/price, GET /email/history and /email/addresses.

- **Human URL:** [https://developers.clicksend.com/docs/messaging/email](https://developers.clicksend.com/docs/messaging/email)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Email
- Transactional
- Messaging

#### Properties

- [Documentation](https://developers.clicksend.com/docs/messaging/email)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Post - Letters API

Print and physically mail letters worldwide from an uploaded PDF, price a letter, validate a delivery address, and view history via POST /post/letters/send, /post/letters/price, /post/letters/detect-address and GET /post/letters/history.

- **Human URL:** [https://developers.clicksend.com/docs/post/letters](https://developers.clicksend.com/docs/post/letters)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Post
- Letters
- Direct Mail

#### Properties

- [Documentation](https://developers.clicksend.com/docs/post/letters)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Post - Postcards API

Print and mail postcards worldwide from an uploaded PDF design, price a postcard, and view postcard history via POST /post/postcards/send, /post/postcards/price and GET /post/postcards/history.

- **Human URL:** [https://developers.clicksend.com/docs/post/postcards](https://developers.clicksend.com/docs/post/postcards)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Post
- Postcards
- Direct Mail

#### Properties

- [Documentation](https://developers.clicksend.com/docs/post/postcards)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Contacts & Lists API

Create and manage contact lists and the contacts within them, import contacts, remove duplicates, transfer and copy contacts between lists, and search across lists via /lists, /lists/{list_id}/contacts, /lists/{list_id}/import and /search/contacts-lists.

- **Human URL:** [https://developers.clicksend.com/docs/contacts](https://developers.clicksend.com/docs/contacts)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Contacts
- Lists
- Address Book

#### Properties

- [Documentation](https://developers.clicksend.com/docs/contacts)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Delivery Receipts & Inbound API

Retrieve delivery receipts and inbound messages for SMS, MMS, voice and email, mark receipts and inbound messages as read, and configure automation rules that forward receipts and inbound messages to your webhook URLs via /sms/receipts, /sms/inbound, /voice/receipts, /mms/receipts and /automations/*.

- **Human URL:** [https://developers.clicksend.com/docs/messaging/sms/receive-sms](https://developers.clicksend.com/docs/messaging/sms/receive-sms)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Delivery Receipts
- Webhooks
- Inbound

#### Properties

- [Documentation](https://developers.clicksend.com/docs/messaging/sms/receive-sms)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClickSend Account & Balance API

Retrieve account details including the current credit balance, view usage by month, manage subaccounts, and recharge account credit via GET /account, /account/usage/{year}/{month}/subaccount, /subaccounts and /recharge/*.

- **Human URL:** [https://developers.clicksend.com/docs/account](https://developers.clicksend.com/docs/account)
- **Base URL:** `https://rest.clicksend.com/v3`

#### Tags

- Account
- Balance
- Billing

#### Properties

- [Documentation](https://developers.clicksend.com/docs/account)
- [OpenAPI](openapi/clicksend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clicksend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clicksend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ClickSend)
- [LinkedIn](https://www.linkedin.com/company/clicksend)
- [Website](https://www.clicksend.com/)
- [Documentation](https://developers.clicksend.com/)
- [Plans](plans/clicksend-plans-pricing.yml)
- [Rate Limits](rate-limits/clicksend-rate-limits.yml)
- [Fin Ops](finops/clicksend-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
