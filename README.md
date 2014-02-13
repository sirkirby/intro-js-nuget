# Intro.js Nuget Package #

For more info on the project, visit the main site http://usablica.github.io/intro.js/

## Build ##
Install the grunt cli tools

`npm install -g grunt-cli`

Install the required modules

`npm install`

build the package to the `dist` folder

`grunt`

## Installing ##
https://www.nuget.org/packages/introjs

`PM> install-package introjs`

## ASP.Net Bundling & Minification ##

    bundles.Add(new ScriptBundle("~/bundles/introjs").Include("~/Scripts/intro.js"));

    bundles.Add(new StyleBundle("~/Content/introjs").Include("~/Content/introjs.css"));

	bundles.Add(new StyleBundle("~/Content/introjs-rtl").Include("~/Content/introjs-rtl.css"));

[License](LICENSE.txt)
==================
