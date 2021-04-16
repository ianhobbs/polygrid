# README #

This is my first grid solution called polygrid.
It's a 12 col asymetric grid using ratio 1.414 for % based columns
This is now depreciated and maintained for legacy projects.
Influenced by Susy SASS

This remains as a implementation of modular scale.

Much of the modualr scale work is better implemented in 
https://utopia.fyi/

Whats good about Utopia? Implementing css --vars integrates well with js injection.

Utopia is missing a grid though so expect a merge of this Utopia's of implementaion of modular scale with
some bits of this grid in a related repo. Polygrid-6

## What is this repository for? ##

Initially developed as a universal scaling grid project.
Developed for cementa initally and versioned in a number of projects 2019 and 20120.


* Version 1.0
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

## How do I get set up? ##

Just chuck it in.

*  * Description

- 12 col responsive asymetric grid using ratio (1.414°) for % based columns
- 18 classes 
- see live demo at https://ianhobbsmedia.com.au/style.php
- version 2 removes the pesky header and rows


* Dependencies

1 Codekit application.
2 Modular scale
3 Config

*  *  *  Config

* Summary of set up

Use codekit frameworks to pull a copy into the project.
Codekit frameworks use a flat file reference.

so to import do

`@import polygrid.sass`

* Configuration

## Dependencies##

Import Modularscale

`npm i modularscale`

##Import Polygrid SASS##

@import polygrid.sass