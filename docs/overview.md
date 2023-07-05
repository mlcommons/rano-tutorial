# Tutorial: How to run an AI study in a clinical setting using GaNDLF and OpenFL on MedPerf

The aim of this tutorial is to provide a detailed description on running a clinical AI study across multiple sites using GaNDLF and OpenFL on MedPerf. At the end of the tutorial, depending on your organization’s role, you should be comfortable with understanding what a clinical AI study is, how to curate medical data, how to prepare data for ingestion by the machine learning (ML) experiments, how to train ML models on multiple distributed sites using Federated Learning, and finally how to perform evaluation on these sites using Federated Evaluation.

*Important: At its current stage this tutorial does not take into consideration the health IT system complexities (e.g. databases, storage, networking) that affect mainly data extraction. It tries to abstact it from these complexities and focus on the machine learning aspects of the clincal AI study.*

## Roles

### Healthcare IT expert
In the context of this tutorial a healthcare IT expert has the following responsibilities: 
* Understands healthcare organization network specifications and requirements, 
* Installs and sets up containerized software on a local server, 
* Understands and provides secure outgoing network communication with an external orchestrator server. 

### Clinical expert
In the context of this tutorial, a clinical expert has the following responsibilities:
* Defines the clinical study: a clinical problem, expected input and output of the AI model, data acquisition (inclusion & exclusion criteria), annotation protocol,
* Provides clinical expertise to the other stakeholders (i.e. healthcare IT expert, machine learning engineer),
* Provides data annotations according to the annotation protocol,
* Provides feedback and issues to other stakeholders

### Machine learning engineer
In the context of this tutorial, a machine learning engineer has the following responsibilities:
* Communicates with other stakeholders
* Prepares ML pipeline and experiments
* Helps setup necessary tools related to this tutorial

## Roadmap to achieving the goals
- *Provide source code examples through a use case: BrATS*
- *Add pictures pics (e.g. gifs) Check out killercoda*
