
<!--- ![beta_badge](https://img.shields.io/badge/State-Beta-orange?style=for-the-badge) -->
[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

# Material 3 Theme for Home Asistant: Template <!--- #07, Dark Olive Green -->

## What is it
A Material 3 based extended Dark & Light theme for Home Assistant.

This theme not only defines Material 3 dark and light mode colors, but also adapts some of the Home Assistant colors in dark mode as advised by Material 3:
- The error, warning, success and info colors
- The energy dashboard colors
- The label badge (red, blue, green, yellow, grey) colors
- The state climate colors
- The state (on, off, home, not home, unknown, idle) colors

All these colors have been desaturated a bit and given more brightness to have a better match with the dark mode.

The theme also defines some Neumorphic shadow colors for dark and light mode.

For beta documentation: see https://ha-m3-themes.docs.amoebelabs.com/

## Installation via HACS
This Theme is in the default theme repository of HACS

## Manual Installation
Get the yaml file and put int into your `themes` folder.

If you have the following in your `configuration.yaml`:
```yaml
frontend:
  themes: !include_dir_merge_named themes/
```

The theme will be automatically available once you have reloaded the themes using the Home Assistant 'Developer Tools' > 'Services' > 'frontend.reload_themes' service.

## Theme Preview:
Below the definition of the theme, generated and displayed using the Swiss Army Knife custom card for Home Assistant (NYR).

![m3-07-palettes](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-theme-07-palettes.png)

![m3-07-surfaces](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-theme-07-surfaces.png)

![m3-07-light](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-theme-07-light.png)

![m3-07-dark](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-theme-07-dark.png)

## Some real-world screenshots:
A Light and Dark example made with the Swiss Army Knife custom card.

Note that the card background in the light theme is white instead of the lightest theme background. Will be corrected...

![m3-07-sake12-light](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/screenshots/Mockup%20Home%20Assistant%20-%20Example%2012m3-07-light%20Detail.png)

![m3-07-sake12-dark](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/screenshots/Mockup%20Home%20Assistant%20-%20Example%2012m3-07-dark%20Detail.png)

