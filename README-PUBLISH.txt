# ORBIT Privacy Policy — publication package

This package contains:
- `index.html`: one public, responsive privacy-policy page with English, Persian, Spanish, French and Arabic language choices.
- `delete-account.html`: a separate five-language external account/data deletion request page.
- `privacy-policy-en.md`, `privacy-policy-fa.md`, `privacy-policy-es.md`, `privacy-policy-fr.md`, `privacy-policy-ar.md`: separate text copies for review and future maintenance.

## Recommended hosting: GitHub Pages

1. Create a public GitHub repository named `orbit-privacy-policy`.
2. Upload `index.html` to the repository root (the Markdown files may also be uploaded for record keeping).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish and use the `Visit site` link. The URL will normally be:
   `https://YOUR-GITHUB-USERNAME.github.io/orbit-privacy-policy/`
7. Open the page in a private/incognito browser and verify that all five languages load and that no sign-in is required.
8. Put the verified `index.html` URL in Google Play Console and in the app's `LINK_PRIVACY` constant. Put the verified `delete-account.html` URL in the Play Console account-deletion URL field, after the deletion process is operational.

GitHub Pages is a public static hosting service. The URL depends on the GitHub account/repository and is not an independently guaranteed permanent URL. Keep the repository and account active. A custom domain that you control can provide more durable branding, but requires domain registration and renewal.

## Important release blocker

The current ORBIT source creates anonymous Supabase accounts but does not yet provide an in-app account-deletion control. Google Play's account-deletion requirements may apply. This package explains the current manual email request channel honestly, but **the policy page alone does not complete the account-deletion requirement**. Implement and test in-app deletion and a clear external deletion-request page before declaring the app fully compliant.

## Accuracy notes

The policy was drafted from the ORBIT ZIP source supplied for review. It describes the current build configuration. If production AdMob ads, Google Play Billing, analytics, new permissions, or other data flows are enabled later, update this policy and the Play Console Data safety declaration before release.
