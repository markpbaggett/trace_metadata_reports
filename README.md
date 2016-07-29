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

| Trace User Interface                   | Oai DC                       | Oai ETDMS   | Proprietary Format   | OAI QDC |
| -------------------------------------- | ---------------------------- | ----------- | -------------------- | ------- |
| Title | dc:title | title |  |   |
| Author | dc:creator | creator |  |   |
| Date of Award | dc:date | datecreated |  |   |
| Degree Type | dc:source |  thesisdegreelevel |  |   |
| Degree Name | **NOT MAPPED** | thesisdegreename |  |   |
| Major | **NOT MAPPED** | thesisdegreediscipline |  |   |
| Major Professor | **NOT MAPPED** | contributor[0] |  |   |
| Committee Members | **NOT MAPPED** | contributor[1-i] |  |   |
| Abstract | dc:description | descriptionabstract |  |   |
| Recommended Citation | **NOT MAPPED** | **NOT MAPPED** |  |   |
| Link to Object | dc:identifier | identifier |  |   |
| **NOT MAPPED** | dc:subject | subject |  |   |
| **NOT MAPPED** | dc:format | **NOT MAPPED** |  |   |
| **NOT MAPPED** | dc:publisher | **NOT MAPPED** |  |   |

**Note**: It doesn't appear that theses or dissertations are being embargoed at this point so it's hard to say what this looks like.  If they are, they don't get a *dateavailable* field.