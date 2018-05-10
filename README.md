This git repository is made to publish some graphs built in the SemBib project
(http://givingsense.eu/sembib/)

See also some posts in
https://onsem.wp.imt.fr/presentation/
like
https://onsem.wp.imt.fr/2018/04/05/where-telecom-paristech-publishes-regularly/

Graphs are saved with the graph store protocol

For example, the graph
http://givingsense.eu/sembib/onto/tpt/biblio

is saved with the request
http://!private access point!/sembib/get?graph=http://givingsense.eu/sembib/onto/tpt/biblio

Available dumps:
* givingsense.eu_sembib_onto_channels.ttl	: graph for venues description
* givingsense.eu_sembib_onto_graphs.ttl : graph listing graohs in SemBib
* givingsense.eu_sembib_onto_persons.ttl : graph describing persons and organizations
* givingsense.eu_sembib_onto_slov.ttl	: graph with a sample domain vocabulary
* givingsense.eu_sembib_onto_tpt_biblio.ttl	: graph describing publications of Telecom ParisTech (TPT)