# knit-pattern-generator
A tool for creating knitting patterns to create guides

Generates an image with numbered rows and columns in which knit symbols can be inserted to visualize a knitting pattern.
I haven't found a free one or some tool that just did the job right, so here is a simple one i made some years ago.
Its originally written in German but i translated it as best as i could without specialized vocabulary.

## Features
* Grid arrangement with numbers up to three digits
* Rows can be optionally just odd numbered
* Simple colors as background
* Very simple way of saving and loading in the browser as a temporary storage
* All commonly used symbols plus multi column braids
* A hidden description of the symbols (likely with translation errors but you get the gist)
* Fully offline & standalone usable (only fonts may change)
* Export the final pattern by right click -> save image as
* Tested in Chrome 101 & FF 100 (fixed CORS errors)
* Free as in MIT license

## Bugs / Improvements
* Braids don't have corner boundary checks
* Black background might not be very useful / contrast issues
* Saving the raw image is a bit crude - maybe a json data format would be a better choice but that was quick
* It can be done without jQuery with some care

## Preview / Example:
![image](https://user-images.githubusercontent.com/19379091/168412772-b6d2a707-99be-4162-b364-9c9806dff1b7.png)
## Symbols used:
![image](https://user-images.githubusercontent.com/19379091/168414151-c8214ff8-5073-40d5-9c87-eb26bc9398cb.png)
