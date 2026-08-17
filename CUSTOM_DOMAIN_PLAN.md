# Gardecor AR clean public URL

Target browser-visible URL:

`https://ar.gardecor.md/...`

Current GitHub Pages host remains the technical origin until DNS/custom-domain activation is complete.

## Required activation sequence
1. In GitHub Pages for this repository, set custom domain to `ar.gardecor.md`.
2. In Gardecor DNS, create `CNAME ar -> casiandrey-lang.github.io` (target excludes repository path).
3. Wait for DNS/HTTPS validation.
4. Verify `https://ar.gardecor.md/webxr-control-v12.html` and the parameterized AR endpoint on a phone.
5. Only after verification, update EVA configurator canonical AR base URL to `https://ar.gardecor.md`.

Do not switch the live configurator before step 4, because doing so would break AR while DNS is unresolved.
