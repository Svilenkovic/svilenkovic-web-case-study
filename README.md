# Svilenković Web

A commerce site about product structure, catalogues, quote flows and the difference between B2C and B2B buying.

**[svilenkovicweb.com](https://svilenkovicweb.com/)** · [Jupiter Planet case study](https://svilenkovicweb.com/en/case-studies/jupiter-planet-configurator/) · [Srpski](README.sr.md)

> [!NOTE]
> This is an independent project by D. Svilenković. The production source stays in a private repository; this public repository documents the work.

<table>
  <tr><td><b>Type</b></td><td>Web shops and B2B catalogues</td></tr>
  <tr><td><b>Languages</b></td><td>Serbian and English</td></tr>
  <tr><td><b>Public routes</b></td><td>18 canonical pages</td></tr>
  <tr><td><b>Role</b></td><td>Research, design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Purpose

A useful shop begins with product data and the way customers buy. The project separates direct checkout, quote requests and B2B catalogues, then shows how one product moves through those paths.

## Design direction

A chromatic sales pavilion turns a physical object into a product card, selection and quote. White space, coral and aqua keep the motion bright without making the catalogue hard to scan.

## What I built

- Separate explanations for checkout, enquiry and B2B catalogue models
- Product data, variants and stock treated as design inputs
- A scroll scene that follows one item through the buying path
- Responsive layouts verified down to narrow phone widths
- No fictional revenue, conversion or customer figures

## Release checks

Every canonical route was checked at 390, 768, 1440 and 1920 px. The release was also tested without JavaScript and with reduced motion. Live checks covered HTTPS, redirects, response headers, structured data, sitemap files, protected paths and invalid contact requests without sending test mail.

These are engineering checks, not claims about search ranking or field performance.

---

<sub>Designed and built by [D. Svilenković](https://svilenkovic.com).</sub>
