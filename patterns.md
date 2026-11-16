# gtm-url-qs-sanitizer reviewer patterns

Snapshot: `b7f70eddd485cf3c2284a14cc249be32708f1b05`. [Repository](https://github.com/seerinteractive/gtm-url-qs-sanitizer).

These reviewer patterns apply to the pinned snapshot. Accepted items passed independent refutation and deterministic evidence checks at the pinned snapshot. Quotes verify source presence; they do not prove every interpretation or current production behavior.

Coverage: 1 extracted business rules; 1 accepted, 0 uncertain, 0 rejected, 0 pending audit. 0 extracted dependencies; 0 accepted, 0 uncertain, 0 rejected, 0 pending audit.

Scanned branch: `main`. GitHub default branch: `main`.

## Accepted business rules

### sanitize-query-and-hash-parameters

gtm-url-qs-sanitizer's documented GTM variable template must strip URL parameters according to a custom parameter allowlist or blocklist, covering parameters in both the query string and the hash.

**Why:** Reason not stated in the repo.

**Applies to:** The documented URL transformation behavior of the GTM variable template.

**Evidence:**

- [gtm-url-qs-sanitizer/README.md:2](https://github.com/seerinteractive/gtm-url-qs-sanitizer/blob/b7f70eddd485cf3c2284a14cc249be32708f1b05/README.md#L2)

  ```text
  A GTM variable template that accepts a URL as input and returns aURL with query parameters (whether part of querystring or in hash) stripped out based on a custom parameter allowlist or blocklist.
  ```

## Accepted dependencies

No dependency has cleared the acceptance gates for this snapshot.

## Provenance and limits

Raw extraction: `out/gtm-url-qs-sanitizer.json`. Independent audit: `audit/gtm-url-qs-sanitizer.json` in the knowledge report bundle. The original whitespace-normalized `.verified.json` files are not acceptance inputs. This report does not assert a complete semantic audit of every tracked file, deployment verification, or owner approval. Excluded candidate text and audit rationale are kept in the separate review report.
