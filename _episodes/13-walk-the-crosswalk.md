---
title: "Thing 13: Walk the crosswalk"
questions:
- "What are metada crosswalks in the context of research data?"
objectives:
- "Identify the reasons for metada standard crosswalks."
- "Create a metadata mapping from one schema to another."
- "Apply and modify a metadata crosswalk using XLST. "
keypoints:
- "First key point."
---

## Getting started: Why do we need crosswalks?

We learned in Thing 11 that lots of metadata schemas exist to support different data types and disciplines.  There are times when metadata created in one schema will need to be transformed  (“crosswalked”) to another schema so that metadata can been shared between systems and is more discoverable.

> ## Explore the Purpose for Metadata Crosswalks
> 1. Start by scrolling down the [contributing institutions](https://researchdata.ands.org.au/contributors) to Research Data Australia. Many of these contributors use different metadata schemas to create their research data records yet all the records appear in the same format in RDA. The records of each contributor need to be ‘crosswalked’ so they can be aggregated into RDA and the right information appears in the correct metadata field for each record in RDA
> 2. Read the Wikpedia introduction to crosswalks.
> 4. Now we’ll look at an example of a metadata record that has been crosswalked to comply with different metadata standards so it can be found in various repositories
> 5. First look at this CSIRO record.  It was created to comply with the ISO19115 standard for describing geospatial data
> 6. In a new window in your browser, take a look at how the metadata for this same record has been transformed (or crosswalked) so it complies with different metadata standards and systems. This is the same record as it appears in the [CSIRO Data Access Portal](http://doi.org/10.4225/08/50F624A9E6D5C)
> 7. And the same record again as it was crosswalked for [Research Data Australia](https://researchdata.ands.org.au/wamsi-node-11-2007-2008/444960/).
> 8.What you notice about these schemas? Do all 3 records provide exactly the same information?  Or are there differences? Why can’t we have One Metadata Schema to rule them all, and not worry about having to Crosswalk?
{: .challenge}


## Learn more: Walk the crosswalk

Let’s map schema!

Mapping and crosswalking metadata from one schema to another enables metadata harvesting and sharing between systems.

> ##  Try your hand at a crosswalk
> 1. Crosswalks are easiest seen in a table or spreadsheet format.  Take a look at [this example](http://www.ddialliance.org/resources/ddi-profiles/dc) of a `Dublin Core<->DDI` crosswalk table.
> 2. Time to get hands on!
> 3. Start by choosing any existing metadata record to work with.  Here’s an [example](https://researchdata.ands.org.au/eeg-perception-microtones-information-stimuli). This will be your “source” record.
> 4. Copy the table from the [example](https://researchdata.ands.org.au/eeg-perception-microtones-information-stimuli) above into Word or Excel.  Can you create a high level metadata mapping from your source record to Dublin Core?  The 15 DC Dublin Core (Simple) metadata set [explained in more detail](http://dublincore.org/documents/dces/).
> 5. Don’t worry if you don’t have time to complete the entire record - just get a feel for the process.
> 6. Consider:  the most confounding issue you encountered in making your Crosswalk.  How did you overcome it?
{: .challenge}

## Challenge me: An introduction to XSLT for crosswalks

Hands on with XML!

This activity will provide an interactive introduction to XSLT using a free online tool.

Many well-known metadata standards are expressed as XML schemas, including MARCXML, Dublin Core, MODS, METS, EAD, RIF-CS and others. The flexible structure of XML makes it possible to convert data from one metadata standard to another using an XSLT. XSLT (Extensible Stylesheet Language Transformations) is a language for transforming XML documents into other XML documents.

> ## Working with XSLT
> 1. Start by having a look at some of the [crosswalks](http://www.ands.org.au/online-services/rif-cs-schema/crosswalks-transform-your-metadata) developed for, and by ANDS for ingesting records into Research Data Australia.
> 2. Go to the [XSLT Test Tool](http://xslttest.appspot.com/) free online tool. Follow the steps in this exercise to create, edit and display XML
> 3. Now have a go at the [23 Things - Technical Crosswalk Exercise](https://www.ands.org.au/partners-and-communities/23-research-data-things/all23/thing-13/technical-crosswalk-exercise)
> 4. Consider: Do you think experience with XML would be useful in your workplace?
{: .challenge}
