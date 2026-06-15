# Hostaway (hostaway)

Hostaway is an AI-powered vacation rental management platform that consolidates property management, channel management, direct booking, guest messaging, automation, and revenue optimization for short-term rental operators. The platform connects to Airbnb, Vrbo, Booking.com, Expedia, Google Vacation Rentals, and Marriott Homes & Villas, and exposes a documented OAuth 2.0 public REST API at https://api.hostaway.com/v1 covering listings, reservations, calendar, messaging, finance, tasks, custom fields, guest payments, and unified webhooks. Pricing is quote-based; a free product demo is available. The Hostaway Marketplace contains 100+ integrated vendors spanning revenue management, operations, smart locks, payments, and accounting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hostaway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hostaway/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Vacation Rentals
- Short-Term Rentals
- Property Management
- Channel Manager
- Airbnb
- Vrbo
- Booking.com
- Expedia
- SaaS

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Hostaway Listings API

Manage vacation rental listings — properties, amenities, bed types, images, and custom field values. Each Hostaway listing maps to one or more external channels (Airbnb, Vrbo, Booking.com, Expedia, Google Vacation Rentals, Marriott Homes & Villas) and is the primary inventory object in the platform.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Listings
- Properties

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [OpenAPI](openapi/hostaway-listings-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hostaway-listing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/hostaway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Hostaway Reservations API

Create, read, and update reservations across all connected channels. Includes coupons, reservation fees, reservation units, host proxy email handling, and channel-of-origin context (channelId/channelName) for every booking.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Reservations
- Bookings

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [OpenAPI](openapi/hostaway-reservations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hostaway-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/hostaway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Hostaway Calendar API

Read and update the per-listing availability and nightly pricing calendar. Supports per-day retrieval, batch updates across date ranges, and inline reservation context via the includeResources query parameter.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Calendar
- Availability
- Pricing

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [OpenAPI](openapi/hostaway-calendar-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Messaging API

Unified guest messaging across Airbnb, Vrbo, Booking.com, Expedia, email, SMS, and WhatsApp. Resources include conversations, conversation messages, and reusable message templates.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Messaging
- Conversations

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Finance API

Financial operations for vacation rental managers — finance fields, price calculations, expenses and extras, offline charges, and owner statements.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Finance
- Owner Statements

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Tasks API

Create, assign, and complete operational tasks (cleaning, maintenance, inspection) tied to listings and reservations.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Tasks
- Operations

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Custom Fields API

Define and manage custom fields on listings and reservations, plus retrieve and set custom field values on individual records.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Custom Fields
- Configuration

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Guest Payments API

Manage guest payments and auto-payment rules for reservations.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Payments
- Auto-Payment

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Reference Data API

Reference-data endpoints for cancellation policies (Airbnb, Vrbo, Booking.com, Marriott), countries, currencies, languages, and timezones.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Reference Data

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [Postman Collection](collections/hostaway-calendar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-calendar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-listings-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-listings-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-reservations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-reservations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hostaway Webhooks API

Manage unified webhooks for the three Hostaway event types — reservation created, reservation updated, and new message received. Failed deliveries retry up to three times before a failure email is sent to the configured alert recipient.

- **Human URL:** [https://api.hostaway.com/documentation](https://api.hostaway.com/documentation)

#### Tags

- Vacation Rentals
- Webhooks
- Events

#### Properties

- [Documentation](https://api.hostaway.com/documentation)
- [OpenAPI](openapi/hostaway-webhooks-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hostaway-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hostaway-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.hostaway.com)
- [Documentation](https://api.hostaway.com/documentation)
- [Sign Up](https://dashboard.hostaway.com/login)
- [Documentation](https://dashboard.hostaway.com/settings/integrations)
- [Pricing](https://www.hostaway.com/pricing/)
- [Getting Started](https://www.hostaway.com/get-free-demo/)
- [Documentation](https://www.hostaway.com/features/)
- [Blog](https://www.hostaway.com/blog/)
- [Marketplace](https://www.hostaway.com/marketplace/)
- [Partners](https://www.hostaway.com/partners/)
- [About](https://www.hostaway.com/about-us/)
- [Support](https://www.hostaway.com/contact/)
- [Privacy Policy](https://www.hostaway.com/privacy-policy/)
- [Terms of Service](https://www.hostaway.com/terms-and-conditions/)
- [LinkedIn](https://www.linkedin.com/company/hostaway)
- [Facebook](https://www.facebook.com/hostawaycom)
- [Twitter](https://twitter.com/hostawaycom)
- [Instagram](https://www.instagram.com/hostawaycom/)
- [YouTube](https://www.youtube.com/@hostaway)
- [GitHub Organization](https://github.com/Hostaway)
- [Plans](https://plans/hostaway-plans-pricing.yml)
- [Rate Limits](https://rate-limits/hostaway-rate-limits.yml)
- [Fin Ops](https://finops/hostaway-finops.yml)
- [Authentication](undefined)
- [Channels](undefined)
- [Features](undefined)
- [Integrations](undefined)
- [Recognition](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
