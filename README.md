# Google Custom Search API

The Google Custom Search JSON API allows programmatic searches over a website or collection of websites. It returns metadata about the search performed, metadata about the search engine used, and the search results.

## APIs

- **Google Custom Search JSON API** - Programmatic web and image searches using Programmable Search Engines.

## Base URL

```
https://customsearch.googleapis.com
```

## Key Endpoints

- **Custom Search** - `GET /customsearch/v1` - Perform a search and retrieve results
- **Site Restricted Search** - `GET /customsearch/v1/siterestrict` - Search restricted to specific sites

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/SearchResult.json) - JSON Schema (draft 2020-12) for SearchResult
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/custom-search/v1/overview)
- [Pricing](https://developers.google.com/custom-search/v1/overview#pricing)
- [API Reference](https://developers.google.com/custom-search/v1/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
