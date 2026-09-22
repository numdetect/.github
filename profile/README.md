## NumDetect

**Asynchronous bulk phone-number enrichment.**

Upload a phone-number list, pick one product and one country, and download a structured result file when the task finishes. NumDetect is a bulk workflow — there is no real-time single-number endpoint.

[**Website**](https://numdetect.com) · [**API documentation**](https://numdetect.com/api-docs) · [**Pricing**](https://numdetect.com/pricing) · [**Get an API key**](https://numdetect.com/register)

### Official API example repositories

| Repository | Product code | Contents |
|---|---|---|
| **[Bulk phone-number tasks](https://github.com/numdetect/bulk-phone-number-api)** | `5 products` | OpenAPI contract, `product.json`, `llms.txt`, examples in 7 languages |
| [numdetect-resources](https://github.com/numdetect/numdetect-resources) | — | Technical notes, guides and announcements |

Every example repository carries a machine-readable `product.json`, an `llms.txt` summary for AI clients, an OpenAPI 3.0 contract, and runnable examples in Python, Node.js, Go, Java, C#, PHP and Shell. All request paths, response fields and limits are taken from the live product pages and the published API documentation.

### One key, one balance

Every product on NumDetect uses the same API key, the same `X-API-Key` header and the same `code` / `msg` / `data` envelope, and draws from the same account balance.

### Responsible use

Results are **point-in-time signals**: they describe what a provider reported at the moment of the check. They are not identity verification, not proof of ownership, and not permission to contact anyone. Use the API only for identifiers you are authorized to process, and comply with applicable privacy laws and platform terms. Third-party trademarks belong to their respective owners; no affiliation or endorsement is implied.
