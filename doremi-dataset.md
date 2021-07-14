---
layout: post-default
---

# DOReMi - Data Collection Lifecycle Document

This documents the lifecycle of the DOREMI dataset. DOReMi is a dataset that contains data related to OMR research. DOReMi is a product of collaborative work between Steinberg (Dorico team) and QMUL (Elona Shatri and George Fazekas). This dataset aims to fill in the existing gaps in OMR research. It is part of a larger research question, whether deep learning can assist theOMR field.  What sets DOReMi aside from the other datasets is the richness of data. Given that this dataset is generated using Dorico (a music notation software from Steinberg), we had the chance to grab more musical information on it, but also different types of data. Using Dorico we can generate 5 types of data that could possibly be used in different steps of OMR. These data are images of scores (binary or colour), the musicXML file, XML files with metadata such as bounding boxes of each object together with musical information, which will be explained in detail later on, and as part of our dataset we can utilize the midi audio file which can be later used for transcription as well. 

## [Discovery and Planning](#discovery-and-planning)
*   [Data type and format]()
*   [Let’s start by explaining each one of the data types and what they contain]()
*   [Dorico project]()
*   [MusicXML]()
*   [OMR metadata]()
*   [Images of scores]()
*   [MIDI]()
*   [Combining DOReMi with Muscima++ and Deepscores]()

## [Initial Data Collection]()
## [Data Preparation and analysis]()
## [Publication and Sharing]()
## [Long-term Management]()


[DoReMi Dataset](./doremi-dataset.html)

##  <A href="#discovery-and-planning"> Discovery and Planning </A>

In this section, I will explain the data types and formats we have decided to use.

*   Data type and format

This dataset has the following six types of data:

* [Dorico project](#dorico-project)
* [MusicXML](#MusicXML)
* OMR metadata
* Images of scores
* MIDI
* Music Encoding Initiative (MEI) 

The following are the data formats:
*   Dorico
*   XML
*   XML
*   PNG
*   MIDI
*   MEI

Let’s start by explaining each one of the data types and what they contain:

<A href="#dorico-project"> Dorico project </A>


When saving the scores in Dorico, it uses the .dorico file format, which is the project type. Saving the projects is really important for the lifecycle since it allows us to use the same layout settings if we later want to generate other data or change.
MusicXML
MusicXML is widely known and used data format in music notation which uses the XML file format. MusicXML allows interchangeability between different scorewriters. Dorico can export the projects to MusicXML. The extension for these files is .xml. 
More on how these files can be exported: https://steinberg.help/dorico_pro/v3/en/dorico/topics/project_file_handling/project_file_handling_musicxml_files_exporting_t.html


<A href="#MusicXML">  MusicXML </A> 

MusicXML is widely known and used data format in music notation which uses the XML file format. MusicXML allows interchangeability between different scorewriters. Dorico can export the projects to MusicXML. The extension for these files is .xml. 
More on how these files can be exported: https://steinberg.help/dorico_pro/v3/en/dorico/topics/project_file_handling/project_file_handling_musicxml_files_exporting_t.html


*   OMR metadata
*   Images of scores
*   MIDI
*   Combining DOReMi with Muscima++ and Deepscores



[back](./)
