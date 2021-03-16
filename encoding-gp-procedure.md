# Procedure for alternative encodings of INSPIRE data

## Introduction
This procedure describes the approach to be followed for encoding INSPIRE data in accordance with the IR through the use of alternative encodings.

Open Question: are (i) additional encoding and (ii) extended INSPIRE models in scope? 

## Approach

### Principles
- A stepwise approach is envisioned for encoding the data. 
- The same approach is applied for all alternative encodings
- Should there be different proposals for the encoding of data for the same data model/theme the changes are discussed (i) between the proposers, and if needed (ii) within the context of the temporary sub-group [2.3.1 'Governance of INSPIRE Artefacts'](https://webgate.ec.europa.eu/fpfis/wikis/display/InspireMIG/Action+2.3+Simplification+of+INSPIRE+implementation).

### Step 1. Data encoding
Data should be encoded through the alternative encoding (e.g. GPKG or GeoJSON) by following the (i) INSPIRE UML models, (ii) model transformation rules and (iii) the encoding-specific rules.

### Step 2. Mapping to the default encoding
Once the data instances are available, mapping to the default INSPIRE encoding (XML) should be made available online through at least one of the following means:
- [INSPIRE Matching tables](https://inspire.ec.europa.eu/data-model/approved/r4618-ir/mapping/)
- Executable transformation script, incl. software-specific approaches that can be replicated.

### Step 3. Data validation
Confirming the approach through the [INSPIRE reference validator](https://inspire.ec.europa.eu/validator/) can be achieved through deriving and validating GML instances based on the mapping performed in Step 2. The GML instances and the test report from the INSPIRE reference validator (html) should be made available.


## Update to the glossary
- Additional encoding
- Alternative encoding
- Default encoding
- Model-transformation rules
- Encoding-specific rules
