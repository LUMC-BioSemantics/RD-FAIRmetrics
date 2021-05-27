# TITLE:  FAIR Maturity Indicator RD-R1

## Authors:
Mark D. Wilkinson, ORCID:0000-0001-6960-357X
Marc Hanauer, ORCID:0000-0002-6758-2506
Marco Roos, ORCID:0000-0002-8691-772X
Rajaram Kaliyaperumal, ORCID:0000-0002-1215-167X
Annika Jacobsen, ORCID:0000-0003-4818-2360
Núria Queralt Rosinach, ORCID:0000-0003-0169-8159

#### Publication Date: 2021-05-26
#### Last Edit: 2021-05-26
#### Accepted: pending


### Maturity Indicator Identifier: RD-R1 [https://w3id.org/rd-fairmetrics/RD-R1](https://w3id.org/rd-fairmetrics/RD-R1)

### Maturity Indicator Name: Use of Rare Disease (RD) specific ORDO or HPO ontologies in the metadata
----

### To which principle does it apply?  
R1

### What is being measured?
Pointers in the metadata document to ORDO or HPO terms

### Why should we measure it?
Metadata that does not comply with the ORDO or HPO specific RD standards, will often render to a ‘reuseless’ dataset by the RD community because information about its content is missing.

### What must be provided for the measurement?
The Metadata GUID.


### How is the measurement executed?
Metadata is gathered following an extensive pipeline including content negotiation for linked data, following appropriate Link meta elements in the headers and HTML, and parsing to extract embedded metadata (pipeline fully explained elsewhere).  The resulting combined metadata record is searched for RDF triples where the Object of the triple is a Resource, whose string-form matches "http://purl.obolibrary.org/obo/HP_" or "http://www.orpha.net/ORDO/" by regular expression matching.


### What is/are considered valid result(s)?
One or more of either or both matches is considered a success.  Test returns binary 1 (success) or 0 (failure)


### For which digital resource(s) is this relevant? (or 'all')
RD digital resources

### Examples of good practices (that would score well on this assessment)
http://fdp.duchennedatafoundation.org:8080/dataset/d877ac76-87ba-461f-803b-3a8a90a2e965

### Comments
This test assesses the presence of RD specific ontologies used by the EJP RD community.

