# action-jira-linter 🧹

For of https://github.com/jira-tools/action-jira-linter in order to accommodate Enf-of-Life for Node16 in GitHub Actions https://github.blog/changelog/2024-09-25-end-of-life-for-actions-node16/

## updating and building

Edit the Typescript files in `/src` and build using Node `v16.20.2` and npm `8.19.4`.

Use `nvm install lts/gallium` to install the appropriate Node version and `npm i` to install dependencies.

Action JS is built using `npm run build` and output to `/lib`.

Push changes to `/lib` to Github and tag a new release.

Update your workflows to use `"marknorton-sabio/action-jira-linter@<tagged version>"`
