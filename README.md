# README

---

This repository includes metadata reports about Trace.

## Reports

* [ETDMS](https://github.com/markpbaggett/trace_metadata_reports/blob/master/etdms_report.md)
	* This report gives a high-level overview of Trace Metadata as OAI_ETDMS.
* [OAIDC](https://github.com/markpbaggett/trace_metadata_reports/blob/master/oaidc_report.md)
	* This report gives a high-level overver of Trace Metadata as OAI_DC.

## Master Metadata Mapping - Theses and Dissertations

| Trace User Interface                   | Oai DC                       | Oai ETDMS   | Proprietary Format   |
| -------------------------------------- | ---------------------------- | ----------- | -------------------- |
| Title | dc:title | title |  |
| Author | dc:creator | creator |  |
| Date of Award | dc:date | datecreated |  |
| Degree Type | dc:source |  thesisdegreelevel |  |
| Degree Name | **NOT MAPPED** | thesisdegreename |  |
| Major | **NOT MAPPED** | thesisdegreediscipline |  |
| Major Professor | **NOT MAPPED** | contributor[0] |  |
| Committee Members | **NOT MAPPED** | contributor[1-i] |  |
| Abstract | dc:description | descriptionabstract |  |
| Recommended Citation | **NOT MAPPED** | **NOT MAPPED** |  |
| Link to Object | dc:identifier | identifier |  |
| **NOT MAPPED** | dc:subject | subject |  |
| **NOT MAPPED** | dc:format | **NOT MAPPED** |  |
| **NOT MAPPED** | dc:publisher | **NOT MAPPED** |  |