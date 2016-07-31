# Trace Data Dump - utk_gradthes Schema Overview

## About

This report is from July 30, 2016.  It describes all fields from the utk_gradthese set only.

## Schema Overview

| key                                                       | types                      | occurrences | percents              |
| --------------------------------------------------------- | -------------------------- | ----------- | --------------------- |
| _id                                                       | ObjectId                   |        3579 | 100.00000000000000000 |
| metadata                                                  | Object                     |        3579 | 100.00000000000000000 |
| metadata.document                                         | Object                     |        3579 | 100.00000000000000000 |
| metadata.document.articleid                               | String                     |        3579 | 100.00000000000000000 |
| metadata.document.authors                                 | Object                     |        3579 | 100.00000000000000000 |
| metadata.document.authors.author                          | Object (3578),Array (1)    |        3579 | 100.00000000000000000 |
| metadata.document.context-key                             | String                     |        3579 | 100.00000000000000000 |
| metadata.document.coverpage-url                           | String                     |        3579 | 100.00000000000000000 |
| metadata.document.document-type                           | String                     |        3579 | 100.00000000000000000 |
| metadata.document.fields                                  | Object                     |        3579 | 100.00000000000000000 |
| metadata.document.fields.field                            | Array                      |        3579 | 100.00000000000000000 |
| metadata.document.fields.field.XX.@name                   | String                     |        3579 | 100.00000000000000000 |
| metadata.document.fields.field.XX.@type                   | String                     |        3579 | 100.00000000000000000 |
| metadata.document.fields.field.XX.value                   | String (3579),Array (3435) |        3579 | 100.00000000000000000 |
| metadata.document.label                                   | String                     |        3579 | 100.00000000000000000 |
| metadata.document.publication-date                        | String                     |        3579 | 100.00000000000000000 |
| metadata.document.publication-title                       | String                     |        3579 | 100.00000000000000000 |
| metadata.document.submission-date                         | String                     |        3579 | 100.00000000000000000 |
| metadata.document.submission-path                         | String                     |        3579 | 100.00000000000000000 |
| metadata.document.title                                   | String                     |        3579 | 100.00000000000000000 |
| metadata.document.type                                    | String                     |        3579 | 100.00000000000000000 |
| record_id                                                 | String                     |        3579 | 100.00000000000000000 |
| metadata.document.authors.author.lname                    | String                     |        3578 |  99.97205923442302833 |
| metadata.document.authors.author.fname                    | String                     |        3577 |  99.94411846884604245 |
| metadata.document.abstract                                | String                     |        3563 |  99.55294775076836800 |
| metadata.document.fields.field.XX.@list                   | String                     |        3507 |  97.98826487845767019 |
| metadata.document.disciplines                             | Object                     |        3452 |  96.45152277172394406 |
| metadata.document.disciplines.discipline                  | String (2716),Array (736)  |        3452 |  96.45152277172394406 |
| metadata.document.fulltext-url                            | String                     |        3175 |  88.71193070690137006 |
| metadata.document.authors.author.institution              | String                     |        2890 |  80.74881251746298005 |
| metadata.document.authors.author.mname                    | String                     |        2539 |  70.94160379994411869 |
| metadata.document.authors.author.email                    | String                     |        1517 |  42.38614138027381983 |
| metadata.document.keywords                                | Object                     |        1454 |  40.62587314892427770 |
| metadata.document.keywords.keyword                        | Array (1396),String (58)   |        1454 |  40.62587314892427770 |
| metadata.document.native-url                              | String                     |         873 |  24.39228834870075602 |
| metadata.document.supplemental-files                      | Object                     |          85 |   2.37496507404302859 |
| metadata.document.supplemental-files.file                 | Array (41),Object (44)     |          85 |   2.37496507404302859 |
| metadata.document.authors.author.suffix                   | String                     |          54 |   1.50880134115674780 |
| metadata.document.supplemental-files.file.archive-name    | String                     |          44 |   1.22939368538697957 |
| metadata.document.supplemental-files.file.mime-type       | String                     |          44 |   1.22939368538697957 |
| metadata.document.supplemental-files.file.upload-name     | String                     |          44 |   1.22939368538697957 |
| metadata.document.supplemental-files.file.url             | String                     |          44 |   1.22939368538697957 |
| metadata.document.supplemental-files.file.XX.archive-name | String                     |          41 |   1.14557138865604924 |
| metadata.document.supplemental-files.file.XX.mime-type    | String                     |          41 |   1.14557138865604924 |
| metadata.document.supplemental-files.file.XX.upload-name  | String                     |          41 |   1.14557138865604924 |
| metadata.document.supplemental-files.file.XX.url          | String                     |          41 |   1.14557138865604924 |
| metadata.document.supplemental-files.file.XX.description  | String                     |          31 |   0.86616373288628112 |
| metadata.document.supplemental-files.file.description     | String                     |          29 |   0.81028220173232746 |
| metadata.document.withdrawn                               | String                     |           2 |   0.05588153115395362 |
| metadata.document.authors.author.XX.fname                 | String                     |           1 |   0.02794076557697681 |
| metadata.document.authors.author.XX.institution           | String                     |           1 |   0.02794076557697681 |
| metadata.document.authors.author.XX.lname                 | String                     |           1 |   0.02794076557697681 |
| metadata.document.authors.author.XX.mname                 | String                     |           1 |   0.02794076557697681 |