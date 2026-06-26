# Security Notes

This is a static frontend website. Practical security steps included:

- No API keys, tokens or secrets are stored in the project.
- No external JavaScript dependencies are loaded.
- A Content Security Policy meta tag is included on every page.
- Contact form inputs are validated and sanitized before preparing a mailto enquiry.
- External links use `rel="noopener noreferrer"` where they open new tabs.
- Documents are served as static files from `assets/docs/`.
- No unsafe inline scripts are used.

For hosts that support headers, copy the rules from `_headers` into the hosting configuration. GitHub Pages does not apply `_headers`, but Netlify and Cloudflare Pages can.
