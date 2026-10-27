# Her Himmat — her himmat ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herhimmatltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herhimmatltd.mjs`).
> To change the content, edit that file and run `node build.mjs herhimmatltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herhimmatltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per item / $Free advice / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Himmat Ltd is a clothing retailer based in Hounslow, west London, trading since 2021. What we do differently is dull and genuinely useful. Fibre composition labelling is a legal requirement in the UK and it has to be accurate, yet most small retailers simply reprint whatever a supplier put on the label, which makes that supplier's error their own offence. We check instead. We also publish real garment measurements rather than relying on a size label, because UK sizing is not standardised and a size 12 from two brands can differ by inches. We will not call anything sustainable, ethical or organic unless we can evidence it, and we explain the hygiene limits on returns before you order rather than when you try to send something back. Site: herhimmatltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
