# App Privacy Policies

Static HTML pages for multiple apps, hosted together with GitHub Pages.

## Pages

- [All app policies](index.html)
- [ElectriCode Pro](electricode-pro/index.html): existing policy, copied without substantive changes.
- [TextPilot](textpilot/index.html): draft, not ready for app store submission.
- [Learn to read](learn-to-read/index.html): draft, not ready for app store submission.
- [Legacy ElectriCode Pro URL](privacy-policy.html): retained for existing links.

The two draft pages do not assert unverified data practices. Confirm each app's
package ID, developer and privacy contact, data and permissions, external services,
advertising, purchases, accounts, retention, deletion, and intended audience before
replacing the draft content with a complete policy. For Learn to read, also confirm
children's privacy and any microphone or speech processing. Then set the effective
date, remove draft notices from the page and directory, and update the robots tag.
The `noindex` tag does not make drafts private: all deployed pages are public.

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
https://USERNAME.github.io/REPOSITORY/textpilot/
https://USERNAME.github.io/REPOSITORY/learn-to-read/
```

Use each app's direct, finalized policy URL in its store listing. No custom domain,
backend, or build step is required. Publishing changes to the selected branch updates
the site automatically. GitHub Pages must still be enabled in the repository settings;
creating these files locally does not deploy them.

Keep the legacy page available while existing app or store links point to it.
When changing the ElectriCode Pro policy, update both its new page and the legacy
page so that they remain consistent. Avoid renaming the repository or app folders
after distributing their URLs.

## Add Another App

Create a folder with a stable lowercase, hyphenated name and an `index.html` policy
inside it, then add a relative link to the root directory page. Use app-specific,
verified content rather than copying another app's data claims.
