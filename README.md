### Deployment Process
1. Make edits to the frames you want to change
2. Run `yarn build`
3. Run `yarn deploy` (site will go down temporarily)
4. In the `gh-pages` branch, create a file called `CNAME` at the root of the repo with the content `moiramacneil.com`

The last step may be easiest to do via the github site, since `gh-pages` has a different gitignore profile