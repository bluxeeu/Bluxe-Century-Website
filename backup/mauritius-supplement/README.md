# Mauritius supplement backup

The live Site includes the complete 55-page PDF at `dist/docs/bluxe-century-mauritius-supplement.pdf`. GitHub stores the same optimized PDF as numbered binary parts under `backup/mauritius-supplement/` to keep each repository API upload small. The original uploaded PDF remains in the user's file collection.

To reconstruct the web PDF from a checkout:

```sh
cat backup/mauritius-supplement/part-*.bin > dist/docs/bluxe-century-mauritius-supplement.pdf
sha256sum dist/docs/bluxe-century-mauritius-supplement.pdf
```

Expected SHA-256: `733dd1f4190ce80eae20e7488283e4bb69682274208bfa5d9c8f51cd16094afd`.

The optimized derivative contains 55 pages, searchable text, and all 14 link annotations from the uploaded source. Site deployment source commit: `1cf8a551e619f77531b16fec7538c475dede91db`.
