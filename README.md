# tileserver-gl deployment

tileserver-gl deployment & custom style for [Kiel Live](https://kiel.ju60.de/)

## setup

1. Download map tiles for *Schleswig-Holstein* from <https://openmaptiles.com/downloads/tileset/osm/europe/germany/schleswig-holstein/> to `./data/sh.mbtiles`
1. Download fonts with `curl https://git.project-insanity.org/onny/web-mapbox-gl-js-offline-example/-/archive/master/web-mapbox-gl-js-offline-example-master.tar.gz\?path\=fonts | tar --strip-components=1 -C ./data -xzf - web-mapbox-gl-js-offline-example-master-fonts`
1. `mv .env.dist .env`
1. Change values according to your needs
