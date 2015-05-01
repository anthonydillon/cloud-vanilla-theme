# Cloud vanilla theme for Vanilla framework

A extenstion of [Vanilla framework](https://github.com/ubuntudesign/vanilla-framework), written in [Sass](http://sass-lang.com/).

## Local usage

Install the Node package into your project:

``` bash
npm install cloud-vanilla-theme  # Installs the theme with the framework within
```

Then reference it from your own Sass file that is built to generate your sites CSS:

``` sass
// Import the theme
@import "../../node_modules/cloud-vanilla-theme/scss/theme";
// Run the theme
@include cloud-vanilla-theme;
```

You can override any of the settings in [_global-settings.scss](scss/_global-settings.scss).

Code licensed [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd.](http://www.canonical.com/).
