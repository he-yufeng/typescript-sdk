---
'@modelcontextprotocol/client': patch
---

Redirect for explicit step-up authorization scopes even when a refresh token is available. A refresh grant can only reuse existing consent, so clients now start the authorization flow when a 403 insufficient-scope challenge asks for a new scope.
