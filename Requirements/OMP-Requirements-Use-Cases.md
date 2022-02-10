## Scope

```
Define as it relates to Open Manufacturing Platform Activity. If it adds clarity, define what is not in the scope. DELETE THIS COMMENT 
```

## References
### Normative References

```
The policy for reference lists is:
1. OMP documents listed should have at least one approved version – draft-only docs should not be referenced.
Exception exists for documents that will be approved with or after the referenced doc is approved (may be part of same enabler package). In short – approved docs should not reference unapproved docs.
2. The name + version (no date) for OMP specifications are generally sufficient – dates should be used only if there is a specific reason to limit the usage.
3. References to other affiliate docs should similarly provide sufficient information to uniquely determine the needed document and should provide the appropriate source information.
4. The URL for OMP material (new OMP and affiliate) should always be http://www.openmanufacturingplatform.org.
    
Models to use:
	[REFLABEL]	<General Model> "Ref Title", Ref information (source, date, id), URL:http//<ref-source>/ 
	[OMPDOC]	<OMP Model> "OMP Document Title",{ Version x.y,} Open Manufacturing Platform™, OMP <docname>{    <version>}, URL:http//www.openmobilealliance.org/ 

If there are no entries in the table – enter ‘none’ to be clear.

DELETE THIS COMMENT
```
<table>
  <caption>Normative References </caption>
  <tbody>
    <tr>
      <td><strong>[RFC2119]</strong></td>
      <td>"Key words for use in RFCs to Indicate Requirement Levels", S. Bradner, March 1997, URL:http://www.ietf.org/rfc/rfc2119.txt</td>
    </tr>
    <tr>
      <td><strong>[RFC5234]</strong></td>
      <td>"Augmented BNF for Syntax Specifications: ABNF", D. Crocker, Ed., P. Overell, Janury 2008, URL: https://tools.ietf.org/rfc/rfc5234.txt</td>
    </tr>
  </tbody>
</table>

```
Add/Remove reference rows as needed - DELETE This Row 
```

### Informative References

```
Check the version of the Dictionary you are using and update the reference below. Delete the [OMPDICT] entry if 
the dictionary is not used. In general, use the latest
available version unless seeking alignment with an 
existing set of specifications.

DELETE THIS COMMENT
```
<table>
  <caption>Informative References </caption>
  <tbody>
    <tr>
      <td><strong>[OMPDICT]</strong></td>
      <td>"Dictionary for OMP Specifications", Version x.y, Open Manufacturing Platform™, OMP-ORG-Dictionary-Vx_y, URL:http://www.openmanufacturingplatform.org/</td>
    </tr>
  </tbody>
</table>

```
Add/Remove references as needed - DELETE This Row
```

## Terminology and Conventions
### Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC2119].

All sections and appendixes, except "Scope" and "Introduction", are normative, unless they are explicitly indicated to be informative.

```
If needed, describe or declare using appropriate normative references the additional conventions that are used. DELETE THIS COMMENT
```

### Definitions

```
Add definitions in new rows of the following table as needed. The following examples show how dictionary references should be made as well as locally defined terms. This table should be maintained in sorted alphabetic order based on the labels of the terms.

Examples:
	Entity              Use definition #1 from [OMPDICT]
	Interactive Service Use definition from [OMPDICT]
	Local Term          The definition description would be presented directly

DELETE THIS COMMENT
```
<table>
  <caption>Definitions</caption>
  <tbody>
    <tr>
	<td><strong>Definition-1</strong></td>
	<td>Description definition-1</td>
    </tr>
    <tr>
	<td><strong>Definition-2</strong></td>
	<td>Description definition-2</td>
    </tr>
  </tbody>
</table>

```
Add/Remove definition rows as needed - DELETE This Row
```

Kindly consult [OMPDICT] for more definitions used in this document.

### Abbreviations

```
Add abbreviations as needed. No special notation should be made regarding terms copied from the Dictionary.  
The list should be maintained in alphabetic order. DELETE This Row
```

<table>
<caption>Definitions</caption>
<tbody>
  <tr>
    <td>OMP</td>
    <td>Open Manufacturing Platform</td>
  </tr>
</tbody>
</table>

## Introduction

```
From a market perspective...  

* What can you do with this specification?
* What problem does this solve?
* How can this specification be applied?
* Consider the target audience and provide deployment examples as possible.

DELETE THIS COMMENT
```

### Version 1.0

```
This section provides a high level, concise and informative description of the main functionality supported in 
the initial version of the specification. The description should be brief, target length should be a few paragraphs. 
When the enabler or reference release is finished, this description should be aligned with the final functionality. 

DELETE THIS COMMENT
```

### Version (x.y)

```
This section should be included for each new major or minor version of the specification.

It should provide a high level, concise and informative description of the new or modified functionality introduced in this version of the specification, compared to the previous version. The description should be brief, target length should be a few paragraphs. When the enabler or reference release is finished, this description should be 
aligned with the final functionality differences.

DELETE THIS COMMENT
```

#### Version (x.y.z)

```
Service indicator (z) for the document. Incremented every time a corrective update is made to the approved document version by the WG. This section should describe at a high level the main changes made to the specification compared to the previous version. The description should be brief, target length should be one paragraph.

DELETE THIS COMMENT
```
## Release name - Release description       (Informative)
```
This clause illustrates what the release is about, describing the release in terms of its functionalities, identifying the actors and their relationships. The inclusion of any pictures to back up text should be kept simple, showing various actors involved. The text shall summarize the functionalities of the release in a generic form which does not constrain terminal or network design. It is intended to allow an understanding of the release without regard to implementation. The description should include functional, charging, administration and configuration, usability, interoperability, privacy aspects as well as interactions with other releases.
Part of this text can be easily extracted from the WID
DELETE THIS COMMENT
```
<figure>
<img scr="images/omp_governance.svg" alt="Example Figure">
<figcaption>Example Figure</figcaption>
</figure>

### End-to-end Service Description
```
This section provides indications on what is the business rational for creating such enabler release. The text has to be a high level description of the features and functions provided by the OMP enabler release, including their objectives, when considered as a service (e.g. xxxx) and/or a building block (e.g. xxxx). 
This description should address the end-to-end experience provided by the OMP services (e.g. the end-users prefer to receive advertising contents that are targeted to their interests and needs; they demand that the service provider guarantees that messages are sent by authenticated parties, as they do not want to receive spam). Also, this description should address what are the overall functions of the enabler release to be able to support other enablers (e.g. xxxx). 
The end-to-end description should address the direct benefits for the end users as well as the indirect benefits for the equipment usage, or network interconnections, or overall operations or content adaptation, to mention just a few. 
Both enterprise and consumer scenarios may be considered.
The text in this section should be brief, target length should be a few paragraphs. When the RD definition is finished, this description should be aligned with the final functionality..   
DELETE THIS COMMENT
```
## Requirements
```
This section should capture the requirements necessary for service releases to support end-to-end interoperability across different devices, networks, service providers and network operators.  Linkage of requirements to Use Cases is not mandatory.
In cases where a common or shared requirement document will supply requirements for a section below (e.g. Privacy RD), note it in the appropriate section and reference the requirements to be included.  Then, in the table, add any specific requirements not covered by the shared document.
Each requirement listed in the tables below includes an indication of release.  The value for the release should identify the release in which the requirement desired, expected, or is fulfilled.  In early phases of RD development preceding the RD Review, this field should provide guidance on preferences.  Before commencing the Consistency Review, the fields should be updated, if needed, to reflect the actual requirement coverage fulfilled by the release.
Within the requirement description column in the tables of the following sections, "Notes" might be optionally included. These notes will be considered informative material. Notes are intended to be used to include any kind of information that could help to clarify the corresponding requirement (meaning, applicability, implications, etc.).
In order to improve further development it is recommended that the reason for classifying a requirement as "SHOULD" or "MAY"(instead of "SHALL") shall be given as an "Informational Note" for each such requirement.  See the following example:
```
<table>
<caption>Example Requirements Table - To Be Deleted</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-EXMPL-001</td>
     <td>The FOO Enabler MAY be capable to notify users or not based on political affiliations contained in the User Profile.
Informational Note: This requirement is optional because in some markets this functionality could be forbidden due to regulatory aspects.
</td>
     <td>FOO V1.0</td>	  
  </tr>
</tbody>
</table>

```
For each table (i.e. set of requirements) in this chapter, please provide introductory text describing the background to the requirements.
DELETE THIS COMMENT >>
```

### High-Level Functional Requirements

```
This clause identifies the high level functional requirements for this release.  These requirements will be used to describe and derive the functions and interfaces that the release will support, and which defines its core purpose.  When writing requirements, care should be taken to recognise the difference between the release specifying a mechanism to perform a function versus its required usage in any given deployment.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.  Whenever a requirement is directly attributable to a particular actor, it is recommended to mention it.
Examples of such requirements are:
o	The XYZ release SHOULD support content delivery estimation time before and /or during service execution.
o	The XYZ release MUST be capable of supporting the Service Provider to log information about invocations of this release
o	The XYZ release MUST allow the end user to terminate a session
o	The XYZ release MUST allow actor X to perform function Y
If possible, requirements should be listed in a logical sequence that intuitively captures the behaviour of the release (or feature of the release). In order to get a good readability and quality of RDs, some additional Sections ("Heading 2") and Subsections should be identified, that group together requirements related to a specific functionality, avoiding having the most of the requirements as High-Level Functional requirements.
DELETE THIS COMMENT
```
(Add introduction text for High Level requirements here.)

<table>
<caption>High-Level Functional Requirements</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-HLF-001</td>
     <td>This is where the requirement goes. <strong>Informational Note</strong>: This is where any supporting comments would be placed, if needed</td>
     <td>FOO v1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>

#### Security

```
This clause identifies the high-level security needs for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements. 
in this area.
DELETE THIS COMMENT
```
(Add introduction text for Security requirements here.)

<table>
<caption>High-Level Functional Requirements – Security Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-SEC-001</td>
     <td>This is where the requirement goes. <strong>Informational Note</strong>: This is where any supporting comments would be placed, if needed</td>
     <td>FOO v1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>  

##### Authentication
```
The tables in sections 6.1.1.1 through 6.1.1.4 have model requirements which might be applicable for this RD. 
DELETE THIS COMMENT
```
(Add introduction text for Authentication requirements here.)
 
<table>
<caption>High-Level Functional Requirements – Authentication Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-AUTHE-001</td>
     <td>This function MUST be able to authenticate the {requestor of this function | user | device | initiator | etc} {if required by the applicable policies}.</td>
     <td>FO0 v1.0</td>	  
  </tr>
  <tr>
     <td>FOO-AUTHE-002</td>
     <td>This function MUST be able to authenticate the {provider of this function | server | proxy | responder | etc} {if required by the applicable policies}.</td>
     <td>FOO v1.0</td>	  
  </tr>
  <tr>
     <td>FOO-AUTHE-003</td>
     <td>This function MUST be able to provide data origination authentication {if required by the applicable policies}. This means, it MUST be possible to ensure confidence that a received message or piece of data has been created by a certain party at some (unspecified) time in the past, and that this data has not been corrupted or tampered with.</td>
     <td>FOO v1.0</td>	  
  </tr>
  <tr>
     <td>FOO-AUTHE-004</td>
     <td>This function MUST be able to provide replay protection {if required by the applicable policies} to ensure confidence that a received message has not been recorded and played back.</td>
     <td>FOO v1.0</td>	  
  </tr>
  <tr>
     <td>FOO-AUTHE-005</td>
     <td>This function MUST be able to authenticate the source of the broadcast or streaming {if required by the applicable policies}.   
     <td>FOO v1.0</td>	  
  </tr>
   <tr>
     <td>FOO-AUTHE-006</td>
     <td>This function MUST be able to implicitly authenticate the destinations of the broadcast or streaming {if required by the applicable policies}.</td> 
     <td>FOO v1.0</td>	  
  </tr>
	<tr>
     <td>FOO-AUTHE-007</td>
     <td>This function MUST allow the user to authenticate himself to the {device | agent} e.g., by entering a PIN code or by using biometrics if applicable.</td>    
     <td>FOO v1.0</td>	  
  </tr>
   <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>

##### Authorization
```
The tables in sections 6.1.1.1 through 6.1.1.4 have model requirements which might be applicable for this RD. 
DELETE THIS COMMENT
```
(Add introduction text for Authorization requirements here.)
 
<table>
<caption>High-Level Functional Requirements – Authorization Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-AUTHO-001</td>
     <td>This function MUST be able to authorize access only to requestors entitled to access the function.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>
</tbody>
</table>

##### Data Integrity

```
The tables in sections 6.1.1.1 through 6.1.1.4 have model requirements which might be applicable for this RD. 
DELETE THIS COMMENT
```
(Add introduction text for Data Integrity requirements here.)

<table>
<caption>High-Level Functional Requirements – Data Integrated Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-DATA-001</td>
     <td>This function MUST be able to provide data integrity, protecting against accidental or intentional changes to the data, by ensuring that changes to the data are detectable.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>

##### Confidentiality
```
The tables in sections 6.1.1.1 through 6.1.1.4 have model requirements which might be applicable for this RD. 
DELETE THIS COMMENT
```
(Add introduction text for Confidentiality requirements here.)

<table>
<caption>High-Level Functional Requirements – Confidentiality Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-CONFI-001</td>
     <td>This function MUST use/support data confidentiality that ensures that transmitted information is not made available or disclosed to unauthorised individuals, entities, or processes.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td>FOO-CONFI-002</td>
     <td>This function MUST use/support* data confidentiality that ensures that stored information is not made available or disclosed to unauthorised individuals, entities, or processes.</td>
     <td>FOO V1.0</td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>
</tbody>
</table>

#### Charging Events
```
This clause identifies the specific charging events needed for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.
DELETE THIS COMMENT
```
(Add introduction text for Charging requirements here.)

<table>
<caption>High-Level Functional Requirements – Charging Events Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-CHG-001</td>
	  <td>The list of Charging events SHALL include at least. </br>- event#1 </br>- event#2 </br>-
	   </br><strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>
</tbody>
</table>

#### Administration and Configuration

```
This clause identifies the high-level administration and configuration needs for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.
DELETE THIS COMMENT
```
(Add introduction text for Administration and Configuration requirements here.)

<table>
<caption>High-Level Functional Requirements – Administration and Configuration Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-ADM-001</td>
	  <td>This is where the requirement goes. <strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>

#### Usability

```
This clause identifies the usability needs for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.
DELETE THIS COMMENT
```
(Add introduction text for Usability requirements here.)

<table>
<caption>High-Level Functional Requirements – Usability Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-USE-001</td>
	  <td>This is where the requirement goes. <strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>		
</tbody>
</table>

### Interoperability
```
This clause identifies the high-level interoperability needs for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.
DELETE THIS COMMENT
```
(Add introduction text for Interoperability requirements here.)

<table>
<caption>High-Level Functional Requirements – Interoperability Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-INT-001</td>
	  <td>This is where the requirement goes. <strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
</tbody>
</table>

#### Privacy
```
This clause identifies the high-level privacy needs for this release.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.  DELETE THIS COMMENT 
```
(Add introduction text for Privacy requirements here.)

<table>
<caption>High-Level Functional Requirements – Privacy Items</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-PRV-001</td>
	  <td>This is where the requirement goes. <strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>		
</tbody>
</table>

### Overall System Requirements

```
<<This clause describes the general behaviour and characteristics of the release such as deployment options, conformance, exceptions, use of existing technologies and specifications, etc.  Requirements shall be presented at a high level, and not assume or imply the technology or implementation of the requirements.  Examples of General System Requirements are:
o	The XYZ release MUST NOT restrict deployment options
o	The XYZ release MUST be defined in an execution environment neutral manner
o	The XYZ release MUST specify interfaces that are access technology neutral
o	The XYZ release MUST be able to support services applicable to any kind of users or segments
o	It SHOULD be possible to use existing OMA Device Management and Provisioning releases.
DELETE THIS COMMENT >>
```
(Add introduction text for System requirements here.)

<table>
<caption>High-Level System Requirements</caption>
<thead>
  <tr>
     <th>Label</th>
     <th>Description</th>
     <th>Release</th>
  </tr>
</thead>
<tbody>
  <tr>
     <td>FOO-SYS-001</td>
	  <td>This is where the requirement goes. <strong>Informational Note:</strong> This is where any supporting comments would be placed, if needed.</td>
     <td>FOO V1.0</td>	  
  </tr>
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>	
  <tr>
     <td></td>
     <td></td>
     <td></td>	  
  </tr>		
</tbody>
</table>


<figure>
	<img src="images/omp_governance.svg" alt="OMP governance">
	<figcaption>OMP governance</figcaption> 
</figure>	




## Appendix Change History (Informative)

### Approved Version x.y History

<table>
    <caption>Approved Version x.y History</caption>
    <thead>
        <tr>
            <th>Reference</th>
            <th>Date</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>    
        <tr>
            <td>n/a</td>
            <td>n/a</td>
            <td>No prior version</td>
        </tr>
    </tbody>
</table>

## Appendix Use Case 1  (Informative)

> This clause provides high-level use cases focused on the users and deployment scenarios
> point of view, targeting release’s requirements. Use cases are additional to the main
> text in the RD and facilitate clarification of the requirements: actually, a use case 
> has to be considered needed (and then added to the RD) when it helps the understanding 
> of a set of requirements. For this reason, it is recommended that the total number of 
> use cases be minimised. Pre conditions and Actors involved MAY be described at the 
> beginning of each use case if this is found to be useful.
> DELETE THIS COMMENT 


### Use Case Title
> The level of detail of descriptions shall be above technical implementations of
> protocols. The sub-sections below should consist of one or two sentences.
> DELETE THIS COMMENT

#### Short Description
> Describe the interaction that occurs in this use case.
> (mandatory)
> DELETE THIS COMMENT 

#### Market Benefits
> Describe the consequence and benefits for the actors as a result of this use case.
> (mandatory)
> DELETE THIS COMMENT 

New line 6:49am, Feb 10th
