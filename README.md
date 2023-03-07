# Python Meme Generator
## Introduction
This is a Meme-Generator for Python, using PIL (with FreeType). It can put captions at the top and the bottom of images.

This fork specifically hands back a PIL Image with the changes made so the caller can do what they'd like with it.

## Requirements
To use the Meme Generator, you have to have Python (duh!) and PIL (Python Image Library) with working FreeType.

## Command-Line Usage

Command-Line usage has been removed from this fork.

## API Usage

Use memegenerator as an imported library. The memegenerator module has a single top-level method, `make_meme(topString, bottomString, filename)`. The first two arguments specify the text which will appear on the image. The final argument is the full filename to the source image to be used. A PIL Image object is returned to the caller. If no text is required for the top (or bottom), pass in the empty string.

## Notes

Feel free to use, fork and improve, and send me Pull Requests if you think you really got something great that should be included here. Consider forking the original instead of this fork.
