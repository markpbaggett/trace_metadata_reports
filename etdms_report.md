# Trace ETDMS Schema Overview

---

## About

This report is from July 27, 2016.  There are at least a few UTF-8 issues that need to be addressed still, so this doesn't include all objects.

## Schema Overview

| key                                    | types                                | occurrences | percents               |
| -------------------------------------- | ------------------------------------ | ----------- | ---------------------- |
| _id                                    | ObjectId                             |       31200 | 100.000000000000000000 |
| metadata                               | Object                               |       31200 | 100.000000000000000000 |
| metadata.thesis                        | Object                               |       31200 | 100.000000000000000000 |
| metadata.thesis.@xmlns                 | String                               |       31200 | 100.000000000000000000 |
| metadata.thesis.@xmlns:xsi             | String                               |       31200 | 100.000000000000000000 |
| metadata.thesis.@xsi:schemaLocation    | String                               |       31200 | 100.000000000000000000 |
| metadata.thesis.title                  | String                               |       31200 | 100.000000000000000000 |
| oai_provider                           | String                               |       31200 | 100.000000000000000000 |
| record_id                              | String                               |       31200 | 100.000000000000000000 |
| metadata.thesis.identifier             | String (30921),Array (123)           |       31044 |  99.500000000000000000 |
| metadata.thesis.datecreated            | String                               |       28100 |  90.064102564102569204 |
| metadata.thesis.subject                | String (10989),Array (11835)         |       22824 |  73.153846153846160405 |
| metadata.thesis.creator                | String (20209),Array (2593)          |       22802 |  73.083333333333328596 |
| metadata.thesis.type                   | String (20373),null (77)             |       20450 |  65.544871794871795601 |
| metadata.thesis.descriptionabstract    | String (12941),null (27)             |       12968 |  41.564102564102562098 |
| metadata.thesis.contributor            | Array (7490),String (1440),null (26) |        8956 |  28.705128205128204399 |
| metadata.thesis.thesisdegreediscipline | String                               |        7964 |  25.525641025641025550 |
| metadata.thesis.thesisdegreelevel      | String                               |        7383 |  23.663461538461540101 |
| metadata.thesis.thesisdegreename       | String                               |        7373 |  23.631410256410255499 |
| metadata.thesis.description            | String (5370),Array (65),null (1)    |        5436 |  17.423076923076923350 |
| metadata.thesis.dateavailable          | String                               |         466 |   1.493589743589743613 |
| metadata.thesis.rights                 | String                               |         222 |   0.711538461538461564 |
| metadata.thesis.descriptionnote        | String (184),null (6)                |         190 |   0.608974358974358920 |
| metadata.thesis.coveragespatial        | String                               |          55 |   0.176282051282051294 |
| metadata.thesis.publisher              | String                               |          55 |   0.176282051282051294 |
| metadata.thesis.rightslicense          | String                               |          13 |   0.041666666666666664 |
| metadata.thesis.coveragespatiallat     | String                               |           4 |   0.012820512820512820 |
| metadata.thesis.coveragespatiallong    | String                               |           4 |   0.012820512820512820 |

## Understanding This Field

This section lists the distinct fields here:

* [Descriptionnote](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/description_note.md)
* [CoverageSpatiallat](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/coveragespatiallat.md)
* [CoverageSpatiallong](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/coveragespatiallong.md)
* [Rightslicense](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/rightslicense.md)
* [Publisher](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/publisher.md)
* [Coveragespatial](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/coveragespatial.md)
* [Rights](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/rights.md)
* [Dateavailable](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/dateavailable.md)
* [Thesisdegreediscipline](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/thesisdegreediscipline.md)
* [Thesisdegreename](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/thesisdegreename.md)
* [Thesisdegreelevel](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/thesisdegreelevel.md)
* [Contributor](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/contributor.md)
* [Type](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_support_files/type.md)


## Potential Problems or Bad Metadata

This section just mentions weird stuff we find that we may want to address.

### Thesisdegreediscipline == "<-- Please Select Major -->"

1.[Increasing Attendance in the National Premier & Women's Premier Soccer League](http://trace.tennessee.edu/utk_chanhonoproj/1848)
2.[How is the Stock Market Like Stephen Curry?](http://trace.tennessee.edu/utk_chanhonoproj/1940)



