# Brightlayer UI Component Documentation
This repository holds the source code for the landing page at [brightlayer-ui-components.github.io](https://brightlayer-ui-components.github.io). It's a single-page React app that links to the separate documentation pages for each framework:
- [React](https://brightlayer-ui-components.github.io/react)
- [Angular/Ionic](https://brightlayer-ui-components.github.io/angular)
- [React Native](https://brightlayer-ui-components.github.io/react-native)

## Updating
To update the site, first clone the repository and make a feature branch:
```
git clone https://github.com/brightlayer-ui-components/documentation.git
cd documentation
git checkout -b feature/my-feature
```
Then you may run `yarn && yarn start` to start a local server. 

Once you have made your changes, push your feature branch and make a Pull Request into the master branch.

## Deployment
Deployment of this site is handled automatically through CircleCI and GitHub Pages. Any code that is merged into the master branch will automatically be deployed to [brightlayer-ui-components.github.io](https://brightlayer-ui-components.github.io). Updates usually take effect in under a minute.
