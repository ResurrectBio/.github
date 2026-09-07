![RBLogo](logo/rb_logo.png?raw=true "logo")
# .github

This repository holds the **default community health files** for every repository in the ResurrectBio organisation.

Any repo in this org that doesn't have its own copy of a file below will automatically use the version defined here.

## What's in here

| File | Purpose |
|---|---|
| `CODE_OF_CONDUCT.md` | Sets expectations for respectful behavior across issues, PRs, and reviews. |
| `SECURITY.md` | Vulnerability reporting policy. Adds a "Report a vulnerability" link to every repo's Security tab. |
| `SUPPORT.md` | Where to ask questions or get help, separate from bug reports. |
| `PULL_REQUEST_TEMPLATE.md` | Default template shown when opening a PR in any repo without its own. |
| `ISSUE_TEMPLATE/bug_report.md` | Structured bug report form. |
| `ISSUE_TEMPLATE/feature_request.md` | Structured feature request form. |
| `ISSUE_TEMPLATE/config.yml` | Controls the issue template chooser (e.g. disabling blank issues, linking to Discussions). |

## How it works

GitHub looks for these files in this order:

1. The individual repo itself (root, `.github/`, or `docs/`)
2. This `.github` repo, as a fallback

So any repo can override a default just by adding its own version of a file — this repo only fills the gaps.

## Updating a default

1. Edit the relevant file in this repo and open a PR.
2. Once merged, the change applies org-wide immediately — no need to touch individual repos.
3. If a change should *not* apply everywhere, add the file directly to the specific repo instead of changing it here.

## Notes

- This repo must stay **public** for the defaults to propagate — see [GitHub's docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for details.

Proprietary and Confidential. © Resurrect Bio. All rights reserved. This repository and its contents may not be copied, modified, or distributed without express written permission from Resurrect Bio.
