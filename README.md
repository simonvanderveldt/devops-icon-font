# Devops icon font

## How to use the font
- Include `output/devops-icon-font.css` and all fonts in the `output/fonts` directory in your HTML/CSS
- Add an icon using `<i class="icon-{icon-name}">`, for example `<i class="icon-docker">`
- For an overview of the icons included see http://simonvanderveldt/devops-icon-font


## How to build the font
```
# Simply run fontcustom to build the devops-icon-font
docker run --rm -v ${PWD}:/project drichner/fontcustom compile
```


# How to add an icon
- [Inkscape](https://inkscape.org) SVG sources can be found in the `sources` directory
- When adding an SVG save the Inkscape SVG in the `sources` directory
- Save the final svg as "Optimized SVG" in the `vectors` directory
- Run fontcustom as described in How to build the font
