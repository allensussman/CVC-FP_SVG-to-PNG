# SVG to PNG converter

Converts the SVG files in the [CVC-FP dataset](http://dag.cvc.uab.es/resources/floorplans/) to PNG files.

This is the CVC-FP dataset's [SVG to PNG converter](http://dag.cvc.uab.es/DATASETS/SVGtoPNG.7z) that was provided by the dataset's authors.  I made a few bug fixes.

## Table of Contents

- [SVG to PNG converter](#svg-to-png-converter)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contact](#contact)

## Installation

From the root directory, run the following command to compile the program:

`javac program/SVG2PNG.java IO/SVGReader.java StructuralElements/myImage.java StructuralElements/StructuralElement.java`

## Usage

1. Download the [CVC-FP dataset](http://dag.cvc.uab.es/DATASETS/CVC-FP.zip).  
2. Place the SVG files in an `svgImages` directory in the root directory of the project.  
3. Place the other files in an `originalImages` directory in the root directory.
4. Run the following command from the root directory to convert the SVG files to PNG files:

`java program.SVG2PNG`

## Contact

allen.sussman@gmail.com
