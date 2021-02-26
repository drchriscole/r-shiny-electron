# R shiny and electron

This is a work in progress template for R shiny and electron integration

_NOT FOR PRODUCTION_

## To fix

The `add-cran-binary-pkgs.R` has an unsatisfied dependency itself. Fix to not use it or do something different.


## Quickstart

* Clone
* `npm install`
* Download mac binaries `./get-r-mac.sh`
* FIXME - manually install the 'automagic' library within the `r-mac/R` install.
* Download shiny `Rscript add-cran-binary-pkgs.R`
* `npm start`
* Build a package with `npm run package`

## Contribute

If you like to contribute, please take a look at the issues. It is all work in progress and early stage but ideas and code is always welcome. Ideally please make an issue before you send a larger PR.

## App

The app currently starts with a loading screen while trying to start the shiny app as a seperate process. If successful, it will switch to the shiny app once it is loaded. If not successful after 3 trys and error is shown.

Loading:
![loading](docs/screenshot-loading.png)

App:
![app](docs/screenshot-app.png)


## References

* The initial javascript template is based on the template from `electron-forge`
* This project is inspired by the work of [@ksasso](https://github.com/ksasso/useR_electron_meet_shiny)
