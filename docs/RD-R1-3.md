# TITLE:  FAIR Maturity Indicator RD-R1.3

## Authors:
Rajaram Kaliyaperumal, ORCID:0000-0002-1215-167X
Núria Queralt Rosinach, ORCID:0000-0003-0169-8159
Matthijs Sloep, ORCID:0000-0003-3602-1885
Karolis Cremers, ORCID:0000-0002-1756-3905


#### Publication Date: 2022-01-20
#### Last Edit: 2022-01-20
#### Accepted: pending


### Maturity Indicator Identifier: RD-R1.3 [https://w3id.org/rd-fairmetrics/RD-R1-3](https://w3id.org/rd-fairmetrics/RD-R1-3)

### Maturity Indicator Name: Use of Rare Disease (RD) specific EJP RD DCAT-based metadata model.
----

### To which principle does it apply?  
R1.3

### What is being measured?
We measure whether the metadata of the resource conforms to the EJP RD DCAT-based metadata semantic model.

### Why should we measure it?
To test if the resource is following the rare disease community standard for metadata description.

### What must be provided for the measurement?
An RDF/Turtle file format containing the metadata triples of the resource tested.

### How is the measurement executed?
We will check the metadata content of the resource against the EJP RD ShEx shapes to validate the triples of the resource.

### What is/are considered valid result(s)?
No failures in the ShEx validation is considered a success; Test returns binary 1 (success) or 0 (failure).

### For which digital resource(s) is this relevant? (or 'all')
RD digital resources

### Examples of good practices (that would score well on this assessment)
https://w3id.org/ejp-rd/fairdatapoints/orphanet-catalog-fdp/patientRegistry/b6a6bdad-6233-4b44-9b5a-5b26eb020eeb

### Comments
Right now we included only the patient registry metadata model from EJP RD, but in the future we are planning to include more metadata models from other projects in the rare disease domain, e.g. bioschema.org.
