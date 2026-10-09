# YOA Installation — yoa installation service llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `yoainstallationservicellc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/yoainstallationservicellc.mjs`).
> To change the content, edit that file and run `node build.mjs yoainstallationservicellc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@yoainstallationservicellc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
YOA Installation Service LLC, a Florida limited liability company (document number L23000351047), installs home furnishings for homeowners, renters, interior designers and property managers: blinds, shades and shutters measured and fitted to the opening, drapery rods and track hardware, wall decor, mirrors and shelving anchored to suit the wall behind them, and flat-pack furniture assembly, television mounting and closet systems. Work is quoted in writing after a free measure, with hardware, access and removal of existing fittings itemised separately. The company does not perform electrical, plumbing or structural work, which is referred to appropriately licensed contractors. Site: yoainstallationservicellc.shop
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
