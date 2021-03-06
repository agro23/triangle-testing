(work-in-progress)

# npm-webpack installer

Originally, I was hoping to be able to have this script be able to create and update all necessary files and folders, but ran into a few roadblocks.

For now, this script will install all the important and relevant plugins, scripts, and dependencies necessary so far.

These include:

- create package.json
- dependency: webpack development dependency
- dependency: allow webpack use from command line (CLI - command line interface)
- dependency: jquery
- dependency: popper
- dependency: bootstrap
- dependency: styles.css
- dependency (plugin): webpack plugin
- dependency (plugin): webpack declutterer
- dependency (plugin): uglify
- dependency (plugin): webpack development server
- dependency (linter): eslint
- dependenct (linter): eslint loader

- jasmine node module
- jasmine helper package
- initialize jasmine


### YOU MUST MANUALLY UPDATE PACKAGE.JSON!
   "scripts": {
     "test": "jasmine"
    }

- karma test-runner
- integrate jasmine and karma
- specify chrome browser
- karma cli
- karma webpack integration
- karma jquery integration
- karma testing reporter
# initialize karma

### MANUALLY UPDATE PACKAGE.JSON
```
  "scripts": {
    "test": "karma start karma.conf.js"
    },
```
### MANUALLY UPDATE WEBPACK.CONFIG.JS
```
{
  test: /\.js$/,
  exclude: [
    /node_modules/,
    /spec/
    ],
  loader: "eslint-loader"
}
```


## Instructions

**Clone**
```
$ cd Desktop
$ git clone https://github.com/ryee926/npm-webpacker
```


**Run Script**
```
$ cd npm-webpacker/
$ ruby launch.rb
```

## Current Bugs
- currently unable to update the script portion of package.json
- does not fully update the webpack.config.js file
- these must be manually updated.

## Contact
If you have any questions or anything lmk.

Goodnight!
