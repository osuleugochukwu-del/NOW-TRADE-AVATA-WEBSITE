TRADE AVATA - COMPLETE WEBSITE PACKAGE
=======================================

This archive is the complete merged Trade Avata website package.
It includes the public website, tools, analytics/journal foundation, Learn/Store/Market/Trade areas, admin pages, Firebase configuration, support, email architecture, copy-trading architecture, prop-firm architecture, and GitHub Actions deployment workflow.

IMPORTANT UPLOAD RULE
---------------------
Upload the CONTENTS of this archive to the ROOT of the GitHub repository.
Do NOT create a folder such as Trade_Avata inside the repository.

CRITICAL GITHUB ACTIONS FILE
----------------------------
.github/workflows/build-and-deploy.yml

The .github folder is REQUIRED. If the GitHub web uploader does not show it, upload the .github/workflows/build-and-deploy.yml file separately after uploading the rest of the package.

DO NOT upload Layer 2 or Layer 3 separately. This package is already merged.

After committing to main:
1. Open the repository's Actions tab.
2. Look for: Trade Avata - Build and Deploy.
3. The push to main should create a run automatically.
4. If it does not, use Actions -> Trade Avata - Build and Deploy -> Run workflow.
5. Do not add another deployment workflow; this package already contains one.

Firebase secrets and production email/provider credentials are intentionally NOT stored in this package.
Use .env.example as the configuration reference and keep real secrets out of GitHub.
