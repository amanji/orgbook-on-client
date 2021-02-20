[![img](https://img.shields.io/badge/Lifecycle-Experimental-339999)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)

# Orgbook ON Client

## Overview

This application implements a user interface (built with Angular) specifically for Orgbook ON, an extension of Aries VCR, for registered organizations within the Province of Ontario.

## Running 

Running the web application in development mode can be done simply with the Angular CLI installed. Just run:

``` 
npm install
``` 

and

``` 
ng serve
```

## Development

With the application running, you can develop against any running Aries VCR instance by configuring the `API_URL` setting in `./src/assets/config.json`. The configuration is not set to point to any specific instance of Aries VCR by default, however you can change this setting at anytime, even while the application is running.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).