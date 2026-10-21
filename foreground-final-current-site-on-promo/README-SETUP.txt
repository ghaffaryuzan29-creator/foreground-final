FOREGROUND — Deploy existing homepage at /promo

Files:
- index.html: original current homepage, unchanged
- promo/index.html: exact byte-for-byte copy of original homepage
- vercel.json: allow /promo (without trailing slash) to load promo/index.html

HOW TO DEPLOY
1. Extract ZIP.
2. Upload all three items to ROOT of GitHub repo ghaffaryuzan29-creator/foreground-final (overwrite root index.html only if requested; its content is identical to source).
3. Commit changes to the production branch and wait for Vercel deployment READY.
4. Test https://www.foreground.id/promo and https://www.foreground.id/.

No DNS changes needed. Keep index.html as-is, and later replace it with the new homepage while leaving promo/index.html untouched.
Note: This is a self-contained JS-bundled page. Test interactive behavior after deploy.
