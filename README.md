# ریشه | Interactive growth plan

Persian RTL cinematic presentation and scenario simulator. Static HTML/CSS/JS, no build dependencies or backend.

## Cloudflare Pages
Connect this repository, production branch `main`, framework `None`, build command blank, output directory `/` (repository root). No secrets needed. Cloudflare deployment has not been performed by this commit.

Local preview: `python3 -m http.server 8080` from repository root.

Features: three channel scenario playbooks, editable economic assumptions, local browser persistence, shareable scenario URL, JSON export, monthly roadmap, presentation controls (left/right arrows, Escape), print styles, responsive layout and reduced-motion support.

Facts and assumptions are explicitly distinguished. Acquisition outcomes are expected values, not forecasts. Repeat assumes at most one extra order per returning buyer. B2B invoices never count toward the B2C target. Contribution is after variable fulfillment/shipping/incentives and before campaign costs; operating fixed costs excluded. No orders/messages/payments are sent by this site.

Font uses Google Fonts with Tahoma fallback. Core page and interactions have no third-party JS dependency. Shared URL contains only financial assumptions, not customer information.
