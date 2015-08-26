This file contains the reduced versions of DINTO used in different experiments performed to evaluate and demonstrate its usefulness in several applications.

DINTO 1 subsets: This file contains the subsets of the ontologies reused to be imported in DINTO
        BRO_DINTO_subset.owl is the fragment imported from the Biomedical Resource Ontology (BRO) to DINTO.
        PKO_DINTO_subset.owl is the fragment imported from the Pharmacokinetics Ontology (PKO) to DINTO

DINTO 1 SWRL rules: This file contains the SWRL rules used to infer new information in DINTO
        DINTO_rules_inferenceDDI.owl is the file containing the 59 SWRL rules created to infer DDIs in DINTO.
        DINTO_rules_inferenceDDI_types.owl is the file containing the 59 SWRL rules created to infer types of DDIs in DINTO.
Experiments using these rules are described in:
        Herrero-Zazo, María; Segura-Bedmar, Isabel; Hastings, Janna; Martínez, Paloma (2015). DINTO: Using OWL ontologies and SWRL rules to infer drug-drug interactions and their mechanisms. Journal of Chemical Information and Modeling. Just Accepted Manuscript. DOI: 10.1021/acs.jcim.5b00119
        Herrero-Zazo, María. PhD Dissertation. "Semantic Resources in Pharmacovigilance: a Corpus and an Ontology for Drug-Drug Interactions" (2015) Universidad Carlos III de Madrid.

DINTO 1 inferred classification: This file contains the two versions used to generate and store, respectively, the inferred classification of DDIs described in DrugBank in basis of their mechanisms.
        DINTO_inf_classification.owl is a reduced version of DINTO 1 containing only the classes ‘drug interaction’ and ‘DDI mechanisms’ and their subclasses. Using the reasoner engine FacT++ in this reduced version we obtained the inferred classification of DDIs.
        DINTO_inf_classification2.owl is a version including the inferred axioms exported as a new ontology. From this version, we deleted those classes not necessary to show the inferred classification, keeping only the classes ‘DDI’, 'DDI described in DB' and its sublclasses, ‘pharmacodynamic DDI’ and its subclasses and ‘pharmacokinetic DDI’ and its subclasses. The inferred version can be imported in DINTO 1 to integrate the inferred classification within the whole ontology.

DINTO 1 reduced versions: This file contains the reduced versions of DINTO used in different experiments.
        DINTO_inf_mech.owl is the version of DINTO intended to be used with a reasoner engine to obtain and inferred classification of DDIs on the basis of their inferred mechanisms.
        DINTO_SEMEVAL2_inf.owl is the version of DINTO created to be evaluated in the framework of the SemEval-2013 DDI Extraction task. It contains the DDIs inferred using a reasoner for a reduced number of pharmacological entities.
Experiments using these versions are described in:
        Herrero-Zazo, María; Segura-Bedmar, Isabel; Hastings, Janna; Martínez, Paloma (2015). DINTO: Using OWL ontologies and SWRL rules to infer drug-drug interactions and their mechanisms. Journal of Chemical Information and Modeling. Just Accepted Manuscript. DOI: 10.1021/acs.jcim.5b00119
        Herrero-Zazo, María; Segura-Bedmar, Isabel; Hastings, Janna; Martínez, Paloma (2015). Application of Domain Ontologies to Natural Language Processing: A Case Study for Drug-Drug Interactions. (2015) International Journal of Information Retrieval Research (IJIRR). 5(3), 19-38.
        Herrero-Zazo, María. PhD Dissertation. "Semantic Resources in Pharmacovigilance: a Corpus and an Ontology for Drug-Drug Interactions" (2015) Universidad Carlos III de Madrid.


