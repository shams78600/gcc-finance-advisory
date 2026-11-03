# FinAnalytix -- Sales Page Setup & GitHub Pages Deployment

## 1. Project overview

This repository contains the FinAnalytix sales landing page for
financial advisory and Excel-based financial solutions targeting CFOs,
Financial Controllers, Finance Managers, and business owners across
Saudi Arabia and the GCC.

The website must be professional, responsive, mobile-friendly,
fast-loading, and optimized for lead generation.

## 2. Business configuration

Update the following constants in the project's configuration section.
Use these exact values:

  Constant         Value
  ---------------- -----------------------------------------------
  `WA_NUMBER`      `"923034114548"`
  `LI_URL`         `"https://www.linkedin.com/in/shamsfaroooq/"`
  `EMAIL`          `"Shams78600@gmail.com"`
  `FORMSPREE_ID`   `""`

**WhatsApp formatting:** The number is already converted to
international format with digits only. Do not add a plus sign, spaces,
or hyphens.

### Formspree

`FORMSPREE_ID` is intentionally left empty because no Formspree ID has
been provided.

-   Keep the WhatsApp fallback active when `FORMSPREE_ID` is empty.
-   Do not invent a Formspree ID.
-   If a Formspree ID is added later, connect the lead-magnet form to
    that endpoint and test successful submission.
-   Do not show a broken form or falsely claim that a submission was
    received.

## 3. Brand and audience

-   **Brand:** FinAnalytix
-   **Target market:** Saudi Arabia and the GCC
-   **Currency:** SAR (Saudi Riyal)
-   **Language:** English
-   **Tone:** Professional, credible, analytical, and commercially
    focused
-   **Audience:** CFOs, Finance Directors, Financial Controllers, Senior
    Finance Managers, and business owners

The design should communicate senior financial expertise and a premium
financial advisory service---not a generic Excel freelancer profile or
software application.

## 4. Website requirements

Ensure the website:

1.  Displays correctly on desktop, tablet, and mobile.
2.  Uses the WhatsApp number above for all WhatsApp contact links.
3.  Links to the LinkedIn profile above.
4.  Uses the email address above for the "Email instead" button.
5.  Uses the WhatsApp fallback for lead-magnet enquiries while
    `FORMSPREE_ID` is empty.
6.  Presents services, deliverables, pricing, and calls to action
    clearly.
7.  Uses professional typography, spacing, and consistent branding.
8.  Includes an appropriate SEO page title and meta description.
9.  Has no broken links, missing images, or JavaScript errors.
10. Does not expose confidential customer information or sample
    financial data.

## 5. GitHub Pages deployment

Configure GitHub Pages to publish the website:

-   Publish from the production branch, normally `main`.
-   Use the repository root (`/`) as the publishing folder unless the
    existing project structure requires `/docs`.
-   Ensure the entry point is named `index.html`.
-   Include all required CSS, JavaScript, images, fonts, and other
    assets.
-   Use paths that work after deployment under the GitHub Pages URL. Do
    not assume the site is hosted at the domain root if it is a project
    repository.
-   Ensure the website works as a static site without requiring a
    backend server.

Do not configure a custom domain unless one is supplied separately.

## 6. Quality assurance before publishing

-   [ ] `WA_NUMBER` is set to `923034114548`.
-   [ ] WhatsApp links open the correct number.
-   [ ] LinkedIn link opens the specified profile.
-   [ ] Email button opens a message to `Shams78600@gmail.com`.
-   [ ] Lead-magnet form uses the WhatsApp fallback while Formspree ID
    is blank.
-   [ ] Mobile layout is responsive.
-   [ ] All images and assets load correctly.
-   [ ] No broken navigation or JavaScript console errors.
-   [ ] Pricing is displayed in SAR where applicable.
-   [ ] All calls to action work.
-   [ ] No placeholder text or dummy contact details remain.

## 7. Final instructions

Do not unnecessarily redesign, rewrite, or remove existing content.
Preserve the existing sales copy, service positioning, pricing, visual
identity, and functionality unless a correction is required.

Do not invent credentials, testimonials, client names, case-study
results, or performance claims.

After completing configuration and deployment:

1.  Confirm whether GitHub Pages deployment succeeded.
2.  Provide the live website URL.
3.  Report any configuration values still requiring the owner's input.
4.  Identify any features that cannot function without an external
    service or API.

**Final objective:** Publish a professional, trustworthy FinAnalytix
sales page that can be shared directly in the Featured section of
LinkedIn and used to convert prospective clients across Saudi Arabia and
the GCC.
