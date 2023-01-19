# PnP SPFx generator - community driven and open source

[![CircleCI](https://circleci.com/gh/pnp/generator-spfx.svg?style=shield)](https://circleci.com/gh/pnp/generator-spfx) [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/generator-spfx/generator)

❗️❗️❗️ Jan 2023 - generator-SPFx is currently not actively mainatained anymore. ❗️❗️❗️

This Yeoman generator provides improved governance for SharePoint Framework projects. It extends the out of the box Yeoman generator from Microsoft (@microsoft/generator-sharepoint) with recommended patterns and additional capabilities.
 
For an optimized development workflow, it extends the capabilities for ReactJS, and Knockout projects and support for additional frameworks, such as HandlebarsJS, Aurelia, VueJS and Angular Elements. It also includes includes advanced code analysis and testing tools, which you can take advantage in you development work.
 
All projects generated by this generator are 100% compliant with the out-of-the-box Yeoman generator from Microsoft. After the creation of a new solution, you can use either this generator or @microsoft/generator-sharepoint to add additional assets to your solution.

![PnP SPFx Generator](https://pnp.github.io/generator-spfx/assets/pnpspfx-title.png)

This is an open-source extension for native out of the box SPFx generator to introduce additional scaffolding support for Angular Elements, Aurelia, VueJS, Handlebars  and many more in future. This generator has a dependency on native SPFx generator from Microsoft.

## Documentation

More details can be found in the documentation at [https://aka.ms/pnpgenerator](https://aka.ms/pnpgenerator)

- [Release notes](https://pnp.github.io/generator-spfx/release-notes/)

## Installation

### via NPM

```sh
npm install -g @pnp/generator-spfx
```

### via YARN

```sh
yarn global add @pnp/generator-spfx
```

### via PNPM

```sh
pnpm install -g @pnp/generator-spfx
```

### For Evaluation and Testing

This generator can be also tested via [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) and the following command:

```sh
npx -p yo -p @pnp/generator-spfx yo @pnp/spfx
```

It will create a new project without installation of the generator. To add other assets the same command line can be executed again on the project folder.

## Usage

To run the generator:

```
yo @pnp/spfx
```

We will guide you through the your project creation.

![Follow the  on screen](https://pnp.github.io/generator-spfx/assets/yo-running.png)

## For Development

```
git clone https://github.com/pnp/generator-spfx.git
```

More details can also be found in the documentation on [how to extend this generator](https://pnp.github.io/generator-spfx/compose/).

*More details on our [documentation](https://pnp.github.io/generator-spfx/)*

![SharePoint Patterns and Practices](https://devoffice.blob.core.windows.net/media/Default/PnP/pnplogoblue.png)

**Sharing is caring!**



