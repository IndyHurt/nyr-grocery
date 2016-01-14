# nyr-grocery
New Year's Resolutions - Grocery POIs

* http://indyhurt.github.io/nyr-grocery

## Parts

* Blog post - [index.html](index.html)
* Small map for blog post - [map_grocery/embed.html](map/embed.html)
* Big map - [map_grocery/index.html](map_grocery/index.html)
* Scene file (powers the map) - [map_grocery/grocery.yaml](map_grocery/grocery.yaml#L697-L761)
* Map interactivity - [map_grocery/main.js](map/main.js)


### To run locally:

Download this repo, then start a web server in its directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to: [http://localhost:8000](http://localhost:8000)
