### Overview

This Australian Digital Health Agency FHIR Implementation Guide is a representation of the [Clinical Document Architecture (CDA) R2.0 specification](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=7) using HL7<sup>&reg;</sup> FHIR<sup>&reg;&copy;</sup> Logical Models expressed as HL7<sup>&reg;</sup> FHIR<sup>&reg;&copy;</sup> StructureDefinition instances.

It is an adaptation of the [HL7 International CDA Logical Model Specification](https://hl7.org/cda/stds/core/2.0.0-sd-snapshot1/) with specific modifications and inclusions to represent Australian CDA schema extensions using the FHIR StructureDefinition framework. 

### Australian CDA schema extensions

Australian CDA schema extensions are published here [Australian Digital Health Agency CDA Schema Extension 3.0 - CDA Schema v20201203](https://developer.digitalhealth.gov.au/resources/australian-digital-health-agency-cda-schema-extension-3-0-cda-schema-v20201203).

The following table outlines the specific CDA classes and extensions that are Australian specific. All unmodified CDA classes are listed on the following page: [HL7 CDA Definitions](hl7cdadefinition.html).

The entry point for this specification is the [ADHA ClinicalDocument](StructureDefinition-au-ClinicalDocument.html) class.

<table class="cda-table">
	<tbody>
	<tr>
		<td>
			<h3>ADHA CDA Classes</h3>
			<ul>
				<li><a href="StructureDefinition-au-ClinicalDocument.html"><b>ADHA ClinicalDocument</b></a></li>
				<li><a href="StructureDefinition-au-AssignedAuthor.html">au-AssignedAuthor</a></li>
				<li><a href="StructureDefinition-au-AssignedEntity.html">au-AssignedEntity</a></li>
				<li><a href="StructureDefinition-au-AssignedCustodian.html">au-AssignedCustodian</a></li>
				<li><a href="StructureDefinition-au-AssociatedEntity.html">au-AssociatedEntity</a></li>
				<li><a href="StructureDefinition-au-Author.html">au-Author</a></li>
				<li><a href="StructureDefinition-au-AuthoringDevice.html">au-AuthoringDevice</a></li>
				<li><a href="StructureDefinition-au-ComponentOf.html">au-ComponentOf</a></li>
				<li><a href="StructureDefinition-au-Custodian.html">au-Custodian</a></li>
				<li><a href="StructureDefinition-au-CustodianOrganization.html">au-CustodianOrganization</a></li>
				<li><a href="StructureDefinition-au-EncompassingEncounter.html">au-EncompassingEncounter</a></li>
				<li><a href="StructureDefinition-au-HealthCareFacility.html">au-HealthCareFacility</a></li>
				<li><a href="StructureDefinition-au-InformationRecipient.html">au-InformationRecipient</a></li>
				<li><a href="StructureDefinition-au-IntendedRecipient.html">au-IntendedRecipient</a></li>                
				<li><a href="StructureDefinition-au-languageCommunication.html">au-languageCommunication</a></li>
				<li><a href="StructureDefinition-au-LegalAuthenticator.html">au-LegalAuthenticator</a></li>
				<li><a href="StructureDefinition-au-Organization.html">au-Organization</a></li>
				<li><a href="StructureDefinition-au-OrganizationPartOf.html">au-OrganizationPartOf</a></li>
				<li><a href="StructureDefinition-au-Participant1.html">au-Participant1</a></li>
				<li><a href="StructureDefinition-au-ParticipantRole.html">au-ParticipantRole</a></li>
				<li><a href="StructureDefinition-au-PatientRole.html">au-PatientRole</a></li>
				<li><a href="StructureDefinition-au-Patient.html">au-Patient</a></li>
				<li><a href="StructureDefinition-au-Person.html">au-Person</a></li>
				<li><a href="StructureDefinition-au-RecordTarget.html">au-RecordTarget</a></li>
			</ul>
		</td>
		<td>
			<h3>ADHA Extensions</h3>
			<ul>
				<li><a href="StructureDefinition-asEmployment.html">asEmployment</a></li>
				<li><a href="StructureDefinition-asEntityIdentifier.html">asEntityIdentifier</a></li>
				<li><a href="StructureDefinition-asQualifications.html">asQualifications</a></li>
				<li><a href="StructureDefinition-code.html">code</a></li>
				<li><a href="StructureDefinition-completionCode.html">completionCode</a></li>
				<li><a href="StructureDefinition-coverage2.html">coverage2</a></li>
				<li><a href="StructureDefinition-deceasedInd.html">deceasedInd</a></li>
				<li><a href="StructureDefinition-deceasedTime.html">deceasedTime</a></li>
				<li><a href="StructureDefinition-entitlement.html">entitlement</a></li>
				<li><a href="StructureDefinition-id.html">id</a></li>
				<li><a href="StructureDefinition-interpreterRequiredInd.html">interpreterRequiredInd</a></li>
				<li><a href="StructureDefinition-multipleBirthInd.html">multipleBirthInd</a></li>                
				<li><a href="StructureDefinition-multipleBirthOrderNumber.html">multipleBirthOrderNumber</a></li>
				<li><a href="StructureDefinition-name.html">name</a></li>
				<li><a href="StructureDefinition-participant.html">participant</a></li>
				<li><a href="StructureDefinition-personalRelationship.html">personalRelationship</a></li>
			</ul>
		</td>
		<td>
			<h3>ADHA Complex Data Types</h3>
			<ul>
				<li><a href="StructureDefinition-au-Address.html">au-Address</a></li>
				<li><a href="StructureDefinition-au-Telecom.html">au-Telecom</a></li>
			</ul>
		</td>
	</tr>
	</tbody>
</table>

### Vocabularies

This section lists all ValueSets and CodeSystems defined as part of this specification. 

#### Code systems

{% include res-list-generator.md type="CodeSystem" %}

#### Value sets

{% include res-list-generator.md type="ValueSet" %}

### Other information

#### Intellectual property considerations

This implementation guide and the underlying FHIR specification are licensed as public domain under the [FHIR license](http://hl7.org/fhir/R4/license.html).

{% include ip-statements.xhtml %}

#### Relationships with other work

This implementation guide builds on other specifications, helping ensure a consistent approach to data sharing that should ease adoption. The specific guides used, and the portions relevant from each of them are as follows:

{% include dependency-table.xhtml %}

#### Global profiles

{% include globals-table.xhtml %}