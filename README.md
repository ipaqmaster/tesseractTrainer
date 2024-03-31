# tesseractTrainer

## About

This is a bash script for quickly training a new .traineddata for any given font.ttf file when given a text file of lines to generate and train against.

## Usage

The script accepts a few arguments:

* `-font` (Required)

A ttf file to train for.

`-traininglines` (Default: `traininglines.txt`)

A text file with lines of text for tif and txt generation for training.

`-fontsize` (Default: `15`)

An optional desired font size for generating .tif's.

`--`

An optional flag to pass arguments through to tesstrain (e.g., `-- MAX_ITERATIONS=1000000 TARGET_ERROR_RATE=0.001`)

