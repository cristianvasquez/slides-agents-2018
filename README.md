# agents-PhD-assets

```
npm start
```

## Palette

Blue
> #4b86c2

Light brown
> #ce6c31

Yellow
> #fafaa2

Darker brown
> #942a0e

## Enable images export in libreDraw

There is an extension for libreDraw at: https://extensions.libreoffice.org/extensions/export-as-images/0.9.3

But for some reason the russian guy deactivated Svg. I had to activate it

Tools -> Macros -> Organize Macros -> ExportAsimages [edit]

Dialog2, enable SVG, make it selected

Changed in ExportImages script:

```
	if imgType = "svg" then
	sFileUrl = ConvertToURL( exportPath + slideNum + "_" + exportName + ".svg")
```