# Trace ETDMS Schema Overview

---

## About

This report is from August 5, 2016.  There are at least a few UTF-8 issues that need to be addressed still, so this doesn't include all objects.

## Schema Overview

| key                                          | types                                | occurrences | percents               |
| -------------------------------------------- | ------------------------------------ | ----------- | ---------------------- |
| _id                                          | ObjectId                             |       31357 | 100.000000000000000000 |
| metadata                                     | Object                               |       31357 | 100.000000000000000000 |
| metadata.thesis                              | Object                               |       31357 | 100.000000000000000000 |
| metadata.thesis.@xmlns                       | String                               |       31357 | 100.000000000000000000 |
| metadata.thesis.@xmlns:xsi                   | String                               |       31357 | 100.000000000000000000 |
| metadata.thesis.@xsi:schemaLocation          | String                               |       31357 | 100.000000000000000000 |
| metadata.thesis.title                        | String                               |       31357 | 100.000000000000000000 |
| oai_provider                                 | String                               |       31357 | 100.000000000000000000 |
| record_id                                    | String                               |       31357 | 100.000000000000000000 |
| metadata.thesis.identifier                   | String (31078),Array (123)           |       31201 |  99.502503428261633189 |
| metadata.thesis.dateDOTcreated               | String                               |       28254 |  90.104282935229775831 |
| metadata.thesis.subject                      | Array (11918),String (11042)         |       22960 |  73.221290302005925810 |
| metadata.thesis.creator                      | String (20348),Array (2599)          |       22947 |  73.179832254361073751 |
| metadata.thesis.type                         | String (20405),null (77)             |       20482 |  65.318748604777240985 |
| metadata.thesis.descriptionDOTabstract       | String (13071),null (27)             |       13098 |  41.770577542494500278 |
| metadata.thesis.contributor                  | Array (7615),String (1440),null (26) |        9081 |  28.960040820231526482 |
| metadata.thesis.thesisDOTdegreeDOTdiscipline | String                               |        8089 |  25.796472876869597002 |
| metadata.thesis.thesisDOTdegreeDOTlevel      | String                               |        7508 |  23.943617055202985000 |
| metadata.thesis.thesisDOTdegreeDOTname       | String                               |        7498 |  23.911726249322320825 |
| metadata.thesis.description                  | String (5371),Array (65),null (1)    |        5437 |  17.339031157317347009 |
| metadata.thesis.dateDOTavailable             | String                               |         466 |   1.486111554038970661 |
| metadata.thesis.rights                       | String                               |         222 |   0.707975890550754272 |
| metadata.thesis.descriptionDOTnote           | String (186),null (6)                |         192 |   0.612303472908760416 |
| metadata.thesis.coverageDOTspatial           | String                               |          55 |   0.175399432343655320 |
| metadata.thesis.publisher                    | String                               |          55 |   0.175399432343655320 |
| metadata.thesis.rightsDOTlicense             | String                               |          13 |   0.041458047644863986 |
| metadata.thesis.coverageDOTspatialDOTlat     | String                               |           4 |   0.012756322352265842 |
| metadata.thesis.coverageDOTspatialDOTlong    | String                               |           4 |   0.012756322352265842 |


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



