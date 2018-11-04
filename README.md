# hexo-renderer-stylus-full

Add support for [Stylus] with [Nib], [Rupture] and [KoutoSwiss].

## Install

Prerequisites:
- Hexo 3: >= 0.2
- Hexo 2: 0.1.x

``` bash
$ npm i hexo-renderer-stylus-full --save
```

## Options

You can configure this plugin in `_config.yml`.

``` yaml
stylus:
  compress: false
  sourcemaps:
    comment: true
    inline: true
    sourceRoot: ''
    basePath: .
```

- **Stylus**:
  - **compress** - Compress generated CSS (default: `false`)


- **Sourcemaps**
  - **comment** - Adds a comment with the `sourceMappingURL` to the generated CSS (default: `true`)
  - **inline** - Inlines the sourcemap with full source text in base64 format (default: `false`)
  - **sourceRoot** - `sourceRoot` property of the generated sourcemap
  - **basePath** - Base path from which sourcemap and all sources are relative (default: `.`)

[Stylus]: http://stylus-lang.com/
[Nib]: http://stylus.github.io/nib/
[Rupture]: https://jescalan.github.io/rupture/
[KoutoSwiss]: http://kouto-swiss.io/
