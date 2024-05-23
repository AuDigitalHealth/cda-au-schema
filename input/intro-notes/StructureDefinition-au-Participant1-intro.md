### ParticipationType Value Set
 
The terminology binding on the au-Participant1 `@typeCode` attribute has been changed to use the http://terminology.hl7.org/ValueSet/v3-ParticipationType valueSet rather than http://terminology.hl7.org/ValueSet/v3-ParticipationType (as used in [HL7 International CDA Participant1 class](https://hl7.org/cda/stds/core/2.0.0-sd-snapshot1/StructureDefinition-Participant1.html)). This is due to the attribute value of `PART`, which is mandated in many of the My Health Record CDA implementations, being removed from [HL7 International CDA Participant1 class](
https://hl7.org/cda/stds/core/2.0.0-sd-snapshot1/StructureDefinition-Participant1.html) ValueSet.
 
A GitHub issue has been raised on the HL7 International CDA Logical Model Specification to have this addressed: [@typeCode="PART" has been removed from ValueSet "CDAParticipationType"](https://github.com/HL7/CDA-core-sd/issues/19.html)