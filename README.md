# Houdini SVG Exporter

Simple Digital Assets that exports Houdini poly lines to SVG file.

## Simple instalation

![LK3NGvWoxy](https://user-images.githubusercontent.com/8003487/87589879-c7f1d780-c69a-11ea-8d72-a1ae692e5e7b.gif)

Go to main menu Assets > Install Asset Library. Select `svg_exporter.hda` from *hdas* directory and click Install. 

Now search for `SVG Exporter` node. 

## Global Instalation (Optional)

 1. Copy *hdas* directory to Houdini preferences directory
 On Windows it is ussualy %USERPROFILE%\Documents\houdini18.0
 2. Open *houdini.env* in any text editor from Houdini preferences directory
 3. Add the following line to it

 ```
 HOUDINI_OTLSCAN_PATH="C:\Users\koval\Documents\houdini18.0\hdas;&"
 ```
 NOTE: Don't forget to replace `C:\Users\kif` with your path.

## Supported polygon attributes

| Attribute  | Description   |
| ---------- | ------------- |
| Cd         | Color         |
| swidth     | Stroke width  |


This script is base on the original work by [Entagma](https://entagma.com/isocontours-importing-exporting-vectors-tofrom-houdini/).
