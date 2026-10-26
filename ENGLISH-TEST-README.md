# Les Clefs d’Or Chinese Taipei — English Test Build v2

This is a separate test package. It has not been deployed, and it does not modify the live site.

## Local preview
1. Extract the ZIP.
2. Open `ct-les-clefs-dor-site_FINAL/index.html` to test the original Traditional Chinese website and its new language selector.
3. Open `ct-les-clefs-dor-site_FINAL/en/index.html` to preview the English version.
4. Check every English page under `/en/`, the language selector, member directory, hotel links, responsive layout, and mobile menu.

## Important
- Original Traditional Chinese content is retained; only the language selector and language alternates have been added to Chinese pages.
- English pages use the shared original stylesheet and assets. Their main navigation collapses to the original-style menu at a slightly wider breakpoint to avoid crowding the added language selector.
- The Congress and News sections use Cloudflare Pages Functions. Their live data requires deployment to a separate test Cloudflare Pages project; opening files directly from disk will not validate those API-backed sections.
- No GitHub repository, Cloudflare project, DNS setting, or production site has been changed.
