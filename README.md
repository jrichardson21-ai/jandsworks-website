# jandsworks.com

Website for J&S Works LLC: practical cybersecurity and private, local AI for small businesses.

Plain static HTML and CSS, no build step and no third-party scripts. Deployed with Cloudflare Pages from the `main` branch (build command: none, output directory: `/`).

- `_headers`: security headers (HSTS, strict Content-Security-Policy, and others) applied by Cloudflare Pages
- `.well-known/security.txt`: security contact ([RFC 9116](https://www.rfc-editor.org/rfc/rfc9116))
