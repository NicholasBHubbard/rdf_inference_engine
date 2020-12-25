-*- mode:org;mode:auto-fill;fill-column:75 -*-
* Overview
Static inference engine powered by SWI-Prolog for the RDFS-Plus modelling language
defined in [[https://workingontologist.org/index.html][Semantic Web for the Working Ontologist]]. 

* Features
  + Static inference engine 
  + Parse [[https://en.wikipedia.org/wiki/Turtle_(syntax)][turtle]] files into pure rdf
  + Performs contradiction analysis
  + /tbd/

* Workflow
Simply run your turtle files against NAME_TBD and you will either get error
messages about all the mistakes you have made, or you will get a new file with a
/.inferred/ extenstion that is a copy of the original file with all
inferred triples appended.

* TODO TODO 
** TODO Modeling Constructs: [1/14]
    - [X] rdfs:subClassOf
    - [ ] rdfs:subPropertyOf
    - [ ] rdfs:domain
    - [ ] rdfs:range
    - [ ] owl:equivalentClass
    - [ ] owl:equivalentProperty
    - [ ] owl:FunctionalProperty
    - [ ] owl:InverseFunctionalProperty
    - [ ] owl:sameAs
    - [ ] owl:inverseOf
    - [ ] owl:SymmetricProperty
    - [ ] owl:TransitiveProperty
    - [ ] owl:DatatypeProperty
    - [ ] owl:ObjectProperty
      
             
