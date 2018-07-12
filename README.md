WebCrawler
===================================================

`WebCrawler` is a library to obtain articles related to light pollution.

© 2018 Jorge Galán - OEG-UPM. Available under Apache License 2.0. See [`LICENSE`](LICENSE).

## Features

- Download any article from [ZENODO](https://zenodo.org/) and [DARKSKY](http://alandb.darksky.org/). While Zenodo is a website with a many articles on different topics, is focused on light pollution.
- Get all information of this articles in a JSON, included tittle, author, abstract, authors, keyWords, doi and licence.

## Requirements

- Make sure you have the latest version of the browser [Google Chrome](https://www.google.com/chrome/) browser on your computer.
- You need a persistent internet connection

## Download

Download a version of the WebCrawler's from our [releases page](../../releases), that includes a jar and a exe, which needs to be given permissions on your machine.

## Usage

`WebCrawler` provides a command line application:

```
$java -jar WebCrawler.jar --help 
usage: PDFExtractor [-h] [-i <inputFolder>] [-k <keywords>] [-s
       <sourceWeb>]
Mised argument
 -h,--help                  Indicate how yo use the program.
 -i,--input <inputFolder>   [REQUIRED] Input folder where download the
                            content. Ex: /Users/jesus/aFolder
 -k,--keyword <keywords>    [REQUIRED] Keyword to search the PDF files
 -s,--sources <sourceWeb>   [OPTIONAL] Choose the information source.
                            (ZENODO, DARKSKY, ALL). Default: ALL
```

## Building from Source

Clone this repo and run:

```
mvn clean compile assembly:single
```

Then, get your own version of the jar in the project's `target` folder.

<a title="OEG Laboratory" href="http://www.oeg-upm.net/" target="_blank"><img alt="OEG Laboratory" src="http://stars4all.eu/wp-content/uploads/2016/10/OEG.png" width="220" height="220"></a>
<a title="STARS4ALL" href="http://stars4all.eu" target="_blank"><img alt="STARS4ALL" src="http://linkeddata4.dia.fi.upm.es/wordpress-new/wp-content/uploads/2016/12/logo_dark.png" width="220" height="220"></a>
