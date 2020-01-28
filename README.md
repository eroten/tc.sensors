# tc.sensors
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com)

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues) [![HitCount](http://hits.dwyl.io/sullivannicole/tcsensors.svg)](http://hits.dwyl.io/sullivannicole/tcsensors) [![Website MnDOT JSON](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](http://data.dot.state.mn.us:8080/trafdat/metro/2018/20181021/5474.c30.json)

<!-- badges: start --> 
<!---- use_badge(Maturing)
<!-- badges: end -->

## Overview
A package for pulling data for Minnesota Department of Transportation (MnDOT) loop detectors installed on the Minnesota Freeway system in 30-second interval measurements of occupancy and volume, data which are pushed daily to a public JSON feed.

## Installation

To use this package, clone this repo (that just means "download all the files locally").  To install the package, you'll first need the devtools library installed, if you don't have it already.  Run `install.packages("devtools")` to do so.  Then attach the devtools package using `library(devtools)`.  Last, run `build("~/package/path/here")`, the path being the where you downloaded/saved your local copy of tc.sensors.  To access documentation and for help on how to use the package, run `?<FUNCTION-NAME>` (e.g. `?pull_sensor`, `?pull_configuration`, `?pull_sensor_ids`).

## Contributor/Maintainer
* Nicole Sullivan (nicole.sullivan@metc.state.mn.us)
