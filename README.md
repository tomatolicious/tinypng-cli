# TinyPNG CLI

> Handy command line tool for shrinking PNG images using the TinyPNG API

## Installation

	npm install -g tinypng-cli

## Preamble

To use TinyPNG CLI, you need an API key for TinyPNG. You can get one at [https://tinypng.com/developers](https://tinypng.com/developers).

## Usage

TinyPNG CLI allows you to provide your API key in two different ways. The more convenient one is to save the API key into a file called `.tinypng` within your home directory. The other way is to provide it as an option while running the CLI.

	tinypng demo.png -k E99a18c4f8cb3EL5f2l08u368_922e03

To shrink all PNG images within the current directory and its subdirectories, you may run one of the following commands—both do exactly the same.

	tinypng
	tinypng .

***
	
To shrink all PNG images within a specific directory (`assets/img` in this example) and its subdirectories, you may run the following command.

	tinypng assets/img

You may also provide multiple directories.

	tinypng assets/img1 assets/img2
	
***
	
To shrink a single PNG image (`assets/img/demo.png` in this example), you may run the following command.

	tinypng assets/img/demo.png

You may also provide multiple single PNG images.

	tinypng assets/img/demo1.png assets/img/demo2.png

That's it. Pretty easy, huh?

## Changelog

* 0.0.2
	* JP(E)G support
* 0.0.1
	* Initial version

## TODO

- Documentation
- Tests

## License

Copyright (c) 2014 [websperts](http://websperts.com/)  
Licensed under the MIT license.

See LICENSE for more info.

## Contributors

- [@rasshofer](https://github.com/rasshofer)
- [@maxkueng](https://github.com/maxkueng)
- [@tholu](https://github.com/tholu)
