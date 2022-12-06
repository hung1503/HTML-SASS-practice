## Table of Contents

# CSS/SASS , Grid , Flexbox Assignment

Refer to this [link](https://preview.themeforest.net/item/maido-multipurpose-ghost-blog-theme/full_screen_preview/24837109?_ga=2.259990478.570486835.1654146705-2133876429.1654146705)(see 'Dark version') and create a similar webpage

## Requirements (max 4)

1. Floating the HTML elements using Flexbox and Grid system
2. Implementing basic animations as shown in the webpage (hover effect,
active link styles, typing effect). You can modify the outlook of the effects
3. Implement you codes, using the platform of your choice (For example, Github Pages), then rewrite README file.

This assignment only requires 1 static page. No JavaScript needed.
Font family and text content can be modified as your preferences.
You can ignore the small buttons/tags/lables in each card. Only
texts with some styles are enough.

## Bonus points (max 1)

1. Using SASS (either .sass or .scss) for styling
2. Make use of variables, mixin, extend



C:.
│   .gitignore
│   package-lock.json
│   package.json
│   README.md
│   
├───node_modules
│   │   .package-lock.json
│   │   
│   ├───.bin
│   │       sass
│   │       sass.cmd
│   │       sass.ps1
│   │       
│   ├───anymatch
│   │       index.d.ts
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │       
│   ├───binary-extensions
│   │       binary-extensions.json
│   │       binary-extensions.json.d.ts
│   │       index.d.ts
│   │       index.js
│   │       license
│   │       package.json
│   │       readme.md
│   │
│   ├───braces
│   │   │   CHANGELOG.md
│   │   │   index.js
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │
│   │   └───lib
│   │           compile.js
│   │           constants.js
│   │           expand.js
│   │           parse.js
│   │           stringify.js
│   │           utils.js
│   │
│   ├───chokidar
│   │   │   index.js
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │
│   │   ├───lib
│   │   │       constants.js
│   │   │       fsevents-handler.js
│   │   │       nodefs-handler.js
│   │   │
│   │   └───types
│   │           index.d.ts
│   │
│   ├───fill-range
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───glob-parent
│   │       CHANGELOG.md
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───immutable
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │
│   │   └───dist
│   │           immutable.d.ts
│   │           immutable.es.js
│   │           immutable.js
│   │           immutable.js.flow
│   │           immutable.min.js
│   │
│   ├───is-binary-path
│   │       index.d.ts
│   │       index.js
│   │       license
│   │       package.json
│   │       readme.md
│   │
│   ├───is-extglob
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───is-glob
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───is-number
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───normalize-path
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───picomatch
│   │   │   CHANGELOG.md
│   │   │   index.js
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │
│   │   └───lib
│   │           constants.js
│   │           parse.js
│   │           picomatch.js
│   │           scan.js
│   │           utils.js
│   │
│   ├───readdirp
│   │       index.d.ts
│   │       index.js
│   │       LICENSE
│   │       package.json
│   │       README.md
│   │
│   ├───sass
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │   sass.dart.js
│   │   │   sass.default.dart.js
│   │   │   sass.js
│   │   │
│   │   └───types
│   │       │   compile.d.ts
│   │       │   exception.d.ts
│   │       │   importer.d.ts
│   │       │   index.d.ts
│   │       │   options.d.ts
│   │       │
│   │       ├───legacy
│   │       │       exception.d.ts
│   │       │       function.d.ts
│   │       │       importer.d.ts
│   │       │       options.d.ts
│   │       │       plugin_this.d.ts
│   │       │       render.d.ts
│   │       │
│   │       ├───logger
│   │       │       index.d.ts
│   │       │       source_location.d.ts
│   │       │       source_span.d.ts
│   │       │
│   │       ├───util
│   │       │       promise_or.d.ts
│   │       │
│   │       └───value
│   │               argument_list.d.ts
│   │               boolean.d.ts
│   │               color.d.ts
│   │               function.d.ts
│   │               index.d.ts
│   │               list.d.ts
│   │               map.d.ts
│   │               number.d.ts
│   │               string.d.ts
│   │
│   ├───source-map-js
│   │   │   CHANGELOG.md
│   │   │   LICENSE
│   │   │   package.json
│   │   │   README.md
│   │   │   source-map.d.ts
│   │   │   source-map.js
│   │   │
│   │   └───lib
│   │           array-set.js
│   │           base64-vlq.js
│   │           base64.js
│   │           binary-search.js
│   │           mapping-list.js
│   │           quick-sort.js
│   │           source-map-consumer.js
│   │           source-map-generator.js
│   │           source-node.js
│   │           util.js
│   │
│   └───to-regex-range
│           index.js
│           LICENSE
│           package.json
│           README.md
│
└───src
    │   index.html
    │
    ├───compiled
    │       styles.css
    │       styles.css.map
    │
    └───styles
        │   styles.scss
        │
        ├───abstracts
        │   │   _mixins.scss
        │   │
        │   └───variables
        │           _colors.scss
        │           _fonts.scss
        │
        ├───images
        │   ├───mainBlogImgs
        │   │       pic1.jpg
        │   │       pic8.jpg
        │   │       pic9.jpg
        │   │
        │   ├───pinnedImgs
        │   │       pic2.jpg
        │   │       pic3.jpg
        │   │       pic4.jpg
        │   │       pic5.jpg
        │   │
        │   └───preBlogImgs
        │           pic10.jpg
        │           pic11.jpg
        │           pic12.jpg
        │           pic6.jpg
        │           pic7.jpg
        │
        └───sections
                _blogContent.scss
                _footer.scss
                _header.scss
                _pinnedSec.scss
                _preBlogs.scss
                _subscription.scss
