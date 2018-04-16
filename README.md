# ESO: The Event and Implied Situation Ontology.  

This repository contains the Event and implied Situation Ontology (ESO). 
This is version 2.0 (stable), which was developed for [the NewsReader Project](http://www.newsreader-project.eu/).

## Resource Description
The Event and Implied Situation Ontology (ESO.owl), is a manually constructed resource which formalizes 
the pre-, during-, and post-situations of *events* and the *roles* of the entities affected by an event. 

The ontology is used to detect information in large natural language document collections that otherwise would 
have remained implicit. 

A *situation* is seen here as some abstract state where some properties and property values hold. 
If something happens in the world, there is a change in at least some of the values of these properties.
For instance: an event associated with the concept or class eso:Buying will have a two cognitive agents carrying the role of
owner-1 and owner-2, some object and some financial asset (usually money). ESO models and infers the following:

*Before the buying event: owner-1 has the object but not the money; owner-2 has the money but not the object.
*During the buying event: there is an exchange of object and money where the money expresses the value of the object.
*After the buying event: owner-1 has the money but not the object; owner-2 has the object but not the money.

### Prerequisites
ESO is fully mapped to [SUMO](http://www.adampease.org/OP/) on class level and to [FrameNet](https://framenet.icsi.berkeley.edu/fndrupal/) on class and role level. 
As an input, ESO needs Semantic Role Labeled annotation based on FrameNet. An additional vocabulary with manually created WordNet-FrameNet-ESO 
mappings is provided too.

If you have PropBank, VerbNet or SemLink annotated data, I refer to the [Predicate Matrix](http://adimen.si.ehu.es/web/PredicateMatrix), 
a resource developed by Maddalen Lopez de Lacalle, Egoitz Laparra and German Rigau, IXA Group, Basque University.

### Contents ESO

ESO is developed for the automotive and financial domain. It contains: 63 event classes; 123 situation rule assertions;
58 properties; 65 roles. Further, 46 SKOS mappings to SUMO classes; 103 SKOS mappings to FrameNet frames and 131 to Frame Elements (roles).


## Repository Description





## Acknowledgements:
This work was co-funded by:
- The European Union - FP7 Work Programme Call FP7-ICT-2011-8 – Objective Cooperation – Research theme 
Information and Communication Technologies, challenge 4.4 - Area Intelligent Information Management – 
- Netherlands Organization for Scientific Research (NWO) via the Spinoza grant, 
awarded to [Piek Vossen](http://vossen.info/) in the project [Understanding Language by Machines](http://www.understandinglanguagebymachines.org/)


If you use this resource, please cite:

Segers R., M. Rospocher, P. Vossen, E. Laparra, G. Rigau, A. Minard. *The Event and Implied Situation Ontology: Application and Evaluation.* 
In: Proceedings of the 10th edition of the Language Resources and Evaluation Conference (LREC2016), 
Portoroz, Slovenia, May 23-28 2016. 




## Publications using ESO

If you use ESO, please send me a message so I can update this list.

* LREC paper
* ....


## Provenance of this repository
This repository is an adapted clone of this original [repository](https://github.com/newsreader/eso-and-ceo).
Cloned an adapted in April 2018.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Event and Implied Situation Ontology (ESO)</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Roxane Segers and Marco Rospocher</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/RoxaneSegers/ESO-Ontology" rel="dct:source">https://github.com/RoxaneSegers/ESO-Ontology</a>.


