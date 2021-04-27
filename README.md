# screenshot-cleanup
A script you can run to clear away your screenshot pileup.

## Technologies
* Bash

## Setup
1. Download or clone remove-screenshots.sh
2. Add executable permissions:
`chmod +x remove-screenshots.sh`

Ready to use!

## How to Use
1. Open Terminal
2. Navigate to directory where you have remove-screenshots.sh
3. Run the file in your terminal:
`./remove-screenshots.sh`

This will _permanently_ remove all files from your Desktop directory with 'Screen' in the file name. It does not remove screenshots that have been renamed. 

If you have screenshots in Desktop you want to keep, move them or rename them. 

## Assumptions/Prerequisites
That this file is in a parallel directory to Desktop. It goes 'up' one directory then 'down' one to Desktop. You may need to edit the file path if you organize differently. 

## Issues
None known but see 'Assumptions/Prerequisites' above. A possible next iteration might be to set this to run daily/weekly or at some interval. 
