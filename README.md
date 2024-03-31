# tesseractTrainer

## About

This is a bash script for quickly training a new .traineddata for any font.ttf file.

## Usage

The script accepts a few arguments: `-font` `-traininglines` `-fontsize`.

There is a default fontsize of `15` and it assumes the traininglines is `./traininglines.txt`.

The traininglines should contains lines the script should generate training .tif's for (And .txt files accompanying them)

The script will then generate tifs and txt files transcribing them in a ground-truth directory for your chosen font and will begin training with tesstrain immediately.
