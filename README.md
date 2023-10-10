# Problematizing Strategic Tension Lines in the Digital Commons

This reposistory contains the source files for the static site containing the report generated 
during the Digital Commons workshop celebrated in Berlin in May 2023.

For all details check the report site:

https://todo

## Technical details

* The site is build with [Jekyll](https://jekyllrb.com/) (pinned to 3.9.x to avoid build errors). To run it locally you'll need to install Jekyll and its requirements and run `jekyll serve`
* The `src` folder contains the source files and the [Pandoc](https://pandoc.org/) command used to generate the PDF version of the report
* The site is currently hosted in [statichost.eu](https://www.statichost.eu/). This repository has a [custom webhook](https://www.statichost.eu/docs/webhooks/#github) set up to automatically deploy changes when pushing to `main`.

## License

The report itself and the site contents are released under XXXX.

The contents of this repository are release under the MIT license (see LICENSE.txt for details).
