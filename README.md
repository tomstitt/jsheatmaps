# jsHeatmaps

1) Download your data
    * Use *download.py* from https://github.com/tomstitt/heatmap
2) Create a filelist
    * `cd strava && find . -name "*.gpx" -exec basename {} \; > filelist.txt`
3) Run *server.py* in the *strava* directory created from *download.py*
    * TODO
4) Open *index.html*
    * You can change the color, opacity, and line thickness in the file
        * TODO
    * You can change the default location and zoom (currently Berkeley CA)
        * TODO
    * Slow...
        * TODO
        * Possible solutions?
            * https://github.com/mapbox/mapbox-gl-js
                * requires mapbox token
            * https://github.com/robertleeplummerjr/Leaflet.glify
