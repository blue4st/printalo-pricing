# Printalo Pricing Calculator

A lightweight static pricing calculator for Printalo album products.

## Structure

- `index.html` — web app UI and calculator logic
- `pricing-data.json` — pricing/configuration data
- `.nojekyll` — ensures GitHub Pages serves the repository as a plain static site

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub Pages will publish `index.html`.

## Updating prices

Edit only `pricing-data.json`. The calculator loads this file at runtime, so pricing changes do not require editing the HTML.

The current configuration includes Hard cover — standard, Hard cover — large, and Magazine products, with their sizes, page limits, printing prices, binding, covers, and finishes.
