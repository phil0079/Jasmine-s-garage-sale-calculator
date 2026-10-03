# Garage Sale Calculator

A phone-friendly, dependency-free calculator for garage sale checkout.

- Quick prices: 25¢, 50¢, $1, $2, $3, $4, $5, $7.50, $10, $20, $25.
- Running total and count per price.
- Remove any history entry or undo the latest item.
- New sale reset with confirmation.
- Venmo QR dialog labeled Jasmine with the current total. The embedded QR encodes the exact Venmo link supplied by the owner.
- The current sale persists in browser local storage on that device; nothing syncs between devices. No payments are processed or automatically verified.

## Run locally

Open `public/index.html`, or serve `public` with a static web server.

## Publish on Netlify through GitHub

Push this directory to a new GitHub repository. In Netlify, choose **Add new project → Import an existing project**, select GitHub and this repository, and deploy the `main` branch. No build command is required. The included `netlify.toml` sets the publish directory to `public`.

Future pushes to the connected production branch will deploy automatically. Netlify account authorization and connecting the repository are still required for the first deployment.
