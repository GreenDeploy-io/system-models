# Product CRUD

Inspired by conversation at https://discord.com/channels/1118241178723291219/1235599570340151316/1244939749299322911

The purpose is to create software-design inputs and then use LLMs to generate code as output.

The primary hypothesis is that if the inputs are of a formal and rationalized type, the LLMs will generate better code results.


## Secondary hypotheses

There are multiple secondary hypotheses. Invalidating any one of them need not invalidate the rest.

1. Systems engineering model methodologies such as SysML, or UML, would be the ideal formal and rationalized type for inputs.
2. The top candidates for modeling methodology chosen in descending order: OPM (Object-Process Methodology), and SysML. The reasons of choosing them will be elaborated in a separate section.
3. LLM with RAG alone is insufficient. The hypothesis is that a graph-based prompting is needed as well. So [synalinks' hybridAGI](https://github.com/SynaLinks/HybridAGI) is the top candidate for this.

## Minimum viable use case

Inside ProductCRUD folder, both SysML and OPM sample inputs are available for the following use case.

1. Create a Product via a form with just its Title and Description
2. the tech stack is a regular Django web app

- Under `ProductCRUD/SysML`, there's a ProductCRUD.xmi file
- Under `ProductCRUD/OPM`, there's a separate md file to hold the diagrams in picture form and the OPL (Object-Process Language) in text form.

