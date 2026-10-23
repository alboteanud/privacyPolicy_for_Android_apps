# App Privacy Policies

Static HTML pages for multiple apps, hosted together with GitHub Pages.

## Pages

- [All app policies](index.html)
- [ElectriCode Pro](electricode-pro/index.html): privacy policy.
- [F-Gas Pro](fgas-pro/index.html): privacy policy for study progress, feedback, and Google Play Billing.
- [Motion Guard](surveillance-app/index.html): privacy policy for on-device motion detection and local video recordings.
- [TextPilot](textpilot/index.html): privacy policy for SMS messaging and scheduled texts.
- [Learn to read](learn-to-read/index.html): privacy policy.
- [Learn Math](learn-math/index.html): privacy policy for locally stored child profiles, settings, and learning progress.
- [PricePeek](pricepeek/index.html): privacy policy for product search and price comparison.
- [Learn to read root URL](privacy-policy.html): same policy at the root-level URL.

The policies describe app behavior and third-party services based on the current app
implementations. Review and update them if an app's permissions, data use, or service
providers change. All GitHub Pages content is public.

## Publish for Free With GitHub Pages

1. Push these files to a public GitHub repository.
2. Open the repository's **Settings > Pages**.
3. Select **Deploy from a branch**, choose the branch containing these files
	(usually `main`), and select **/(root)**.
4. Click **Save** and wait for GitHub to report a successful deployment.
5. Open the published site and check each policy link.

For a project repository, the URLs have this form; replace `USERNAME` and `REPOSITORY`:

```text
https://USERNAME.github.io/REPOSITORY/
https://USERNAME.github.io/REPOSITORY/electricode-pro/
https://USERNAME.github.io/REPOSITORY/fgas-pro/
https://USERNAME.github.io/REPOSITORY/surveillance-app/
https://USERNAME.github.io/REPOSITORY/textpilot/
https://USERNAME.github.io/REPOSITORY/learn-to-read/
https://USERNAME.github.io/REPOSITORY/learn-math/
https://USERNAME.github.io/REPOSITORY/pricepeek/
```

Use each app's direct, finalized policy URL in its store listing. No custom domain,
backend, or build step is required. Publishing changes to the selected branch updates
the site automatically. GitHub Pages must still be enabled in the repository settings;
creating these files locally does not deploy them.

The root-level `privacy-policy.html` URL serves Learn to read. Use each app's
dedicated policy URL in its store listing. Avoid renaming the repository or app
folders after distributing their URLs.

## Add Another App

Create a folder with a stable lowercase, hyphenated name and an `index.html` policy
inside it, then add a relative link to the root directory page. Use app-specific,
verified content rather than copying another app's data claims.
