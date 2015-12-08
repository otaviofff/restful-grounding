RESTful Grounding Ontology
==========================

RESTful Grounding was the very first Web Ontology to allow the semantic description of RESTful Web Services. It was originally published in the Proceedings of IADIS International Conference WWW/Internet (ICWI), back in November 2009, in Rome. 

This ontology was authored by two Brazilian researchers, from the University of Sao Paulo (USP) - Engineering School, as part of their master thesis on RESTful Semantic Web Services: 

* Otavio Freitas Ferreira Filho
* Maria Alice Grigas Verella Ferreira

Abstract
-------

The proposal is to allow the development of semantic Web services according to an architectural style called REST. More specifically, it considers a REST implementation based on the HTTP protocol, resulting in RESTful Semantic Web Services. 

The development of semantic Web services has been the subject of various academic papers. However, the predominant effort considers Web services designed according to another architectural style named RPC, mainly through the SOAP protocol. The RPC approach, strongly stimulated by the enterprise software industry, aggregates unnecessary processing and definitions that make Web services more complex than desired. Therefore, services end up being not as scalable or fast as possible. 

In fact, REST services form the majority of Web services currently developed on the social Web, an environment focused on user-generated content and networking, clearly stronger and more predominant than others.  

The proposal presented here makes use of a specific selection of existing languages and protocols, reinforcing its feasibility. Firstly, OWL-S is used as the base ontology for services, whereas WADL is for syntactically describing them. Secondly, the HTTP protocol is used for transferring messages; defining the action to be executed; and also defining the execution scope. Finally, URI identifiers are responsible for specifying the service interface. 

The final compilation proposed results in an ontology named RESTfulGrounding, which extends OWL-S (Ontology Web Language for Services).
