# Western Union (western-union)

The Western Union Company is a global leader in cross-border, cross-currency money movement, providing money transfer, money order, and other financial services to consumers and businesses worldwide. Western Union's Partnership APIs enable financial institutions, fintech companies, and enterprise customers to integrate WU's global payment network for money transfers, batch payments, FX quotes, and account management across 200+ countries and territories in 130+ currencies.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Fortune 500
- Money Transfer
- Payments
- International
- Batch Payments
- Foreign Exchange
- Financial Services
- Open Banking

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Western Union Mass Payments API

Enables financial institutions and enterprise customers to send up to 10,000 international payments in a single batch across 130+ currencies in 200+ countries. Authentication uses mTLS client certificates.

- **Human URL:** [https://developer.westernunion.com/api-money-transfer.html](https://developer.westernunion.com/api-money-transfer.html)
- **Base URL:** https://api.westernunion.com

#### Properties

- [Documentation](https://developer.westernunion.com/api-money-transfer.html)
- [Portal](https://developer.westernunion.com/getting-started.html)
- [OpenAPI](openapi/western-union-mass-payments-openapi.yml)

### Western Union Open Banking API

PSD2-compliant Open Banking API for Account Information Services (AIS) and Payment Initiation Services (PIS) for European financial institutions.

- **Human URL:** [https://wu-priora.saltedge.com/](https://wu-priora.saltedge.com/)

## Common Properties

- [Website](https://www.westernunion.com)
- [Business Solutions](https://business.westernunion.com)
- [Developer Portal](https://developer.westernunion.com)
- [Getting Started](https://developer.westernunion.com/getting-started.html)
- [Privacy Policy](https://www.westernunion.com/us/en/privacy-statement.html)
- [LinkedIn](https://www.linkedin.com/company/western-union)

## Artifacts

### OpenAPI Specifications

- [Mass Payments API](openapi/western-union-mass-payments-openapi.yml)

### Spectral Rules

- [Western Union Rules](rules/western-union-rules.yml)

### Naftiko Capabilities

- [International Payments](capabilities/international-payments.yaml) — Batch payment, FX quotes, balance checks
- [Shared: Mass Payments](capabilities/shared/mass-payments.yaml)

### JSON Schema

- [Payment Schema](json-schema/western-union-payment-schema.json)
- [Batch Schema](json-schema/western-union-batch-schema.json)

### JSON Structure

- [Payment Structure](json-structure/western-union-payment-structure.json)

### JSON-LD Context

- [Western Union Context](json-ld/western-union-context.jsonld)

### Examples

- [Create Batch](examples/western-union-create-batch-example.json)
- [Add Payment to Batch](examples/western-union-add-payment-example.json)
- [Create FX Quote](examples/western-union-create-quote-example.json)

### Vocabulary

- [Western Union Vocabulary](vocabulary/western-union-vocabulary.yml)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
