# blazium-assets

Artwork, documents, and other assets used in the [Blazium](https://blazium.app) project.

Colors used in the logo and other assets.

-   `#F079F2` :pink_circle: **Pink**
-   `#8130F2` :purple_circle: **LTPurple**
-   `#7732D9` :purple_circle: **Purple**
-   `#797FF2` :blue_circle: **Blueish**
-   `#0D0D0D` :black_circle: **Black**

## For SVG images
SVG images need to be processed with svgo before usage to minimize file size.

``` bash
# install svgo
npm install -g svgo

# svgo usage
svgo --config ./svg.config.mjs -rf path/to/directory_with_svgs -o path/to/output_directory
```

The file `svg.config.mjs` can be found in the repository.
