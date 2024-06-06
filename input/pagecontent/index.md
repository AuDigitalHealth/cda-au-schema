### Introduction

This Australian Digital Health Agency FHIR Implementation Guide is a representation of the [Clinical Document Architecture (CDA) R2.0 specification](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=7) using HL7<sup>&reg;</sup> FHIR<sup>&reg;&copy;</sup> Logical Models expressed as HL7<sup>&reg;</sup> FHIR<sup>&reg;&copy;</sup> StructureDefinition instances.

It is an adaptation of the [HL7 International CDA Logical Model Specification](https://hl7.org/cda/stds/core/2.0.0-sd/) with specific modifications and inclusions to represent the CDA schema including Australian CDA extensions using the FHIR StructureDefinition framework. 

### Document purpose and scope

The primary aim of this implementation guide is to support implementers who are implementing CDA. It contains CDA extensions in Australian context and the HL7 CDA classes using the Australian extensions. 

This implementation guide does not describe presentation of the information, user experience, or expected behaviour of producing and receiving systems.

Wherever possible, material in this specification is based on existing standards. All efforts have been made to minimise divergence from the HL7 international CDA classes to provide for system interoperability and compatibility with other classes. Issues of an editorial nature in the source material (such as spelling or punctuation errors) are intentionally reproduced.

### Context and use

This CDA extensions logical model FHIR implementation guide should be read in conjunction with the remaining documentation available from [HL7 International CDA Logical Model Specification](https://hl7.org/cda/stds/core/2.0.0-sd-snapshot1/).

The guide includes:
* CDA extensions used in Australian context
* CDA classes in the form of structure definitions
* Vocabularies for the content exchange

### Intended audience

This implementation guide is aimed at software development teams, architects, and designers of CDA implementation in Australia.

This implementation guide and related artefacts are technical in nature and the audience is expected to be familiar with the language of health data specifications and to have some familiarity with health information standards and specifications, such as CDA.

### Document information

#### Intellectual property considerations

This implementation guide and the underlying FHIR specification are licensed as public domain under the [FHIR license](http://hl7.org/fhir/R5/license.html).

{% include ip-statements.xhtml %}

#### Relationships with other work

This implementation guide builds on other specifications, helping ensure a consistent approach to data sharing that should ease adoption. The specific guides used, and the portions relevant from each of them are as follows:

{% include dependency-table.xhtml %}

#### Global profiles

{% include globals-table.xhtml %}

### Known issues

This table lists known issues with this specification at the time of publishing. We are working on solutions to these issues and encourage comments to help us develop these solutions.

<table border="1" cellpadding="1" valign="middle">
 <tbody>
   <col width="15%" />
   <col width="auto" />
   <tr bgcolor="#DCDCDC">
     <th>Reference</th>
     <th>Description</th>
   </tr>
   <tr>
     <td><a href="https://github.com/HL7/CDA-core-sd/issues/19.html">https://github.com/HL7/CDA-core-sd/issues/19</a></td>
     <td>The terminology binding on the au-Participant1 `@typeCode` attribute has been changed to use the <a href="http://terminology.hl7.org/ValueSet/v3-ParticipationType">v3-ParticipationType valueSet</a> rather than the valueSet as used in <a href="https://hl7.org/cda/stds/core/2.0.0-sd-snapshot1/StructureDefinition-Participant1.html">HL7 International CDA Participant1 class</a>. This is due to the attribute value of `PART`, which is mandated in many of the My Health Record CDA implementations.</td>
   </tr>
 </tbody>
</table> 



