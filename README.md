# Walk to Mordor Data

Locations extracted from the Walk to Mordor app.

## What is this?

A few years ago, [Matt Beckett](http://mattbeckett.me/) wrote the Walk to Mordor app.
Unforutnately it's no longer available, and its website no longer exists.
APKs of the app are available, but they require the original API backend, which isn't online anymore.
However, the location, distance, and text data are still within the APK, so I thought I'd extract it in case anyone was interested.

## What are the files?

- `en.json`: the original data strings extracted from the app.
- `nodes.json`: location data, original text, and references collected into one JSON map, keyed by travelled distance in miles.
- `nodes.csv`: the same data as `nodes.json` but in CSV format suitable for importing into a spreadsheet.

## How did you make this?

Long story short: I extracted the strings, did a little Python magic to put everything together, then scraped an edition of LotR [freely available](https://archive.org/details/lordofrings0000tolk_b2r2) on archive.org to get page numbers. The edition used is the Houghton Miffin one-volume edition (ISBN: 0-618-12901-4).

## License

I've no idea what how the original app was licensed, but I'm making the assumption that it is abandonware and the original author doesn't mind me using his data.
If this isn't the case please let me know.
The files in this repo are made available under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.
