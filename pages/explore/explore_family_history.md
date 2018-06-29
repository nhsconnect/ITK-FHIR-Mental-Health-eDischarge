---
title: Family history Section
keywords:  messaging, sections
tags: [fhir,messaging,section]
sidebar: foundations_sidebar
permalink: explore_family_history.html
summary: "Gives information about the Family history section"
---

{% include custom/section.warnbanner.html %}

## Family History Section Content##
This section gives information on illness in family relations relevant to the health or care of the patient. Elements should be rendered as subheadings in any HTML sent.


<table style="width:100%;max-width: 100%;">
	<thead>
		<tr>
			<th width="15%">Section</th>
			<th width="35%">Description</th>
			<th width="5%">Card.</th>
			<th width="5%">MRO*</th>
			<th width="40%">FHIR Target and Guidance</th>
		</tr>
	</thead>
 <tbody>
  <tr>
   <td>Family history</td>
   <td>Information on illness in family relations relevant to the health or care of the patient.</td>
   <td>&nbsp;</td>
   <td>O</td>
			<td>Carried in the CodeableConcept of <b>Composition.section.code</b> FHIR element.</td>
  </tr>
		<tr>
			<th>PRSB Element</th>
			<th>Description</th>
			<th>Card.</th>
			<th>MRO*</th>
			<th>FHIR Target and Guidance</th>		
		</tr>
  <tr>
   <td>Family history</td>
   <td>The record of relevant illness in family relations deemed to be significant to the care or health of the patient, including mental illness and suicide, genetic information etc.</td>
   <td>0 to 1</td>
   <td>O</td>
   <td>Text only.</td>
  </tr>
		<tr>
		<td colspan="5"><b>* M=Mandatory R=Required O=Optional</b></td>
		</tr>
 </tbody>
</table>


##  Example Family History Section ##

<script src="https://gist.github.com/IOPS-DEV/3043b183416ff3b3b9965ae11ba09182.js"></script>

## Coded Resources ##

This text section should be linked to the following FHIR Resources to provide the textual information in a coded format.

- The ITK3 FHIR Mental Health eDischarge does not currently support coded family history information.






