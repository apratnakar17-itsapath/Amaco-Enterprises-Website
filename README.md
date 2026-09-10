# AMACO Enterprises — Website

A static, mobile-first website for AMACO Enterprises (Jabalpur, Madhya Pradesh).

## Structure

```text
AMACO-Website/
│
├── index.html
├── contact.html
├── contact.vcf
├── README.md
│
└── assets/
    ├── style.css
    ├── main.js
    ├── logo_full.png
    ├── logo_mark_tight.png
    └── favicon files...
```

## Deploying

This is a plain static site — no build step and no backend. Upload the whole `AMACO-Website` contents so `index.html` sits at the repository/domain root. Keep the relative paths intact.

## QR code

After the site is live at its permanent HTTPS URL, generate the business-card QR to point to:

`https://your-domain.com/contact.html`

## Notes

The current package uses the supplied AMACO logo assets. The main site includes the hero, eight services, About, Why AMACO, Industries and Contact sections. The contact page provides call, WhatsApp, email, Maps and Save Contact actions.
