# ResourceCite

A free, source-based public resource library with verified organizations across legal aid, housing, medical access, victim support, mental health, child safety, and whistleblower protection.

## Live Site

This project is hosted with GitHub Pages.

## What This Site Includes

- Home page
- Start Here page
- Resources directory
- Support page
- One-time donation link
- Monthly donation links

## Donation Setup

This site uses Stripe Payment Links.

### One-Time Donation
- Custom amount
- Stripe hosted checkout

### Monthly Donations
- $15/month
- $45/month
- $80/month

## Stripe Links Currently Used

- `ONE_TIME_DONATION_LINK`
- `MONTHLY_15_LINK`
- `MONTHLY_45_LINK`
- `MONTHLY_80_LINK`

## Main File

- `index.html` — main site file

## Current Donation Logic

The donation logic is inside the `<script>` block at the bottom of `index.html`.

Current monthly display amounts:

```js
const AMT = {one:[15,45,120], month:[15,45,80]};
