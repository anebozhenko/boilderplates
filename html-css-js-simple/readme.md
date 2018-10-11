# Boilerplate for writing html css(sass) and js

## List of gulp tasks

### Development

Task name          | Description                                                      
:------------------|:----------------------------------
`html:dev`         | trigger livereload if it is active
`css:dev`          | compile sass to css and place it in `./src/css` folder
`js:dev`           | trigger livereload if it is active
`compile:dev`      | run all of the above
`watch:dev`        | watch files in `./src/**/`
`dev`              | run `compile:dev` and `watch:dev`

### Build

Task name          | Description                                                      
:------------------|:----------------------------------
`imagemin`         | minify all the images in `./src/img` and put them in `./build/images`
`fonts`            | put fonts in `./build/fonts`
`html:build`       | put html in `./build`
`css:build`        | autoprefix and minify css, put it in `./build/css`
`js:build`         | use babel and put js in `./build/js`
`build`            | run `compile:dev`, and all the tasks above

### Other tasks

Task name          | Description                                                      
:------------------|:----------------------------------
`default`          | run `dev` task
