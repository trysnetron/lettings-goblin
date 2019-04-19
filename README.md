# lettings-goblin
Application for extracting lettings from finn.no/hybel.no and append relevant data to a Google Sheets document.

## How to make it work

1. Load current list of lettings from Sheets
2. Load all lettings from finn and hybel
3. Compare scraped lettings to existing list, add new lettings and mark expired lettings in Sheets.

## App must be able to...

- Get list of lettings from both finn and hybel
- Get data from each letting, both finn and hybel
- Read rows from Google Sheets document
- Write rows to Google Sheets document
- Update rows in Google Sheets document
- Load Sheets URL from config file

## What data do we need from the lettings?

- Price
- Bedrooms
- Location
- Is electricity included?
- Is internet included?
- Is furniture included?

The last three in the list is probably easiser to add manually.

## App is finished when it can

- [ ] Scrape lettings from finn.no
- [ ] Scrape data from finn.no letting
- [ ] Scrape lettings from hybel.no
- [ ] Scrape data from hybel.no letting
- [ ] Read existing lettings from Sheets
- [ ] Identify removed lettings on finn.no
- [ ] Identify removed lettings on hybel.no
- [ ] Update removed lettings in Sheets
- [ ] Add new lettings to Sheets
- [ ] Update changed lettings in Sheets
