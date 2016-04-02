# amchartsJava

This repository is the repository central of the amchartsJava project. amchartsJava is the app developed as my Degree Final Work to "Grado de Ingeniería Informática" in University of Vigo.

amchartsJava born as support to [BEW](https://github.com/sing-group/BEW) but changed to an independent library. My intention is that
can be used in every java project as a project library.

amchartsJava is more than an API to use [AmCharts JavaScript Charts](https://www.amcharts.com/) in Java, transform amcharts API in an API more oriented to objects Java, also offer a set of validators to validate users entries and generate correct json to be used by amcharts library. Advanced users can use this library in its totality, future release will include a module to can visualize in your app the chart generated by amchartsJava using [JCEF](https://bitbucket.org/chromiumembedded/java-cef).

## Modules

This project is comprised of the following modules:

* [amchartsJava-core](https://github.com/ifcunharro/amchartsJava-core): Contains core functionality of amchartsJava
* [amchartsJava-export](https://github.com/ifcunharro/amchartsJava-export): Contains functionality to export to html chart generated by core.
* amchartsJava-jcef: Contains basic functionality to load chart generated into desktop app using JCEF. Future release.

## Dependencies
amchartsJava needs amcharts to be used. Only support version 3.15.1 of AmCharts JavaScript Charts. Can be downloaded of its github:
* [amcharts version 3.15.1](https://github.com/amcharts/amcharts3/releases/tag/3.15.1)

Once downloaded, unzip and rename folder to amcharts of manner that have the following tree directory:
* amcharts/amcharts
* amcharts/images
* amcharts/samples
* amcharts/temp: this folder doesn't exist, create it.

