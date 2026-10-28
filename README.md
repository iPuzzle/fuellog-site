# Easy Fuel Log's website

Easy Fuel Log's public pages, served by GitHub Pages at <https://ipuzzle.github.io/fuellog-site/>:

- the home and support page, in [English](index.html) and [Ukrainian](uk/index.html);
- the privacy policy, in [English](privacy/index.html) and [Ukrainian](uk/privacy/index.html);
- the terms of use, in [English](terms/index.html) and [Ukrainian](uk/terms/index.html);
- the desktop installers of each beta and release, under [Releases](https://github.com/iPuzzle/fuellog-site/releases).

The pages are plain HTML and CSS, with no build step and no scripts. They are written alongside the
app, so that the privacy policy always matches what the app does, and published here from it.
Questions: easyfuellog@gmail.com.

The font is Roboto, with the hryvnia sign added, under the SIL Open Font License
([assets/fonts/Roboto-OFL.txt](assets/fonts/Roboto-OFL.txt)).
The icons, the logo and the social cards in `assets/` are the app's brand kit's, and the fonts the design
system's, copied there by the app's build.

The home pages show the app's own screens and the design system's haze and icons, as WebP:

- `assets/screens/en/`: Google Play's English phone screenshots (`docs/store/google-play/en-US/images/phoneScreenshots/`)
  at 720×1280, and its 10-inch `1-Timeline` at 1600×900;
- `assets/screens/uk/`: the screen tests' Ukrainian Dusk goldens (`app/shared/screenshots/screens/*_UkDusk.png`, 360×800),
  and Google Play's Ukrainian 10-inch `1-Timeline` at 1600×900;
- `assets/haze-roadside.webp` and `assets/haze-station.webp`: `docs/design/system/backdrop/`, tinted with `--haze` through a mask;
- `assets/icons/`: the icons the pages use, from `docs/design/system/icons/`, tinted through a mask.
