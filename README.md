# google-image-scraper
This script pulls URLs from a given set of google queries, making them easy to download with wget.

## Setup
1. Clone the files and run `npm install` to install all dependencies.
2. Take some time to fill out scraper-config.js before running the script.

## Use
1. Run `npm start`.
2. Once the URL collection has been created, go to the results folder.
3. From the results folder, run `wget -i TEXT_FILE.txt -P OUTPUT_DIRECTORY` to download images to the OUTPUT_DIRECTORY.

Check js files for comments if you need clarification.
