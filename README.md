# .github Repository

This is a special repository that provides organization-wide configuration and documentation for Everybody Eats' GitHub organization.

## What is this repo for?

The `.github` repository is a GitHub feature that allows organizations to define shared templates, workflows, and documentation that apply across all repositories in the organization.

## What's in here?

### `/profile/README.md`
This file appears on the main page of our GitHub organization (at `github.com/your-org-name`). It's the first thing people see when they visit our organization, so it should:
- Welcome new contributors
- Explain what Everybody Eats does
- Link to our active repositories
- Provide guidance on how to get involved

## How does it work?

When you create a repository called `.github` in your organization:

1. **The profile README** (`/profile/README.md`) automatically displays on your organization's main page
2. **Templates and workflows** become available to all repositories in the organization
3. **Fallback defaults** - If an individual repo doesn't have its own templates, GitHub will use the ones from this repo

## Making changes

To update the organization profile or templates:

1. Clone this repository
2. Make your changes
3. Create a pull request
4. Get it reviewed by another team member
5. Merge to main

Changes to `/profile/README.md` will immediately appear on the organization page.

## Important notes

- This repo is public (or should be) so that the profile README displays correctly
- Don't put any sensitive information in here
- Individual repositories can override these defaults by creating their own templates
- Not all features require this repo - use it for truly organization-wide content

## Learn more

- [GitHub documentation on `.github` repositories](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Creating default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
