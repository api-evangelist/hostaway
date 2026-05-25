# Hostaway (hostaway)
Hostaway is an AI-powered vacation rental management platform that consolidates property management, channel management, direct booking, guest messaging, automation, and revenue optimization for short-term rental operators. The platform connects to Airbnb, Vrbo, Booking.com, Expedia, Google Vacation Rentals, and Marriott Homes & Villas, and exposes a documented OAuth 2.0 public REST API at `https://api.hostaway.com/v1` covering listings, reservations, calendar, messaging, finance, tasks, custom fields, guest payments, and unified webhooks. Pricing is quote-based; a free product demo is available. The Hostaway Marketplace contains 100+ integrated vendors spanning revenue management, operations, smart locks, payments, and accounting.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/hostaway/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Vacation Rentals, Short-Term Rentals, Property Management, Channel Manager, Airbnb, Vrbo, Booking.com, Expedia, SaaS

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Authentication

| Detail | Value |
|---|---|
| Scheme | OAuth 2.0 — Client Credentials grant |
| Token endpoint | `POST https://api.hostaway.com/v1/accessTokens` |
| Token type | Bearer |
| Validity | 24 months |
| Revocation | `DELETE https://api.hostaway.com/v1/accessTokens` |
| Caveat | Wait at least 1 second before using a freshly issued token |

## Rate Limits

| Scope | Limit | Window |
|---|---|---|
| Per source IP | 15 requests | 10 seconds |
| Per account ID | 20 requests | 10 seconds |

Exceeding either limit returns HTTP 429. See [rate-limits/hostaway-rate-limits.yml](rate-limits/hostaway-rate-limits.yml).

## APIs

### Hostaway Listings API
Manage vacation rental listings — properties, amenities, bed types, images, and custom field values. Each Hostaway listing maps to one or more external channels.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

- [Documentation](https://api.hostaway.com/documentation)
- [OpenAPI](openapi/hostaway-listings-api-openapi.yml)
- [JSON Schema — Listing](json-schema/hostaway-listing-schema.json)
- [JSON-LD](json-ld/hostaway-context.jsonld)
- [Naftiko Capability — Listings](capabilities/listings-listings.yaml)

### Hostaway Reservations API
Create, read, and update reservations across all connected channels. Includes coupons, reservation fees, reservation units, and host proxy email handling.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

- [OpenAPI](openapi/hostaway-reservations-api-openapi.yml)
- [JSON Schema — Reservation](json-schema/hostaway-reservation-schema.json)
- [Naftiko Capability — Reservations](capabilities/reservations-reservations.yaml)

### Hostaway Calendar API
Read and update per-listing availability and nightly pricing. Supports per-day retrieval, batch updates, and inline reservation context via `includeResources`.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

- [OpenAPI](openapi/hostaway-calendar-api-openapi.yml)
- [Naftiko Capability — Calendar](capabilities/calendar-calendar.yaml)

### Hostaway Messaging API
Unified guest messaging across Airbnb, Vrbo, Booking.com, Expedia, email, SMS, and WhatsApp. Conversations, conversation messages, and reusable message templates.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Finance API
Finance fields, price calculations, expenses and extras, offline charges, and owner statements.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Tasks API
Create, assign, and complete operational tasks tied to listings and reservations.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Custom Fields API
Define and manage custom fields on listings and reservations.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Guest Payments API
Manage guest payments and auto-payment rules.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Reference Data API
Reference-data endpoints for cancellation policies (Airbnb, Vrbo, Booking.com, Marriott), countries, currencies, languages, and timezones.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

### Hostaway Webhooks API
Manage unified webhooks for the three Hostaway event types — reservation created, reservation updated, and new message received. Failed deliveries retry up to three times before a failure email.

**Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

- [OpenAPI](openapi/hostaway-webhooks-api-openapi.yml)
- [Naftiko Capability — Webhooks](capabilities/webhooks-webhooks.yaml)

## Connected Channels

- Airbnb (2025 Preferred Partner)
- Vrbo (2025 Elite Partner)
- Booking.com (2025 Premier Partner / 2026 Premier Plus Connectivity Partner)
- Expedia
- Google Vacation Rentals
- Marriott Homes & Villas
- HomeAway

## Marketplace Integrations (selected)

- **Revenue management** — Pricelabs, Wheelhouse, Beyond, DPGO
- **Property operations** — Breezeway, Turno, Operto, Doinn
- **Guest screening & safety** — Safely, Autohost, Truvi
- **Smart locks** — RemoteLock, August, Yale, Nuki, Schlage
- **Payments** — Stripe, Braintree, ChargeAutomation, Authorize.net
- **Accounting** — QuickBooks, Ximplifi, Clearing
- **Communication** — Slack, WhatsApp, Zapier
- **Cleaning & maintenance** — Lula Cleaning, Keepers, Tidy, Pacho

See the full list at [https://www.hostaway.com/marketplace/](https://www.hostaway.com/marketplace/).

## Plans and Pricing

Hostaway publishes no self-serve list prices. Pricing is quote-based after a portfolio questionnaire and sales conversation; a free product demo is offered at [https://www.hostaway.com/get-free-demo/](https://www.hostaway.com/get-free-demo/). See [plans/hostaway-plans-pricing.yml](plans/hostaway-plans-pricing.yml) and [finops/hostaway-finops.yml](finops/hostaway-finops.yml).

## Common Properties

- [Portal](https://www.hostaway.com)
- [API Documentation](https://api.hostaway.com/documentation)
- [Dashboard Login](https://dashboard.hostaway.com/login)
- [Webhook Configuration](https://dashboard.hostaway.com/settings/integrations)
- [Pricing](https://www.hostaway.com/pricing/)
- [Free Demo](https://www.hostaway.com/get-free-demo/)
- [Features](https://www.hostaway.com/features/)
- [Marketplace](https://www.hostaway.com/marketplace/)
- [Blog](https://www.hostaway.com/blog/)
- [Partners](https://www.hostaway.com/partners/)
- [GitHub](https://github.com/Hostaway)
- [LinkedIn](https://www.linkedin.com/company/hostaway)

## Maintainers

- **Kin Lane** ([apievangelist.com](https://apievangelist.com)) — info@apievangelist.com
