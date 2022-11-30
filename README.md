# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## NOTE: 
*The purpose of this repo was to test deployment of Docusaurus, via Github pages, in addition to using several tools/features (such as versions and a local search bar).*

I plan to continue with a new repo to utilize Docusaurus for its handy features and ease of use!

The live site for this demo can be found [here](https://etam1234.github.io/Docusaurus-Test/).

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
