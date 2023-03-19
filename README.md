# Run my private pages on a GH Pages server

Objective: Publish an Antora site stored on Bitbucket on GithubPages

https://github.com/npiper/bitbucket-repos.git

`personal-mba-token`

## Site deployment

https://npiper.github.io/bitbucket-repos/Personal%20MBA/main/

## GH Actions

The Github actions checks out bitbucket repo, installs and builds antora
then copies the `dist` folder and commits into the GH Pages branch.

## Secrets needed

 * Bitbucket token - clone / authenticate to private Repo
 * GH Token - Publish Antora site once generated to GH Pages

## References

https://github.com/shimataro/test-clone-bitbucket-in-actions/blob/master/.github/workflows/ci.yml[Gist of a bitbucket checkout]

https://docs.antora.org/antora/latest/publish-to-github-pages/[Antora - Publish to Github pages]

