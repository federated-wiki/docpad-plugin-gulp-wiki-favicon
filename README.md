# docpad-plugin-gulp-wiki-favicon
This DocPad plugin integrates a hosted gulp pipeline, based on the canvas module, for the favicon generator of wiki-client.

#### Favicon generation via Gulp

The initial idea and code for changing Favicons comes from [Federated Wiki](http://fed.wiki.org).
Check the source!

* `canvas`

#### Dependencies for `canvas`

* Ubuntu : `apt-get install pkg-config libpng-dev libgif-dev libfreetype6-dev libpixman-1-dev libcairo2-dev libjpeg-dev`
* [Fedora](https://github.com/Automattic/node-canvas/wiki/Installation---Fedora) : `yum install cairo cairo-devel cairomm-devel libjpeg-turbo-devel pango pango-devel pangomm pangomm-devel giflib-devel`
* OS X : https://github.com/Automattic/node-canvas

---

This repo came into existence after its logic caused trouble within another [DocPad project](https://github.com/geopedia/geopedia.github.io/commit/d5ada0e8eb66aadadc4a7829fdc6666e4115e670).
