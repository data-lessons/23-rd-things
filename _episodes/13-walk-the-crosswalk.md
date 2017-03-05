---
title: "Thing 13: Walk the crosswalk"
questions:
- "Question 1"
objectives:
- "Objective 1."
keypoints:
- "First key point."
date: "2017-06-01T12:00:00-08:00"
enddate: "2017-06-01T13:00:00-08:00"
location: "Geisel Classroom 2"
published: false
---


Thing 13: Walk the crosswalk
There are times when metadata created using one standard will need to be transformed or crosswalked to another standard so that metadata can been shared between systems.
Getting started: start walking the crosswalks for metadata
Learn more: Hands on with crosswalking Dublin Core
Challenge me: Hands-on with XSLT






Getting started: Why do we need crosswalks?
We learned in Thing 11 that lots of metadata schemas exist to support different data types and disciplines.  There are times when metadata created in one schema will need to be transformed  (“crosswalked”) to another schema so that metadata can been shared between systems and is more discoverable.
Start by simply scrolling down the contributing institutions to Research Data Australia. Many of these contributors use different metadata schemas to create their research data records yet all the records appear in the same format in RDA. The records of each contributor need to be ‘crosswalked’ so they can be aggregated into RDA and the right information appears in the correct metadata field for each record in RDA
Read the Wikpedia introduction to crosswalks.
Now we’ll look at an example of a metadata record that has been crosswalked to comply with different metadata standards so it can be found in various repositories
First look at this CSIRO record.  It was created to comply with the ISO19115 standard for describing geospatial data
in a new window in your browser, take a look at how the metadata for this same record has been transformed (or crosswalked) so it complies with different metadata standards and systems. This is the same record as it appears in the CSIRO Data Access Portal
And the same record again as it was crosswalked for Research Data Australia.


Consider What you notice about these schemas? Do all 3 records provide exactly the same information?  Or are there differences? Why can’t we have One Metadata Schema to rule them all, and not worry about having to Crosswalk?



Learn more: Try your hand at a crosswalk
Let’s map schema!
Mapping and crosswalking metadata from one schema to another enables metadata harvesting and sharing between systems.
Crosswalks are easiest seen in a table or spreadsheet format.  Take a look at this example of a Dublin Core<->DDI crosswalk table.
Time to get hands on!
Start by choosing any existing metadata record to work with.  Here’s an example. This will be your “source” record.
Copy the table from the example above into Word or Excel.  Can you create a high level metadata mapping from your source record to Dublin Core?  The 15 DC Dublin Core (Simple) metadata set explained in more detail.
Don’t worry if you don’t have time to complete the entire record - just get a feel for the process.
Consider:  the most confounding issue you encountered in making your Crosswalk.  How did you overcome it?



Challenge me: An introduction to XSLT for crosswalks
Hands on with XML!
This activity will provide an interactive introduction to XSLT using a free online tool.
Many well-known metadata standards are expressed as XML schemas, including MARCXML, Dublin Core, MODS, METS, EAD, RIF-CS and others. The flexible structure of XML makes it possible to convert data from one metadata standard to another using an XSLT. XSLT (Extensible Stylesheet Language Transformations) is a language for transforming XML documents into other XML documents.
Start by having a look at some of the crosswalks developed for, and by ANDS for ingesting records into Research Data Australia.
Go to the XSLT Test Tool free online tool. Follow the steps in this exercise to create, edit and display XML
Now have a go at the 23 Things - Technical Crosswalk Exercise

Consider: Do you think experience with XML would be useful in your workplace?
