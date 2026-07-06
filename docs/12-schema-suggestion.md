# 12. Schema Suggestion

Schema helps search engines understand page type, author, organization, and structured sections.

## Schema Mapping

| Page Type | Suggested Schema |
|---|---|
| Blog post | Article / BlogPosting |
| FAQ section | FAQPage |
| Author page | Person |
| Service page | Service |
| Business website | Organization / LocalBusiness |
| Navigation path | BreadcrumbList |
| Product/category content | CollectionPage / ItemList where appropriate |

## Author and Reviewer Signals

For content that needs author or reviewer context, consider:

- Person schema
- Author profile URL
- sameAs links
- worksFor organization
- knowsAbout topics
- reviewedBy where appropriate

## Example Person Fields

```json
{
  "@type": "Person",
  "name": "Đoàn Trình Dục",
  "url": "https://seobeginer.net/author/doan-trinh-duc/",
  "jobTitle": "Technical SEO & WordPress Optimization Specialist",
  "knowsAbout": [
    "Technical SEO",
    "WordPress SEO",
    "Onpage SEO",
    "Schema Markup",
    "EEAT"
  ]
}
```

## Schema Notes

- Do not add schema that does not match visible content.
- Avoid fake reviews or fake ratings.
- Keep author and organization data consistent.
- Validate schema before publishing.
