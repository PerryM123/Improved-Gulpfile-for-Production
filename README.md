# Improved Gulpfile for Production

My previous gulpfile.js had a lot of problems and bottle necks when used so I finished making improvement to solve those issues.

# Installation

```sh
npm install
```

# Running

```sh
gulp browsersync
```

# Watcher

```sh
gulp watch
```

# Prepare Code for Production

```sh
gulp release-time
```

# Remaining Gulp Tasks

* gulp-sass: Convert scss to css
* gulp-uglify: Minify JS files
* gulp-cssnano: Minify css files
* gulp-imagemin: Compress images (doesn't always seems to compress at times...)
* gulp-autoprefixer: Auto prefixes css
* fonts-copy + html-copy + sass-copy: Send font, SCSS, and HTML files over to dist folder
* browser-sync: run browsersync allowing for auto-broswer-refreshing
* release-time: Prepare production files in the dist folder

# Please Note

Be sure to change the directories to fit your project