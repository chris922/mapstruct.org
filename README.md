# mapstruct.org

This repository contains the [mapstruct.org](https://www.mapstruct.org) webpage.

## Build it locally

### Install hugo

The page is built using [hugo](https://gohugo.io/). You first need to install _hugo_ as described 
[here](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo).

### Built the page

You just need to run `hugo` and get an output like this:

```
$ hugo
Building sites …
                   |  EN
+------------------+------+
  Pages            |   76
  Paginator pages  |   14
  Non-page files   |    0
  Static files     | 3227
  Processed images |    0
  Aliases          |   24
  Sitemaps         |    1
  Cleaned          |    0

Total in 4362 ms
```

Afterwards you will find the compiled files in the folder `public`.

Be aware that you can't just open the `index.html` and take a look at the generated site. 
In general it should run on a webserver to be served correctly.

### Development mode

When you make changes and want to check them directly in your browser you can start the _hugo_ dev-mode.
This will spawn a HTTP server, serve the compiled content and refresh everything automatically as soon as you 
make a change.

Just run `hugo server -D` and open the shown page (http://localhost:1313/ by default)

## Publish changes

TBD; `scripts/publish.sh`
