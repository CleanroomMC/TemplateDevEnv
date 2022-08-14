## Releasing to Github:

This workflow will make a release and tag based on the version of your mod (`mod_version` variable). 
It is also checking if you have incremented the version based on the latest release, but this is also introducing a unique issue.
If you don't have a release it will fail, so a workaround is to create a dummy release based on the initial commit and delete it afterwards

## Releasing to CurseForge:
For the `Release to CurseForge` workflow to work you will need to set up [github secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository)

The following secrets exist:

CURSEFORGE_PROJECT_ID - needs to be setup manually for each project

CURSEFORGE_API_KEY - if your project belongs to the Clanroom CF group then this [secret](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-an-organization) should already exit

## Notes:

For the workflows to be detected they must be on the main branch

You can add the template as a remote in git and pull changes from it

For the `Release to GitHub` workflow to work your repo needs to be public

Information about the [GITHUB_TOKEN](https://docs.github.com/en/actions/security-guides/automatic-token-authentication#permissions-for-the-github_token) in the `Release to CurseForge` workflow

## Credits:

The workflows are taken from the [BQ-u repo](https://github.com/CleanroomMC/BetterQuesting)