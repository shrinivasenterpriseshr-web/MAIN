# TRIBES GitHub + Firebase Starter

## Local preview

Open `index.html` in a browser, or serve the project with any static file server. This repository does not include a payment backend, so online checkout and merchant donations are unavailable.

Publish both `firestore.rules` and `storage.rules` to the `tribes-c55f4` Firebase project before adding products from the admin dashboard. Storage accepts image files smaller than 5 MB; product writes are limited to the required catalog fields.

## Free GitHub Pages hosting

1. Create or open a GitHub repository and upload this project.
2. In GitHub, open **Settings → Pages** and choose **GitHub Actions** as the source.
3. Push to `main`; `.github/workflows/static.yml` deploys the static storefront automatically.
4. Your free URL will be `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Firebase setup

1. Create Firebase project, Firestore and Storage.
2. Put Firebase Web App configuration in js/firebase-config.js.
3. Configure Authentication and Firebase Security Rules before production.
4. Upload this folder to GitHub and enable GitHub Pages.
5. Connect your owned www.tribes.info domain in GitHub Pages.
Fields: Product Name, UOM, Quantity, AVLB Stk, Price, Image URL.
