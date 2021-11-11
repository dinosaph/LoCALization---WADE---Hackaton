# LoCALization---WADE---Hackaton

Turtle RDF data:
![alt text](/media/rdf-grapher.png)

Used:
- visualization: https://www.ldf.fi/service/rdf-grapher
- data: https://www.dbpedia.org/
- sparql tries: https://sparql-playground.sib.swiss/, https://dbpedia.org/sparql
> work-in-progress
> 
> select distinct ?person where
{?person a dbo:Person . ?person dbo:genre ?genre . ?genre a dbr:Country_music . }
LIMIT 100
