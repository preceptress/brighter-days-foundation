# Brighter Days Foundation — nonprofit website starter

A polished, handoff-ready static website for a pediatric cancer community nonprofit.

https://preceptress.github.io/brighter-days-foundation/

## What is included

- Responsive homepage
- Founder/story section
- Programs/mission section
- Community section
- Resource links
- Donation call-to-action
- Newsletter section
- Mobile navigation
- Subtle scroll animation
- Accessible HTML structure
- No framework, database, or build step required

## Launch in 5 minutes

1. Unzip the folder.
2. Double-click `index.html` to preview it locally.
3. Replace the placeholder nonprofit name, email, story, and resource links.
4. Replace photo placeholder blocks with real `<img>` tags.
5. Upload the folder to Netlify, GitHub Pages, Cloudflare Pages, or any normal web host.
6. Point the nonprofit's custom domain to the host.

## Replace the name

Search all files for:

`Brighter Days Foundation`

and replace it with the nonprofit's real name.

## Replace the email

Search for:

`hello@example.org`

and replace it with the nonprofit's email address.

## Add the logo

Inside the `.brand` link in `index.html`, replace:

```html
<span class="brand-mark" aria-hidden="true">✦</span>
```

with something like:

```html
<img src="images/logo.svg" alt="Nonprofit name" class="logo">
```

Then add the image to an `images/` folder.

## Add real photos

The site intentionally uses visible photo placeholders so nobody accidentally launches it with stock imagery.

Replace a block like:

```html
<div class="photo-placeholder">
  <span>ADD HERO PHOTO</span>
</div>
```

with:

```html
<img src="images/founder.jpg" alt="Founder smiling outdoors">
```

For the large hero image, put the `<img>` inside the existing `.photo-card.main-photo` wrapper.

## Donation button

The current Donate Securely button uses `href="#"`.

Replace it with a real donation page from Givebutter, Donorbox, PayPal, Stripe, or the nonprofit's preferred processor.

## Newsletter

The newsletter form is visual only right now. Connect it to Mailchimp, Buttondown, ConvertKit, or another email provider before launch.

## Recommended content before launch

- Exact nonprofit name
- Founder-approved story text
- Mission statement
- Programs offered today
- City/state served
- Contact email
- Donation provider
- 501(c)(3) status and EIN if appropriate to publish
- Privacy policy
- Photo permissions, especially for minors
- Accurate medical/resource disclaimers
- Social media links

## Important child-safety/privacy note

Because this nonprofit serves children, avoid publishing a child's diagnosis, treatment history, location, school, hospital, or photographs unless the organization has clear consent to do so. Do not collect sensitive medical information through a basic website form.

## Files

- `index.html` — page structure and text
- `styles.css` — all visual design
- `script.js` — menu, donation selection, scroll animations
- `README.md` — handoff instructions

No npm. No framework. No build process. It is intentionally boring underneath and beautiful on top.

## Support This Project

This software is free and open for everyone.

Organizations that require professional deployment, hosting, training, or custom development are welcome to contact us. Revenue from these services helps us continue developing free software for nonprofits, educators, researchers, and communities worldwide.

📧 **info@preceptress.design**
