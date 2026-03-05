# .github (Org Profile + Community Health)

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR](https://github.com/Cloud2BR)

Last updated: 2026-02-25

----------

> This repository holds the public GitHub organization profile content for Cloud2BR and shared GitHub community health files (issue templates, PR template, security policy, etc.).

## What this is for

- Profile hub: `profile/README.md` is displayed on the Cloud2BR organization profile page (when this repository is the special `.github` repo for an organization).
- Community health: Shared templates and policies under `.github/` apply across repositories in the organization (where supported by GitHub).
- View counter automation (optional): A GitHub Actions workflow can refresh the "Total views" badge in the profile README and rewrite `metrics.json`.

## How to update

- Update the org profile text: edit `profile/README.md`.
- Update templates/policies: edit the relevant files in this repo.

## View counter setup

- Add a repository secret named `TRAFFIC_TOKEN`.
	- This must be a token that can read repository traffic insights for this repo.
- Run the workflow manually from GitHub: Actions -> Update view counter -> Run workflow.

> [!NOTE]
> - The workflow uses an open source tool repository to generate the badge and `metrics.json`.
> - Manual edits to `metrics.json` are not recommended because the workflow will overwrite it.

<!-- START BADGE -->
<div align="center">
	<img src="https://img.shields.io/badge/Total%20views-1580-0A66C2" alt="Total views">
	<p>Refresh Date: 2026-02-25</p>
</div>
<!-- END BADGE -->
