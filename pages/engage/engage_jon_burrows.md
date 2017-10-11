---
title: Jon Burrows Mental Health Discharge Summary Scenario
keywords: workflow
tags: [development,fhir,profiles]
sidebar: overview_sidebar
permalink: engage_jon_burrows.html
summary: "Example scenario - Jon Burrows Mental Health Discharge Summary"
---

{% include custom/search.warnbanner.html %}

## Background ##

Jon Burrows aged 47, has been depressed for several months after losing his job as a building surveyor. He was having difficulty sleeping and often waking early, sometimes at three or four in the morning. One afternoon he goes to a local park with several packets of Paracetamol and a bottle of whisky. He sits on a bench and swallows a handful of the Paracetamol while drinking half of the bottle of whisky before passing out and falling off the bench into some bushes. 

Luckily he is found by Frank a neighbour, out walking his dog. Frank sees the half bottle of whisky and thinks Jon is just drunk. He knows Jon's wife Eve, is at work but is friends with Jon's father and rings him. Jon's father hurries to the park where Frank has managed to rouse Jon who is sitting on the bench. By this time Frank has found out that Jon is not just drunk but has taken some tablets. Jon did not want Frank to call for an ambulance but agrees to go to A&E with his father. Frank helps get Jon to his father's car and then rings Jon's wife to let her know what's going on. On the way to the hospital Frank questions Jon about what he has taken and Jon mumbles that its just a few Paracetamol. On Arrival at the hospital A&E Jon's father explains that Jon has drunk half a bottle of whisky and shows the empty paracetamol foils.

## The Inpatient Stay ##

The Inpatient stay is carried in the [Encounter Resource](https://fhir.nhs.uk/STU3/StructureDefinition/CareConnect-ITK-Encounter-1)

## Named Participants ##

- Patient - **Jon Burrows** - [Patient Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Patient-1)
- Patient's Father (Encounter participant) - **Andrew Burrows** - [RelatedPerson Resource](https://fhir.nhs.uk/STU3/StructureDefinition/ITK-RelatedPerson-1)
- Consultant - **Dr Daniel Beck** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Consultant - **Dr Mike Scott** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Patient's GP (Document recipient) - **Dr James Lozo** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Community Team member (Document recipient) - **Mrs Gay Gillingham** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)

## Named Organisations ##

- Patient's GP Practice - **MGP Medical Centre** - [Organization Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Organization-1)
- Discharging Hospital - **Leeds Mental Health NHS Trust** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)

Following his triage at A & E Jon is admitted to the Psychiatric Ward on the 13th March. A nurse takes a blood sample so that a full blood count can be done. The nurse asks him a few questions about his family life and drinking habits. Jon tells the nurse he has a wife and two teenage daughters and jokes that his daughter are bit of a handful. Jon points out that he does not normally drink. The nurse asks if he has any worries or concerns and Jon tells her that he does not want ECT. The nurse replies that she does not think that will be necessary. 

Later he has a consultation with Dr Daniel Beck. During the course of the consultation he is assessed using HoNOS and scored at 19 and diagnosed with severe depressive episode without psychotic symptoms. He is prescribed Sertraline 200mg. Later he is asked if he would be prepared to participate in research. He agrees that he would like to do so. 
While on the ward his suicidal urges have reduced and he has responded to antidepressant to good effect. He now regrets attempting to take his own life, is thankful for the support of his family and looks forward to commencing psychological therapies for depression (IAPT) and seeking new employment. Jon is discharged by Dr Mike Scott on the 6th April who sends a copy of the discharge Jon's GP (Dr James Lozo) and the Mrs Gillingham the Community Team member.

## Example Instance of Scenario ##

<script src="https://gist.github.com/IOPS-DEV/f35fd1282d2e594b0b4d07b0cb6a2fec.js"></script>