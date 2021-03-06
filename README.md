# Tab swipe
Swipe to navigate between tabs.

## Dependencies
Mendix 6.10

## Demo project
![Demo](/assets/demo.gif)

https://tabswipe100.mxapps.io

## Usage
- Place the widget in the same page/container/snippet as the target tab container (right below it).
- Add the name of the target tab container / tab control to the widget (found in the common tab of the tab container properties in the modeler)

![config_general_tab](/assets/config_general_tab.png)
![config_appearance_tab](/assets/config_appearance_tab.png)

## Issues, suggestions and feature requests
We are actively maintaining this widget, please report any issues or suggestions for improvement
https://github.com/mendixlabs/tab-swipe/issues

## Development
Prerequisite: Install git, node package manager, webpack CLI, grunt CLI

To contribute, fork and clone.

    > git clone https://github.com/mendixlabs/tab-swipe.git

The code is in typescript. Use a typescript IDE of your choice, like Visual Studio Code or WebStorm.

To set up the development environment, run:

    > npm install

Create a folder named `dist` in the project root.

Create a Mendix test project in the dist folder and rename its root folder to `dist/MxTestProject`.
Changes to the widget code shall be automatically pushed to this test project. Or get the test project from
[https://github.com/mendixlabs/tab-swipe/releases/latest](https://github.com/mendixlabs/tab-swipe/releases/latest)

To automatically compile, bundle and push code changes to the running test project, run:

    > grunt
