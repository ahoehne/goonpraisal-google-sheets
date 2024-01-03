# goonpraisal-google-sheets
Goonpraisal helper functions intended for use in Google sheets

## Install

1. Open a google sheets document
2. Go to Extensions > Apps Script...
3. Replace the contents of the file with the contents of [Goonpraisal.gs](https://raw.githubusercontent.com/ahoehne/goonpraisal-google-sheets/master/Goonpraisal.gs)
4. Save the file (enter in a project name, this doesn't really matter)
5. Try some of the examples below


## Examples
```
// Get the total buy price for an existing appraisal
=EVEPRAISAL_TOTAL("gp5av"; "buy")

// Get the cost of a single unit of tritanium in jita
=EVEPRAISAL_ITEM(34; "jita"; "sell"; "volume")
=EVEPRAISAL_ITEM(34; "jita"; "sell"; "min")
=EVEPRAISAL_ITEM(34; "jita"; "sell"; "avg")

```
Credits:
This is an Fork of https://github.com/evepraisal/evepraisal-google-sheets by Kevin McDonald
