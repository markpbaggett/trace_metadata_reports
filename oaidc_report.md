# Trace OAI_DC Schema Overview

---

## About

This report is from July 28, 2016.  There are at least a few UTF-8 issues that need to be addressed still, so this doesn't include all objects.

## Schema Overview

| key                                    | types                        | occurrences | percents             |
| -------------------------------------- | ---------------------------- | ----------- | -------------------- |
| _id                                    | ObjectId                     |       31240 | 100.0000000000000000 |
| metadata                               | Object                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc                     | Object                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.@xmlns:dc           | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.@xmlns:oai_dc       | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.@xmlns:xsi          | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.@xsi:schemaLocation | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:date             | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:identifier       | Array (29833),String (1407)  |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:publisher        | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:source           | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:title            | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:type             | String                       |       31240 | 100.0000000000000000 |
| oai_provider                           | String                       |       31240 | 100.0000000000000000 |
| record_id                              | String                       |       31240 | 100.0000000000000000 |
| metadata.oai_dc:dc.dc:format           | String                       |       29270 |  93.6939820742637579 |
| metadata.oai_dc:dc.dc:subject          | Array (11867),String (11001) |       22868 |  73.2010243277848929 |
| metadata.oai_dc:dc.dc:creator          | String (20237),Array (2593)  |       22830 |  73.0793854033290700 |
| metadata.oai_dc:dc.dc:description      | String (12339),Array (796)   |       13135 |  42.0454545454545467 |
| metadata.oai_dc:dc.dc:rights           | String                       |         235 |   0.7522407170294494 |

## What Is This Field

See below for distinct values associated with a particular field. If a field's value is truly unique, it will not be included.

* [Publiser](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oai_dc/publisher.md)
* [Source](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oai_dc/source.md)
* [Type](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oai_dc/type.md)
* [Format](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oai_dc/format.md)
* [Rights](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oai_dc/rights.md)




