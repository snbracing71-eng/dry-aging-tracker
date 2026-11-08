# Project Rules & Guidelines (AgerPro PWA)

These strict rules must be followed on every single turn:

1. **Always Push to GitHub Automatically**: Whenever asked for any change or update, edit the file, commit it, and run `git push origin main` automatically without waiting for the user to ask to push.
2. **Never Remove Existing Features**: `index.html` is our single-file AgerPro PWA. Only make the exact surgical edit requested—never simplify, truncate, or delete any existing features, styles, cuts, modals, photos, or `localStorage` keys (`dryAgeItemsV6`, `dryAgeItemsV5`, etc.).
3. **Cache-Busting & PWA Integrity**: Keep `manifest.json`, `sw.js`, and `icon.png` intact, and always verify `index.html` ends cleanly with `<!-- END_OF_FILE_OK --></html>` before committing.
4. **Confirm Live Link**: After pushing to GitHub, tell the user in one short sentence what was changed and remind them to wait 45 seconds before reloading AgerPro.
