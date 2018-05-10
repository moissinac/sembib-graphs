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
* givingsense.eu_sembib_onto_graphs.ttl : graph listing graphs in SemBib
* givingsense.eu_sembib_onto_persons.ttl : graph describing persons and organizations
* givingsense.eu_sembib_onto_slov.ttl	: graph with a sample domain vocabulary
* givingsense.eu_sembib_onto_tpt_biblio.ttl	: graph describing publications of Telecom ParisTech (TPT)

Accociated SPARQL access points:
* http://givingsense.eu/sembib/sparql/  (based on ARC2, limited support of sparql)
* https://ws49-cl4-jena.tl.teralab-datascience.fr/dataset.html?tab=query&ds=/sembib (based on Fuseki))

Sample requests:
see https://gist.github.com/moissinac

For example:
https://gist.github.com/moissinac/c6045b5eb052ca7bf4aab34f0c1a2427
which gives a small list of graphs, where
<http://givingsense.eu/sembib/onto/tpt/biblio>
could concern a bibliography.
Then
https://gist.github.com/moissinac/5ff5ab9db1fb51ddd33997274ce8ff4f
gives one and only one type in the ‘biblio’ graph
<http://purl.org/spar/fabio/ResearchPaper>
(also known as fabio:ResearchPaper)
How many papers are in the ‘biblio’, the request
https://gist.github.com/moissinac/1fba003e674cbd8bb31da64c9dfade8a
gives 11607
which is the count of papers in the original database at the date of the query.

