# CSI & Criminal Trial 2025 — NIC Lookup Website

Public NIC lookup for the Law Students' Association of Sri Lanka (External Affairs Dept).

## How to use
1. Replace the `REACT_APP_LOOKUP_URL` in `index.html` with your n8n webhook URL.
2. Commit to GitHub and enable **GitHub Pages** in repository settings.
3. Ensure your n8n webhook allows CORS from your GitHub Pages domain.

## Example API Response
```json
{
  "found": true,
  "nic": "123456789V",
  "name": "A. Silva",
  "reference": "REF001"
}
```

Hosted free on GitHub Pages.
