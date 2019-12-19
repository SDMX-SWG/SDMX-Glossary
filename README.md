<center> <h1> SDMX GUIDELINES </h1> </center>

# SDMX GLOSSARY 
## VERSION 2.0 - AUGUST 2018

DOCUMENT HISTORY

|Version|Description|
|---|---|
|Version 1.0	|Finalised in February 2016|
|Version 2.0	|Finalised in August 2018|
|Version 2.1	|Added “Recommended uses and limitations”, “Technical notes”. Updates to existing termss|


## INTRODUCTION
The SDMX Glossary is an SDMX guideline containing concepts and related definitions that are useful for building and understanding data and metadata exchange arrangements based on SDMX. The Glossary provides definition of terms found in the SDMX Information Model, Data Structure Definitions  (DSDs), and Metadata Structure Definitions (MSDs) at the time of the present release. It is recommended as a single entry point to a common SDMX terminology to be used in order to facilitate communication and understanding of the standard.
In short, the overall message of the glossary is the following: if a term is used, then its precise meaning should correspond to the SDMX Glossary definition, and any reference to a particular phenomenon described in the SDMX Glossary should use the appropriate term.
The glossary is not intended to cover the whole range of statistical terminology, as this area is already covered by other general or domain-specific glossaries. The focus of the glossary is largely those terms that are normally used for building and understanding metadata systems and SDMX data exchange arrangements.

## BUSINESS CASE FOR THE ADOPTION OF CROSS-DOMAIN CONCEPTS (CDCS)
In the SDMX framework, "Cross-domain concepts" are Concepts relevant to several, if not all, statistical domains. SDMX recommends the use of these concepts, whenever feasible, in SDMX data and metadata structures and messages in order to promote re-usability and exchange of statistical information and their related metadata between organisations. Whenever used, these Concepts should conform to the specified names, ID, Representations and Codelists defined in the SDMX Content-Oriented Guidelines.
Cross-Domain Concepts (CDCs) are useful for exchanging data and metadata between multiple agencies and statistical subject-matter domains.
The CDCs, if adhered to by international organisations and national institutions, promote the:
- efficient exchange of data and related structural and reference metadata by interlinking statistical information systems of organisations, in spite of technological or linguistic differences that might exist between them from their internal perspectives;
- exchange of consistent metadata that can be used by different international organisations and national and regional data-producing agencies to compare concepts and practices; 
- re-usability of exchange messages from an institution to other institutions, thereby reducing the overall data and metadata reporting burden.

ATTRIBUTES USED FOR DESCRIBING CONCEPTS LISTED IN THE GLOSSARY

|Name|Description|
|---|---|
|Term*	|Name of the concept. The term should preferably be entered in the singular form and upper cases should be avoided to the largest extent possible.|
|Definition*	|Short statement explaining the meaning of the concept. This textual description of the concept should answer the question "What is it?" rather than "How is it done?" or "Why do we have it?, etc. It is recommended to keep definitions short and add any explanatory text under field "Context".|
|Context	|Complementary information on the background, history, use, status, etc. of the concept. This field is used to add information on how and where the term may be used. It describes SDMX use cases for the term and may contain examples of its use. This field is optional, though strongly recommended.|
|Type	|Used to explicitly denote concepts which are cross-domain.|
|Concept ID*	|Unique identifier for the concept that allows it to be unambiguously used for machine-to-machine exchange.|
|Recommended representation	|Recommended type of value for the concept term. Examples are "primitive" types such as string (i.e. free text), or complex types such as Codelist, that is used for those terms that have an associated Codelist in Codelist ID. There may be more than one recommended type; in this case, the first type is recommended over the others. For time types, it could be possible to use a more precise representation of time than the recommended type (e.g. Reporting Time Period instead of Observational Time Period). |
|Codelist ID	|Unique identifier for the Codelist associated with the Concept. Most often it is the term's Concept ID prefixed by "CL_". For example, the "Observation Status" term has the Concept ID of OBS_STATUS, and the Codelist ID of CL_OBS_STATUS. This attribute is used only if the concept's "Recommended representation" includes "Codelist".|
|Related terms	|Entries in the SDMX Glossary that are closely associated with the concept term. It is possible here to create relationships between concepts, e.g. between "Reference metadata" and "Structural metadata". No hierarchy is created between the concepts linked, i.e. if a link is established between "Reference metadata" and "Metadata", a similar link will be established between "Metadata" and "Reference metadata".|
|Source	Source |information from which the definition was extracted. The reference must be as complete as possible. When available, the source is followed by a hyperlink, i.e. a link to the source material for the term.|
|Other link(s)	|Link(s) to material that is related, closely or loosely, to, but not directly associated with the concept source of the term, e.g. link to a general methodological document.|

\* Denotes mandatory fields

## CONTACT ADDRESS
For any question, comment or correction, feel free to contact the SDMX Statistical Working Group (SWG) at the following address: swg@sdmx.org. 
