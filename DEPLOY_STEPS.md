# Deploy Notes - Workshop QC Portal

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

Email signature target:

`https://artkis.github.io/aloma-workshop-qc-portal/`

If the company requires Edge on Windows, the email signature can use this protocol target:

`microsoft-edge:https://artkis.github.io/aloma-workshop-qc-portal/`

## Files To Publish

- `index.html`
- `README.md`

## Portal Route Rule

The GitHub Pages URL opens the clickable QC portal directly.

Do not make the first portal click land in a SharePoint folder or Microsoft sign-in screen. Public buttons should route inside the portal first. Protected company files remain in the approved company file system and are not published here.

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

GitHub Pages is the public-safe clickable QC portal surface. Controlled company records stay in the approved company file system.
