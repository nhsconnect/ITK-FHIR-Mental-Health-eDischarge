---
title: Elizabeth Black Mental Health Discharge Summary Scenario
keywords: workflow
tags: [development,fhir,profiles]
sidebar: overview_sidebar
permalink: engage_elizabeth_black.html
summary: "Example scenario - Elizabeth Black Mental Health Discharge Summary"
---

{% include custom/search.warnbanner.html %}

## Background ##

Elizabeth Black is well known to local mental health services and police. On the 12th Feb at a local shopping centre she is involved in an disturbance with another customer who she then assaults. The police are called and they take her to the hospital A+E department.

## The Inpatient Stay ##

The Inpatient stay is carried in the [Encounter Resource](https://fhir.nhs.uk/STU3/StructureDefinition/CareConnect-ITK-Encounter-1)

## Named Participants ##

- Patient - **Elizabeth Black** - [Patient Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Patient-1)
- Patient's contact (Daughter) - **Mrs Susan Smith** - [RelatedPerson Resource](https://fhir.nhs.uk/STU3/StructureDefinition/ITK-RelatedPerson-1)
- Patient's contact (Community Consultant) - **Mrs Gay Gillingham** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Consultant - **Dr Daniel Beck** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Specialty registrar (Document Author) - **Dr Mike Scott** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Patient's GP (Document recipient) - **Dr James Lozo** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)
- Community Team member (Document recipient) - **Mrs Gay Gillingham** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)

## Named Organisations ##

- Patient's GP Practice - **MGP Medical Centre** - [Organization Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Organization-1)
- Discharging Hospital - **Leeds Mental Health NHS Trust** - [Practitioner Resource](https://fhir.hl7.org.uk/STU3/StructureDefinition/CareConnect-Practitioner-1)

Dr Daniel Beck interviews Elizabeth on the 12th Feb and notes she appears agitated and denying any thoughts of self-harm. She denies any drug misuse. She is tested and proves negative for banned substances following admission. Dr Black makes a diagnosis of Paranoid Schizophrenia and is aware that Elizabeth is frequently uncompliant with treatment. Due to poor adherence with treatment she is discharged from hospital subject to a Community Treatment Order and warned that she is subject to recall to hospital if she does not adhere to treatment.Jon is discharged by Dr Daniel Beck on the 5th March who sends a copy of the discharge to Jon's GP and the Mrs Gillingham the Community Team member.

## Example Instance of Scenario ##

<script src="https://gist.github.com/IOPS-DEV/12fe5deaca548bbcb5f0d8db00f08989.js"></script>