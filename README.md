# Welcome to MLS Data

MLS data is an open-source repository of MLS data. It is a combination of original data from contributors and automatic extraction from sites like fantasy.mlssoccer.com and Wikipedia.

Data is provided in CSV and JSON format and is largely denormalized for ease of use.

## Why MLS Data?
MLS is one of the fastest growing sports leagues in the world, but there is no simple-to-use and open repository for the enormous amounts of data it generates to reside.

In addition to general interest, <a href="http://fantasy.mlssoccer.com">MLS Fantasy</a> is a popular and complex strategy game. This data is designed to be useful for players.

## Getting started

There are two datasets availablue under the automated import:
* **Teams** - a CSV, sourced from MLS fantasy, of all of the teams
* **Players** - a CSV, sourced from MLS fantasy, of all of the players and their current status

## Roadmap

MLS Data is in development and there will be likely be sweeping changes over time. However, my (<a href="https://github.com/coffenbacher/">@coffenbacher</a>) general approach is to work on three tiers of projects:

* **Data persistence** - The open repository <a href="https://github.com/coffenbacher/mls-data">https://github.com/coffenbacher/mls-data</a>  will serve as the repository for acquired data. Github allows the data to be discoverable, natively versioned, and CDN hosted for hotlinking using <a href="http://rawgit.com/">http://rawgit.com/</a>.

* **Data acquisition** - Multiple open- and closed-source projects by both myself and others will automatically contribute data to the the cfb-data repository. Data can be either committed directly by approved projects or provided via pull request.

* **Data client** - Client libraries in various popular languages to access the data and make usage clean.

* **Data visualization** - Closed-source visualization projects, like blogs and websites, are welcome to use the data. Of course, open-source projects are welcome too, but I expect most users at this tier will be doing closed analyses.

## Contributing

This is very much a work in progress - please contact me at <a href="mailto:charles.offenbacher@gmail.com">charles.offenbacher@gmail.com</a> to discuss collaborating. I'd love to have help!

## Related projects

* **CFB Data** - The equivalent repository <a href="https://github.com/coffenbacher/cfb-data">https://github.com/coffenbacher/cfb-data</a> for College Football (American).