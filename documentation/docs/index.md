# MkDocs Vercel Test

This is an example MkDocs project deployed to Vercel.

Vercel automatically detects the contents of this repo and automatically runs `pip install` and runs the `mkdocs build` command to generate the pages.

## Github Repository

This sample repository can be found here: https://github.com/john-fueled/mkdocs-vercel-test

## Deployment

Vercel can connect to a Github repo and deploy the contents based on the subfolder in the repo.

This project contains the `documentation` subfolder where this MkDocs project lives.

### Configuring the Vercel Project

Navigate to the project settings page: `https://vercel.com/<org>/<project>/settings`.

Override the `Root Directory` to be `documentation`.

![Vercel Root Directory settings](images/vercel-settings-root-directory.jpg)

Optional: Toggle the "Include source files outside of the Root Directory in the Build Step" off if you only need the contents in `/documentation`.
