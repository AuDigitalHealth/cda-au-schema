### This table lists the deviations from <a href="https://hl7.org/cda/stds/core/2.0.0-sd/index.html">hl7.cda.uv.core</a>.

<table border="1" cellpadding="1" valign="middle">
 <tbody>
   <col width="15%" />
   <col width="auto" />
   <tr bgcolor="#DCDCDC">
     <th>Reference</th>
     <th>Description of the deviation</th>
   </tr>
   <tr>
     <td>StructureDefinition-au-Observation</td>
     <td>Added xsi:type 'CS' to observation.value since it is not present in <a href="https://hl7.org/cda/stds/core/2.0.0-sd/StructureDefinition-Observation.html">Observation (CDA Class)</a>.</td>
   </tr>
   <tr>
     <td>StructureDefinition-au-Observation</td>
     <td>Added xsi:type 'PN' to observation.value since it is not present in <a href="https://hl7.org/cda/stds/core/2.0.0-sd/StructureDefinition-Observation.html">Observation (CDA Class)</a>.</td>
   </tr>
   <tr>
     <td>StructureDefinition-au-Address</td>
     <td>Changed the cardinality of AD.streetAddressLine to 0..* as the Agency CDA specificatons allow for 0..* but <a href="https://hl7.org/cda/stds/core/2.0.0-sd/StructureDefinition-AD.html">AD: PostalAddress (V3 Data Type)</a> allows for only 0..1.</td>
   </tr>
 </tbody>
</table> 