# utk_gradthes

## About

This report was created on August 22, 2016.

## Schema

| key                                                       | types                      | occurrences | percents              |
| --------------------------------------------------------- | -------------------------- | ----------- | --------------------- |
| _id                                                       | ObjectId                   |        3815 | 100.00000000000000000 |
| metadata                                                  | Object                     |        3815 | 100.00000000000000000 |
| metadata.document                                         | Object                     |        3815 | 100.00000000000000000 |
| metadata.document.articleid                               | String                     |        3815 | 100.00000000000000000 |
| metadata.document.authors                                 | Object                     |        3815 | 100.00000000000000000 |
| metadata.document.authors.author                          | Object (3814),Array (1)    |        3815 | 100.00000000000000000 |
| metadata.document.context-key                             | String                     |        3815 | 100.00000000000000000 |
| metadata.document.coverpage-url                           | String                     |        3815 | 100.00000000000000000 |
| metadata.document.document-type                           | String                     |        3815 | 100.00000000000000000 |
| metadata.document.fields                                  | Object                     |        3815 | 100.00000000000000000 |
| metadata.document.fields.field                            | Array                      |        3815 | 100.00000000000000000 |
| metadata.document.fields.field.XX.@name                   | String                     |        3815 | 100.00000000000000000 |
| metadata.document.fields.field.XX.@type                   | String                     |        3815 | 100.00000000000000000 |
| metadata.document.fields.field.XX.value                   | String (3815),Array (3669) |        3815 | 100.00000000000000000 |
| metadata.document.label                                   | String                     |        3815 | 100.00000000000000000 |
| metadata.document.publication-date                        | String                     |        3815 | 100.00000000000000000 |
| metadata.document.publication-title                       | String                     |        3815 | 100.00000000000000000 |
| metadata.document.submission-date                         | String                     |        3815 | 100.00000000000000000 |
| metadata.document.submission-path                         | String                     |        3815 | 100.00000000000000000 |
| metadata.document.title                                   | String                     |        3815 | 100.00000000000000000 |
| metadata.document.type                                    | String                     |        3815 | 100.00000000000000000 |
| record_id                                                 | String                     |        3815 | 100.00000000000000000 |
| metadata.document.authors.author.lname                    | String                     |        3814 |  99.97378768020969630 |
| metadata.document.authors.author.fname                    | String                     |        3813 |  99.94757536041939261 |
| metadata.document.fulltext-url                            | String                     |        3809 |  99.84272608125819204 |
| metadata.document.abstract                                | String                     |        3799 |  99.58060288335518351 |
| metadata.document.fields.field.XX.@list                   | String                     |        3743 |  98.11271297509829026 |
| metadata.document.disciplines                             | Object                     |        3682 |  96.51376146788990695 |
| metadata.document.disciplines.discipline                  | String (2911),Array (771)  |        3682 |  96.51376146788990695 |
| metadata.document.authors.author.institution              | String                     |        3123 |  81.86107470511140605 |
| metadata.document.authors.author.mname                    | String                     |        2744 |  71.92660550458715818 |
| metadata.document.authors.author.email                    | String                     |        1601 |  41.96592398427260662 |
| metadata.document.keywords                                | Object                     |        1529 |  40.07863695937090398 |
| metadata.document.keywords.keyword                        | Array (1470),String (59)   |        1529 |  40.07863695937090398 |
| metadata.document.native-url                              | String                     |         905 |  23.72214941022280499 |
| metadata.document.supplemental-files                      | Object                     |          86 |   2.25425950196592417 |
| metadata.document.supplemental-files.file                 | Array (42),Object (44)     |          86 |   2.25425950196592417 |
| metadata.document.authors.author.suffix                   | String                     |          58 |   1.52031454783748354 |
| metadata.document.supplemental-files.file.archive-name    | String                     |          44 |   1.15334207077326334 |
| metadata.document.supplemental-files.file.mime-type       | String                     |          44 |   1.15334207077326334 |
| metadata.document.supplemental-files.file.upload-name     | String                     |          44 |   1.15334207077326334 |
| metadata.document.supplemental-files.file.url             | String                     |          44 |   1.15334207077326334 |
| metadata.document.supplemental-files.file.XX.archive-name | String                     |          42 |   1.10091743119266061 |
| metadata.document.supplemental-files.file.XX.mime-type    | String                     |          42 |   1.10091743119266061 |
| metadata.document.supplemental-files.file.XX.upload-name  | String                     |          42 |   1.10091743119266061 |
| metadata.document.supplemental-files.file.XX.url          | String                     |          42 |   1.10091743119266061 |
| metadata.document.supplemental-files.file.XX.description  | String                     |          32 |   0.83879423328964609 |
| metadata.document.supplemental-files.file.description     | String                     |          29 |   0.76015727391874177 |
| metadata.document.withdrawn                               | String                     |           2 |   0.05242463958060288 |
| metadata.document.authors.author.XX.fname                 | String                     |           1 |   0.02621231979030144 |
| metadata.document.authors.author.XX.institution           | String                     |           1 |   0.02621231979030144 |
| metadata.document.authors.author.XX.lname                 | String                     |           1 |   0.02621231979030144 |
| metadata.document.authors.author.XX.mname                 | String                     |           1 |   0.02621231979030144 |

## Distinct Value Reports

* [abstract](distinct_reports/abstract.md)
* [article-id](distinct_reports/article-id.md)
* [authors.author.email](distinct_reports/authorauthoremail.md)
* [authors.author.fname](distinct_reports/authorauthorfname.md)
* [authors.author.mname](distinct_reports/authorauthormname.md)
* [authors.author.lname](distinct_reports/authorauthorlname.md)
* [authors.author.institution](distinct_reports/authorauthorinstitution.md)
* [authors.author.suffix](distinct_reports/authorauthorsuffix.md)
* [context-key](distinct_reports/context-key.md)
* [coverpage-url](distinct_reports/coverpage-url.md)
* [disciplines.discipline](distinct_reports/discipline.md)
* [document-type](distinct_reports/document-type.md)
* [fields.field.list](distinct_reports/fieldsfieldlist.md)
* [fields.field.name](distinct_reports/fields.field.name.md)
* [fields.field.type](distinct_reports/fields.field.type.md)
* [fields.field.value](distinct_reports/fieldsfieldvalue.md)
* [fulltext-url](distinct_reports/fulltext-url.md)
* [keywords.keyword](distinct_reports/keywords.md)
* [label](distinct_reports/label.md)
* [native-url](distinct_reports/native-url.md)
* [publication-date](distinct_reports/publication-date.md)
* [publication-title](distinct_reports/publication-title.md)
* [submission-date](distinct_reports/submission-date.md)
* [submission-path](distinct_reports/submission-path.md)
* [supplemental-files.file.archive-name](distinct_reports/supplemental-files_file-archive-name.md)
* [supplemental-files.file.description](distinct-reports/description.md)
* [supplemental-files.file.mime-type](distinct_reports/supplemental-files_file_mime-type.md)
* [supplemental-files.file.upload-name](distinct_reports/supplemental-files_file_upload-name.md)
* [supplemental-files.file.url](distinct_reports/supplemental-files_file_url.md)
* [type](distinct_reports/type.md)
* [withdrawn](distinct_reports/withdrawn.md)

**NOTE**: If you're trying to understand fields/field, use **the [full JSON object report for fields.field](distinct_reports/fields_complete.md).** Trust me, JSON is your friend.