# rethinkable-app.github.io

Static files for the Rethinkable iOS app. Nothing else belongs here.

- `.well-known/apple-app-site-association`: tells iOS that links under `/plaid/` open the app (universal links).
- `plaid/oauth.html`: where a bank sends you back after you sign in with it through Plaid. The app opens instead;
  this page only shows if it can't. No scripts, nothing collected.
- `.nojekyll`: so GitHub Pages serves the `.well-known` folder.
