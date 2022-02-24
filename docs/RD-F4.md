# TITLE:  FAIR Maturity Indicator RD-F4

## Authors:
Núria Queralt Rosinach, ORCID:0000-0003-0169-8159
Rajaram Kaliyaperumal, ORCID:0000-0002-1215-167X
Vincent Emonet ORCID:0000-0002-1501-1082
Karolis Cremers ORCID:0000-0002-1756-3905
Matthijs Sloep ORCID:0000-0003-3602-1885
César Henrique Bernabé ORCID:0000-0003-1795-5930

#### Publication Date: 2022-01-13
#### Last Edit: 2022-01-13
#### Accepted: pending


### Maturity Indicator Identifier: RD-F4 [https://w3id.org/rd-fairmetrics/RD-F4](https://w3id.org/rd-fairmetrics/RD-F4)

### Use of Rare Disease (RD) specific Search Engines to find the (meta)data of the indexed resource.
----

### To which principle does it apply?  
F4

### What is being measured?
We extract the title property of the resource from the metadata document and check if the RD specific search engine returns the metadata document of the resource that we are testing.

### Why should we measure it?
To test if the resource is Findable using RD specific search engines used by the community.

### What must be provided for the measurement?
The Metadata GUID.


### How is the measurement executed?
The test checks if the title property of the resource provided returns any result in the FAIR Data Point Index search. If so, we compare the results with the URI provided for testing, checking if the URI is contained in the results from the FDP Index. If True, the test passes.


### What is/are considered valid result(s)?
One or more of the matches is considered a success. Test returns binary 1 (success) or 0 (failure)


### For which digital resource(s) is this relevant? (or 'all')
RD digital resources

### Examples of good practices (that would score well on this assessment)
https://w3id.org/ejp-rd/fairdatapoints/wp13/dataset/c5414323-eab1-483f-a883-77951f246972

### Comments
Right now we included only the FAIR Data Point Index as search engine, but in the future we plan to include other catalogs (e.g., Orphanet catalog).

