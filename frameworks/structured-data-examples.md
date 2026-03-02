# Structured Data Examples (JSON-LD)

This file contains safe, engineering-friendly schema patterns.

---

## Article Schema (Template)

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "TITLE",
  "description": "SHORT DESCRIPTION",
  "author": { "@type": "Person", "name": "Deepak Kumar" },
  "publisher": {
    "@type": "Organization",
    "name": "Quokka Labs",
    "logo": {
      "@type": "ImageObject",
      "url": "https://quokkalabs.com/path/to/logo.png"
    }
  },
  "datePublished": "2026-03-02",
  "dateModified": "2026-03-02"
}
