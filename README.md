# ABBY-0419 Public Developer Site

Static GitHub Pages site for ByeShrimp developer information and privacy policies. The app source remains in the separate `KAI-0419/ByeShrimp` repository.

## Pages

- `/` — developer and policy links
- `/privacy/ko.html` — Korean privacy policy
- `/privacy/en.html` — English privacy policy
- `/privacy/ja.html` — Japanese privacy policy
- `/privacy/zh-hans.html` — Simplified Chinese privacy policy

The site has no build step, JavaScript, analytics, or external font dependency. The operator is **MUISIK** and the contact address is **visionary.0419@gmail.com**. The policy pages were revised on October 16, 2026. They cover local motion processing, saved postures and shared display references, call status, StoreKit, device backups, GitHub Pages, and Gmail inquiries.

The app links to the policy for its currently displayed language from the bottom of Settings. Policy edits here must be deployed before the updated text is available at the public URLs. Before release, check the policy against the final app binary, operating practices, and applicable law.

## Publish with GitHub Pages

1. Create a public repository named `ABBY-0419.github.io` under the `ABBY-0419` account.
2. Push this folder's `main` branch to that repository.
3. In **Settings → Pages**, select **GitHub Actions** as the deployment source.
4. After the workflow completes, verify the root page and all four policy URLs.
5. Use `https://abby-0419.github.io/privacy/ko.html` and `https://abby-0419.github.io/privacy/en.html` in the relevant store metadata.

The GitHub CLI was authenticated as `KAI-0419` when this draft was prepared. Do not push it until the CLI is authenticated as `ABBY-0419`.
