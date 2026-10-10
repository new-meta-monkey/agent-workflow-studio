# Fieldwork AI — Agent Workflow Studio

A responsive, single-page React website for an open-source AI workflow automation and consulting startup serving small and medium businesses in India. **Fieldwork AI is a temporary brand name**; replace it before launch.

## Included

- Responsive landing page with industry-specific workflow examples
- Self-hosted and managed deployment positioning
- Indicative INR pricing cards
- Consulting and discovery-call sections
- FAQ, responsive navigation, and contact enquiry form
- Basic accessibility: semantic landmarks, input labels, keyboard-operable buttons, reduced-motion support

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To make a production build:

```bash
npm run build
npm run preview
```

## Before production

1. **Brand:** Replace `Fieldwork AI` / `fieldwork.ai` and update page title, description, logo text and footer.
2. **Contact:** Replace `hello@yourcompany.in` in `src/main.jsx` with a real monitored inbox. The current form opens a prefilled `mailto:` draft; it does not store or transmit leads to a backend.
3. **Pricing:** The ₹4,999/month managed plan is illustrative launch pricing, not a costed or guaranteed offer. Validate hosting, support, model usage, taxes, limits, uptime and overage pricing before publishing.
4. **Open-source claims:** Select and document actual software components and their licences. This page intentionally does not claim a proprietary platform is already open source.
5. **Privacy and security:** Add a privacy notice, terms, consent as appropriate, data retention details, and secure backend processing before collecting personal data.
6. **Deployment:** Add authentication, tenant isolation, secret management, monitoring, backups, incident response and approval gates where relevant. Healthcare and other sensitive workflows need domain-specific compliance review.
7. **SEO and analytics:** Add a canonical URL, social preview image, sitemap, robots policy and privacy-respecting analytics if needed.

## Technology

- React + Vite
- Lucide React icons
- Plain CSS; no component framework

## Project structure

```text
agent-workflow-studio/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```
