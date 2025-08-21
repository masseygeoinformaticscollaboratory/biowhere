# Datasets for the BioWhere Project

This directory contains manually annotated datasets prepared for training, validation, and testing of models developed 
to georeference New Zealand biota from text.

The datasets included in this directory as follows:

| Dataset name                                                | Description                                                                                                                     |
|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| NZ Georefs For Biowhere Training and Testing/NZ Georefs.csv | Biological collection records with manually verified coordinates and uncertainty                                                |
| NZ Georefs For Biowhere Training and Testing/NZ Places.csv  | New Zealand places found in GBIF records with manually verified coordinates and uncertainty                                            |
| NZ Georefs For Biowhere Training and Testing/Distinct Localities (BELS).csv | Distinct values of the v_locality field from the BELS gazetteer snapshot from records that had an interpreted_country_code 'NZ' |
| NZ Georefs For Biowhere Training and Testing/NZ Georefs w_ Protocol (BELS).csv | New Zealand localities from BELS gazetteer snapshot records that has a valid georeferencing protocol  |
| NZ Georefs For Biowhere Training and Testing/NZ Verified Georefs (BELS).csv | New Zealand localities from BELS gazetteer snapshot records that has a acceptable verification status  |

### References

* [Georeferencing Best Practices](https://docs.gbif.org/georeferencing-best-practices/1.0/en/#introduction)
* [Darwin Core Quick Reference Guide](https://dwc.tdwg.org/terms/)
* [Georeferencing calculator](https://georeferencing.org/georefcalculator/gc.html) 
* [Georeferencing Quick Reference Guide](https://docs.gbif-test.org/georeferencing-quick-reference-guide/1.0/en/) 
