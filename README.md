# Superglutamic
***adjective.***

1. supercooled so that it no longer obscures photographic or video images
*"the superglutamic photos"*
2. a word that does not exist; it was invented, defined and used by a machine learning algorithm. 

Superglutamic is a small front end for generating complex ffmpeg crop and blur commands.

Trying to understand advanced ffmpeg filter chaining makes my head spin. I wrote a quick and dirty front end to do the hard work of writing the commands. This is intended to be a single, portable file that does just a few things well:

- Load an mp4 file that will be edited by ffmpeg
- Visually define a single crop zone
- Visually define various blur regions
- Provide a shaded mode to reduce eye strain or add privacy when in a public space
- Generate and chain the necessary ffmpeg commands to crop and blur video regions

## Things Superglutamic is NOT and never will be

- A full-fledged video editing suite
- A video converter

## Prerequisites

- A working ffmpeg binary (I don't provide one or help you install it)
- A knowledge of your file system and how to edit the commands generated to reference correct paths
