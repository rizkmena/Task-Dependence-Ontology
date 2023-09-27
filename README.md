# Task-Dependence-Ontology

This repository contains the full specification and implementations of the Task Dependence Ontology. The ontology was first introduced in a paper titled ``Towards an Ontology of Task Dependence'' in KEOD 2023.

Four files are contained in this repository:
- ```task_dependence_ontology_axioms.pdf```: Presents the formal model in first-order logic, accompanied by English descriptions of each axiom.
- ```tdo_axioms.in```: Prover9 implementation of the entire axiomatization for usage in Prover9/Mace4. 
- ```tdo_instance.in```: Prover9 implementation of the scenario captured in the Application section of the paper, for the purposes of model validation. Instance assertions are at the end of the file.
- ```tdo.owl```: OWL (and SWRL) implementation of the task dependence ontology specification (detailed in ```task_dependence_ontology_axioms.pdf```)
- ```tdo_instance.owl```: OWL (and SWRL) implementation of the task dependence ontology specification (detailed in ```task_dependence_ontology_axioms.pdf```) with all instance assertions for the scenario presented in the Application section of the paper.
- ```paper.pdf```: A copy of the paper.
