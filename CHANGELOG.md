# Changelog



## 1.7.0
2016-07-13

### Improved
- GPU acceleration for Styleguide nav
- Major CSS moving and juggling and changing

### Updates
- package.json

### Added
- Concat helper for Handlebars
- SVG for Everybody

### Fixed
- ESLint configuration



## 1.6.2
2016-07-03

### Improved
- Styleguide navigation reset

### Updated
- ESLint to v3.0.0

### Fixed
- icons.html removal on html clean task

### Removed
- svg-sprite inline option



## 1.6.1
2016-06-27

## Improved
- Browsersync notification
- Styleguide CSS

### Removed
- border-radius Sass mixin



## 1.6.0
2016-06-26

### Improved
- Outsource Gulp config and paths

### Added
- SVG sprite generation
- ESLint

### Fixed
- Babel and gulp-filter problem

### Removed
- JSHint
- Holder.js



## 1.5.0
2016-06-20

### Improved
- Styleguide article partial position
- Handlebars error logging
- Browsersync notification

### Added
- Babel to the party. Let's use ES6!
- Stricter JSHint config

### Fixed
- Imagemin settings



## 1.4.1
2016-06-16

### Improved
- Component article partial

### Updated
- Documentation for component article



## 1.4.0
2016-06-12

### Improved
- Styleguide menu

### Updated
- jQuery to 3.0.0

### Added
- Partial for component markup



## 1.3.2
2016-07-09

### Improved
- Small CSS changes

### Updated
- Normalize.css

### Fixed
- gulp-hb `file` to `@file`



## 1.3.1
2016-05-26

### Improved
- Error handling for Handlebars
- Switch to relative paths in generated HTML files
- Switch from Assets to Images because all the other stuff like fonts will be loaded from CDNs - there is no need for other assets anymore
- Make Styleguide Nav a bit more beautiful by removing file extension

### Updated
- Dependencies



## 1.2.1
2016-05-18

### Improved
- Highly decrease gulpfile.js complexity



## 1.2.0
2016-05-18

### Updated
- README.md

### Added
- gulp-concat for JavaScript concatenation

### Removed
- gulp-bless since old IE versions aren't supported anymore
- gulp-include (switch to gulp-concat)



## 1.1.0
2016-03-25

### Added
- Holder.js for easy image placeholders
- Forms and Typography example components
- Material Icons credits to README.md



## 1.0.1
2016-03-11

### Improved
- Switch to SVG icons for Styleguide navigation
- Open Browsersync settings in a new tab



## 1.0.0
2016-03-11

### Improved
- Completely overhauled the Styleguide navigation menu

### Updated
- jQuery to 2.2.1
- README.md



## 0.12.3
2016-03-10

### Improved
- Make the Styleguide navigation more awesome (visually)…



## 0.12.2
2016-02-21

### Improved
- Aasset version system has random number



## 0.12.1
2016-02-04

### Removed
- gulp-responsive



## 0.12.0
2016-02-04

### Added
- Bootstrap responsive utilities
- Tried gulp-responsive (not enabled because of a bug)

### Removed
- Unused Sass mixins



## 0.11.5
2016-01-28

### Added
- CSS and JavaScript version number for cache invalidation



## 0.11.4
2016-01-26

### Added
- `box-sizing: border-box` to all Elements… cause Bootstrap requires it and everyone needs it



## 0.11.3
2016-01-21

### Improved
- Styleguide CSS

### Added
- `gulp development` task for one time generation of development files

### Fixed
- Handlebars production task receives correct input files
- Browsersync reloads correctly on Sass change



## 0.11.2
2016-01-16

### Added
- Assets Browsersync reloading

### Fixed
- Splitted CSS generation for IE is now working properly



## 0.11.1
2016-01-11

### Improved
- Some cleaning here, some cleaning there



## 0.11.0
2016-01-10

### Improved
- Styleguide dev menu uses more streamlined CSS

### Added
- Handlebars to HTML compilation now supports subfolders
- Console logging shows which file changed



## 0.10.0
2016-01-08

### Added
- gulp-include for JavaScript concatenation

### Removed
- gulp-concat (switch to gulp-include)



## 0.9.0
2016-01-06

### Improved
- Some general clean up and update

### Added
- gulp-bless



## 0.8.1
2016-01-03

### Improved
- Handlebars error logging

### Added
- gulp-plumber to prevent unpiping



## 0.8.0
2015-12-29

### Added
- gulp-hb/Handlebars template engine

### Removed
- Nunjucks (switch to Handlebars… again)



## 0.7.0
2015-12-20

### Added
- gulp-watch for file/directory watching

### Removed
- watchr (switch to gulp-watch)



## 0.6.0
2015-12-14

### Improved
- Page generation with Nunjucks is feature complete

### Updated
- README.md



## 0.5.0
2015-12-11

### Added
- Nunjucks template engine

### Removed
- Assemble/Handlebars (some core features are still not available)



## 0.4.0
2015-12-8

### Added
- Assemble/Handlebars template engine



## 0.3.0
2016-12-02

### Added
- Browsersync



## 0.2.0
2016-11-29

### Added
- watchr for file/directory watching

### Removed
- gulp.watch
- gulp-watch



## 0.1.0
2016-11-28

The first (almost) working release. Some issues with Gulp's watch remaining (editor's note after 8 months: still not working flaweless :P).