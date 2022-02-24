This folder is for examples to test a customized HAPI codebase to implement [FHIR Terminology Service](https://hl7.org/fhir/R4/terminology-service.html)

The goal for this first test example is to be able to run the FHIR validator against [this R4 Observation example](http://hl7.org/fhir/r4/observation-example-f001-glucose.json.html) and have the example validated with the HAPI instance acting as a terminology server instead of http://tx.fhir.org.

All that is needed for this validation is:
* 15074-8 is in CS http://loinc.org
* mmol/L is in CS http://unitsofmeasure.org
