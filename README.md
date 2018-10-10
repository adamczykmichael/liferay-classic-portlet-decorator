# Classic Portlet Decorator Themelet
Brings back the old way of hiding and displaying what is now called the portlet decorators. With this themelet you will be able to get the functionality without touching your themes. You will be extending your themes with the themelet.

## Compatibility:
Liferay 7.0 and 7.1

## Getting Started
### Prerequisites:
- Node.js
- Yeoman
- gulp
- Liferay Theme Generator

Information/guide on how to install the Liferay Font-End ecosystem:
https://dev.liferay.com/develop/tutorials/-/knowledge_base/7-1/creating-themes

### npm module
You can install the themelet from the npm registry using the Theme Generator.

### Install locally
This is a themelet, so you will need to install it into to you existing theme(s).

1. Navigate to your theme’s root folder and run the following command:
  `gulp extend`
2. Choose Themelet as the theme asset to extend
3. Select Search globally installed npm modules (cloned from github) or search the npm registry
4. Highlight your themelet, press spacebar to activate it, and press Enter to install it
5. Run `gulp deploy` to build and deploy your theme with the new themelet updates

