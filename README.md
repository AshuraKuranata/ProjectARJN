# README

https://chatgpt.com/s/t_68d5b67b961c8191babf77a6ed7eb625

## Requirements

## 🛠️ Core Features

### Patient Lookup
Query FHIR server for Patient resources.
Display demographics (name, DOB, gender, MRN).

### Clinical Data View
Fetch Observation resources (labs, vitals).
Show chart of lab trends (Chart.js / Recharts).
Display Conditions or Medications.

### HL7 → FHIR Mapping
Parse a sample HL7 ORU message (MSH|...|OBR|...|OBX|...).
Convert OBX (lab result) into a FHIR Observation.
Store it in your FHIR server.

### Imaging Studies (DICOM)
Query a DICOMweb server with QIDO-RS (list studies).
Fetch images with WADO-RS.
Display with OHIF Viewer / cornerstone.js.

### Linked Timeline
Show labs + images together in a timeline.
Example: “Lab X drawn on 01/01/2025” → “MRI performed on 01/03/2025”.

🔗 Tutorials & Tools to Build This
* FHIR CRUD: Simple FHIR Tutorial
* HL7 v2 parsing: hl7apy (Python) or nHapi (.NET)
* FHIR Server: HAPI FHIR
* DICOM Server: Orthanc
* DICOMweb Client (JS): dicomweb-client
* Viewer: OHIF Viewer


To-do
* Review Fire information related to 