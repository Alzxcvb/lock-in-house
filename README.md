# Lock In House

Landing page for a one month co living and co working house in Da Nang, Vietnam, September 2026.

Live: https://lock-in-house.vercel.app

## What this is

A single self contained `index.html`. No build step, no dependencies, no framework, no external requests.

## Changing things

Everything you are likely to change sits in one place.

- **Price and dates**: search `index.html` for `$750` and `1 Sep`.
- **Where reservations go**: the `TO` variable at the top of the script block. Set `ENDPOINT` to a POST url and submissions are sent there as JSON instead of opening an email.
- **Photos**: replace the `<div class="ph">` inside each `.shot` with an `<img>`. The grid and object fit are already handled.

## Status

The villa is not booked yet. The page says so plainly and takes no money, by design. Wifi speed is deliberately not stated anywhere because it has not been measured in the house.
