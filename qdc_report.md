# Trace QDC Schema Overview

---

## About

This report is from July 29, 2016.

## Schema Overview

| key                                          | types                                | occurrences | percents               |
| -------------------------------------------- | ------------------------------------ | ----------- | ---------------------- |
| _id                                          | ObjectId                             |       31244 | 100.000000000000000000 |
| metadata                                     | Object                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc                           | Object                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.@xmlns:dc                 | String                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.@xmlns:oai_dc             | String                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.@xmlns:xsi                | String                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.@xsi:schemaLocation       | String                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.dc:title                  | String                               |       31244 | 100.000000000000000000 |
| oai_provider                                 | String                               |       31244 | 100.000000000000000000 |
| record_id                                    | String                               |       31244 | 100.000000000000000000 |
| metadata.oai_dc:dc.dc:identifier             | String (30965),Array (123)           |       31088 |  99.500704135193956290 |
| metadata.oai_dc:dc.dc:datecreated            | String                               |       28143 |  90.074894379720902293 |
| metadata.oai_dc:dc.dc:subject                | Array (11836),String (11017)         |       22853 |  73.143643579567282131 |
| metadata.oai_dc:dc.dc:creator                | String (20240),Array (2594)          |       22834 |  73.082831903725519851 |
| metadata.oai_dc:dc.dc:type                   | String (20396),null (77)             |       20473 |  65.526181026757143400 |
| metadata.oai_dc:dc.dc:descriptionabstract    | String (12963),null (27)             |       12990 |  41.575982588657019789 |
| metadata.oai_dc:dc.dc:contributor            | Array (7511),String (1440),null (26) |        8977 |  28.731916527973371700 |
| metadata.oai_dc:dc.dc:thesisdegreediscipline | String                               |        7985 |  25.556906926129816071 |
| metadata.oai_dc:dc.dc:thesisdegreelevel      | String                               |        7404 |  23.697349891179104731 |
| metadata.oai_dc:dc.dc:thesisdegreename       | String                               |        7394 |  23.665343745999230407 |
| metadata.oai_dc:dc.dc:description            | String (5370),Array (65),null (1)    |        5436 |  17.398540519779796654 |
| metadata.oai_dc:dc.dc:dateavailable          | String                               |         466 |   1.491486365382153290 |
| metadata.oai_dc:dc.dc:rights                 | String                               |         222 |   0.710536422993214734 |
| metadata.oai_dc:dc.dc:descriptionnote        | String (184),null (6)                |         190 |   0.608116758417616143 |
| metadata.oai_dc:dc.dc:coveragespatial        | String                               |          55 |   0.176033798489309945 |
| metadata.oai_dc:dc.dc:publisher              | String                               |          55 |   0.176033798489309945 |
| metadata.oai_dc:dc.dc:rightslicense          | String                               |          13 |   0.041607988733836899 |
| metadata.oai_dc:dc.dc:coveragespatiallat     | String                               |           4 |   0.012802458071949815 |
| metadata.oai_dc:dc.dc:coveragespatiallong    | String                               |           4 |   0.012802458071949815 |


## Understanding This Field

This section lists the distinct fields here:

* [Rights](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/rights.md)
* [Rightslicense](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/rightslicense.md)
* [coveragespatial](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/coveragespatial.md)
* [coveragespatiallat](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/coveragespatiallat.md)
* [coveragespatiallong](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/coveragespatiallong.md)
* [publisher](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/publisher.md)
* [descriptionnote](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/descriptionnote.md)
* [dateavailable](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/dateavailable.md)
* [thesisdegreename](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/thesisdegreename.md)
* [thesisdegreelevel](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/thesisdegreelevel.md)
* [thesisdegreediscipline](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/thesisdegreediscipline.md)
* [contributor](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/contributor.md)
* [type](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/type.md)
* [description](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_files/description.md)