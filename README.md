# README

---

This repository includes metadata reports about Trace.

## Reports

* [ETDMS](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_report.md)
	* This report gives a high-level overview of Trace Metadata as OAI_ETDMS.
* [OAIDC](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oaidc_report.md)
	* This report gives a high-level overview of Trace Metadata as OAI_DC.
* [QDC](https://github.com/markpbaggett/trace_metadata_reports/blob/master/qdc_report.md)
	* This report gives a high-level overview of Trace Metadata as QDC.

## Master Metadata Mapping - Theses and Dissertations

| Trace User Interface                   | Oai DC                       | Oai ETDMS   | Trace Data Dump | OAI QDC |
| -------------------------------------- | ---------------------------- | ----------- | -------------------- | ------- |
| Title | dc:title | title | title | dc:title |
| Author | dc:creator | creator | authors\author\fname, authors\author\mname, authors\author\lname  |  dc:creator |
| Date of Award | dc:date | datecreated | publicationdate | dc:datecreated  |
| Degree Type | **NOT MAPPED** |  thesisdegreelevel | document-type  | dc:thesisdegreelevel  |
| Degree Name | **NOT MAPPED** | thesisdegreename | fields\field@name='degree_name'\value  | dc:thesisdegreename |
| Major | **NOT MAPPED** | thesisdegreediscipline | fields\field@name='department'\value | dc:thesisdegreediscipline |
| Major Professor | **NOT MAPPED** | contributor[0] | fields\field@name='advisor1'\value | dc:contributor[0] |
| Committee Members | **NOT MAPPED** | contributor[1-i] | fields\field@name='advisor2'\value[0-i] | dc:contributor[1-i] |
| Abstract | dc:description | descriptionabstract | abstract | dc:descriptionabstract |
| Recommended Citation | **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** |
| **NOT MAPPED** | dc:subject[!last] | subject[!last] | keywords\keyword | dc:subject[!last] |
| **NOT MAPPED** | dc:format | **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** |
| **NOT MAPPED** | dc:publisher | **NOT MAPPED** | **NOT MAPPED** |  **NOT MAPPED** |
| **NOT MAPPED** | dc:subject[last] | subject[last] | disciplines\discipline | dc:subject[last] |
| Web URL (no label) | dc:identifer[0] | identifer | coverpage-url | dc:identifer |
| Link to Full-text (no label) | dc:identifer[1] | **NOT MAPPED** | fulltext-url | **NOT MAPPED** |
| Breadcrumb | **NOT MAPPED** | **NOT MAPPED** | label | **NOT MAPPED** |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | type | **NOT MAPPED** |
| **NOT MAPPED** | oaipmhid | **NOT MAPPED** | articleid | oaipmhid |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | submission date | **NOT MAPPED** |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | native-url | **NOT MAPPED** |
| **NOT MAPPED** | dc:source | **NOT MAPPED** | publication-title | **NOT MAPPED**  |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | context-key | **NOT MAPPED** |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | submission-path | **NOT MAPPED** |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | authors\author\email | **NOT MAPPED** |
| **NOT MAPPED** | **NOT MAPPED** | **NOT MAPPED** | authors\author\institution | **NOT MAPPED** |

**Note**: It doesn't appear that theses or dissertations are being embargoed at this point so it's hard to say what this looks like.  If they are, they don't get a *dateavailable* field.
**About Trace Data Dump**: Full Xpath is not given.  XML document starts at \documents\document