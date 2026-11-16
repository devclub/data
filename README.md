# Devclub data

This repository is used as data server. We keep here all data about all 
meetings for [devclub.eu](http://devclub.eu) and [devclub.ee](http://devclub.ee).

Files are accessible by url: https://devclub.github.io/data/${FILENAME_HERE}

For example, https://devclub.github.io/data/eu_conf.json

## Sponsor end dates

Sponsors are configured in the `companies` array in `data_finances.json`, shared by
both sites. An optional `endDate` in `YYYY-MM-DD` format controls the last day a
sponsor's logo is displayed, inclusive, using the visitor's local calendar date.
Omit `endDate`, or set it to `""` or `null`, for a perpetual sponsor.
For example, `"endDate": "2026-12-31"` displays the logo through 31 December 2026.
