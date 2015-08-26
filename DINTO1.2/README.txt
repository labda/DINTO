Version: DINTO 1.2
Launched: June 2015

DINTO 1.2 is an extended version of DINTO 1 that includes information about adverse drug reactions (ADRs) and their relationships to pharmacological entities included in the ontology. To create this version, we have imported a reduced version of the Ontology for Adverse Events (OAE version 1.1.247), including only the top class 'adverse event' and its subclasses. In addition to this, we have imported drug-ADR relationships for the database SIDER, which can be used with SWRL rules to infer DDIs occurring by the addition of a common ADR.

In addition to this, addional material includes:
    
DINTO 1.2 subset: This file contains the subsets of the ontologies reused to be imported in DINTO.
      OAE_DINTO_subset.owl is the fragment imported from the Ontology of Adverse Events (OAE) to DINTO.

DINTO 1.2 reduced version: This file contains the reduced version of DINTO 1.2 and the SWRL rule used to infer possible ADRs.
      DINTO_1.2_IExp4.owl
Experiments using this version and rule are described in:
        Herrero-Zazo, María; Segura-Bedmar, Isabel; Hastings, Janna; Martínez, Paloma (2015). DINTO: Using OWL ontologies and SWRL rules to infer drug-drug interactions and their mechanisms. Journal of Chemical Information and Modeling. Just Accepted Manuscript. DOI: 10.1021/acs.jcim.5b00119