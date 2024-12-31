# blazium-assets

Artwork, documents, and other assets used in the [Blazium](https://blazium.app) project.

Colors used in the logo and other assets:
- `#ff80ff` **Pink**
- `#af40df` **Gradient middle color**
- `#6000bf` **Purple**
- `#220f25` **Purple background**
- `#404040` **Dark gray**

Fonts used:
- Roboto Bold for `Blazium` with -4.0 charachter spacing
- Poppins Regular for `Game Engine`

## For SVG images
SVG images need to be processed with svgo before usage to minimize file size.

``` bash
# install svgo
npm install -g svgo

# svgo usage
svgo --config ./svg.config.mjs -rf path/to/directory_with_svgs -o path/to/output_directory
```

The file `svg.config.mjs` can be found in the repository.
