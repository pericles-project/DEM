# Digital Ecosystem Model Ontology
The DEM is an ontology that uses the Web Ontology Language (OWL). A DEM supports the analysis and management of a Digital Ecosystem. A Digital Ecosystem (DE) should be interpreted as a concept with the purpose for analysing and modelling the ability of infrastructure to maintain the usefulness of digital objects. A digital ecosystem consists of a set of the entities and dependencies influencing or necessary for a successful use at a later point in time.

It provides a flexible mechanism to analyse dependencies between a broad range of entities. The aim of a DEM is to analyse a DE, perform or simulate changes in advance, determine the impact of a change and create relations from old to new semantic concepts.  In case of unplanned changes, the DEM can be used to determine the impact of unpredicted failures and to mitigate further risks.

## Reasons for modelling a DE
The DEM provides a representation of the DE landscape with dependencies between a wide range of different entities and change types. It can be used for comprehension of a DE, justification of planned changes and design decisions. There is also change in a wider context that needs to be considered:
*	expectations, requirements and background knowledge of user communities can change
*	organisations can merge
*	introduction of new policies
*	exchange of Digital Objects with other organisations or communities
*	processes and workflows may change 
*	technical infrastructure evolves and dependencies can be quite intricate given the growing dependency on external and networked services. The impact of these changes needs to be evaluated
*	change in larger social or cultural contexts such as laws, disciplines or cultural norms may require adaption of a DE 

The DEM allows simulation of planned change for mitigating risks and offers a recording and comparison of the implemented change and in case of an unplanned change the impact on the DE can be determined. 

## File structure
The ontology files are available as Turtle and RDF/XML and have the following purpose:

* DEM-Core.ttl/owl: The core model consists of five main entity types (Digital Object, Process, Policy, Technical Service and User Community which allow to define basic principles that are valid for all inheriting entities of the model. It contains also a few helper components
* DEM-Analysis.ttl/owl: The DEM can be seen as a multigraph. The DEM Analysis model provides entities and special relations for edges.
* DEM-Infrastructure.ttl/owl: The DEM Infrastructure model has the purpose to model infrastructure components such as hardware and software, interfaces and the corresponding agents
* DEM-Policy.ttl/owl and SCAPE-Preservation.ttl/owl: Allows to record detailed policies including policies for digital preservation, which are based on the SCAPE project.
* DEM-Process.ttl/owl: The purpose of the DEM Process model is to capture which Ecosystem entity is processed by a certain process and which Ecosystem Agent is part of the process

# Supporting tool EcoBuilder

The [EcoBuilder](https://github.com/pericles-project/ecobuilder) tool will facilitate the simple creation of Digital Ecosystem Models for user scenarios. It provides a GUI for creating Ecosystem Models and an API.

# License

Apache 2.0

# Documentation

The full reference of the Digital Ecosystem Model can be found in the <a href="http://pericles-project.eu/deliverables/75">PERICLES Deliverable 3.5</a>. A short reference is available under the <a href="https://github.com/pericles-project/DEM/wiki">GitHub Wiki pages</a>.
There is also a paper of the Digital Ecosystem Model which has been presented on <a href="http://medes.sigappfr.org/16/">8th International ACM Conference on Management of Digital EcoSystems (MEDES'16)</a>. 

# Credits

 _This project has received funding from the European Union’s Seventh Framework Programme for research, technological development and demonstration under grant agreement no FP7- 601138 PERICLES._   
 
 <a href="http://ec.europa.eu/research/fp7"><img src="https://github.com/pericles-project/pet/blob/master/wiki-images/LogoEU.png" width="110"/></a>
 <a href="http://www.pericles-project.eu/"> <img src="https://github.com/pericles-project/pet/blob/master/wiki-images/PERICLES%20logo_black.jpg" width="200" align="right"/> </a>

<a href="http://www.sub.uni-goettingen.de/"><img src="https://github.com/pericles-project/pet/blob/master/wiki-images/sub-logo.jpg" width="300"/></a>
