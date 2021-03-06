# Maki jp

Makiは、ポイントデータ(POI)表記を中心に、特にMapBoxマップで使用するために作られた地図アイコンデザインセットです。
MapBoxでMakiを使用する詳細方法については、こちらをご参考ください。

http://mapbox.com/tilemill/docs/guides/using-maki-icons/.

Makijp は上記の Maki をフォークして、日本で用いられている地図記号表記を追加、反映させることを目標とした地図アイコンデザインセットです。

Makijpアイコンデザイン公開グループ

https://www.facebook.com/groups/619889871355231


## Notes on Contributing

The working file that includes all the icons is here: https://github.com/mapbox/maki/blob/gh-pages/src/maki-icons.svg.

I use [Inkscape](http://inkscape.org/) for editing and exporting from the .SVG, to take advantage of Inkscape's batch export, as all the icons have unique ID's that Inkscape uses to create file names. 

Maki follows these design principles:

- Simple, clear, recognizable
- Three sizes: 12/18/24 px
- Single color, with 1px 30% transparent white outline.
- Based upon internationally recognized symbols when appropriate. Good sources for symbol precedents include [AIGA symbols](http://www.aiga.org/symbol-signs/), OSM's icon set [SBBJ SVG Map Icons](http://www.sjjb.co.uk/mapicons/contactsheet) and the [Noun Project](http://thenounproject.com/).

To view the backlog of icons that need to be created, visit https://github.com/mapbox/maki/wiki/Maki-Backlog

If you decide to modify `src/maki-icons.svg` in order to add an icon to the set, before submitting a pull request, make sure you clear user-specific settings from the SVG with: `sed -i 's/\ *inkscape:export-filename=".*"//g' maki-icons.svg` on Linux or `sed -i "" -e 's/\ *inkscape:export-filename=".*"//g' maki-icons.svg` on OSX.

It isn't necessary, but if you want to be an over-acheiver, you can also update the website with your new icon by [following these instructions](https://github.com/mapbox/maki/wiki/Adding-icons-to-the-site)
## Completed icons
