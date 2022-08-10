## Releasing to CurseForge:
For the `Release to CurseForge` workflow to work you will need to set up [github secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository)

The following secrets exist:

CURSEFORGE_PROJECT_ID - needs to be setup manually for each project

CURSEFORGE_API_KEY - if your project belongs to the Clanroom CF group then this [secret](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-an-organization) should already exit


Information about the [GITHUB_TOKEN](https://docs.github.com/en/actions/security-guides/automatic-token-authentication#permissions-for-the-github_token) in the `Release to CurseForge` workflow

## Notes:

For the `Release to GitHub` workflow to work you repo needs to be public

You can add the template as a remote in git and pull changes from it

For the workflows to be detected they must be on the main branch

## Credits:

The workflows are taken from the [BQ-u repo](https://github.com/CleanroomMC/BetterQuesting)