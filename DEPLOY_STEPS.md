# Deploy Steps - GitHub Pages

Current test repository:

`https://github.com/artkis/aloma-workshop-qc-portal`

This is hosted under Arthur's existing `artkis` GitHub account to avoid the new-account verification bottleneck. If a dedicated QC Workshop GitHub account becomes practical later, recreate or transfer the repository there.

## Repository

Recommended repository name:

`aloma-workshop-qc-portal`

Recommended visibility:

`Public`

GitHub Pages URL shape:

`https://artkis.github.io/aloma-workshop-qc-portal/`

Edge-first email signature link:

`microsoft-edge:https://artkis.github.io/aloma-workshop-qc-portal/`

## Files To Publish

- `index.html`
- `README.md`

## Browser Rule

Use a normal HTTPS link when the page must work in any browser.

Use an Edge protocol link when the company requirement is to land in Microsoft Edge on Windows:

`microsoft-edge:https://...`

Do not use:

- `ms-excel:`
- `ms-word:`
- `file:///`
- local `C:\...` paths
- `.url` shortcut files
- `.lnk` shortcut files

Note: `microsoft-edge:` is Windows/Edge-specific. If an email app or non-Windows device blocks protocol links, use the normal HTTPS URL as fallback.

## Safe Publishing Rule

Do not publish controlled files, case evidence, internal drafts, private working notes, or company records to GitHub Pages.

GitHub Pages is only the front door. Protected company files stay in Microsoft 365 / SharePoint.
