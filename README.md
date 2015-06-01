GROUND TRUTH USED IN PAPER: http://dx.doi.org/10.1145/2764947.2764953

This is ground truth relies on IR benchmark from the ImageCLEF2011: http://www.imageclef.org/2011/Wikipedia

This ground truth identifies, for each query of the benchmark:
	a) A set of Wikipedia articles that are mentioned in the queri's topic: <input>ARTICLES</input>
	b) A set of Wikipedia articles whose titles in case of being used as expansion features retrieves 
	   the best results for the query according to the ImageCLEF2011: <article_nodes>ARTICLES</article_nodes>

Retrieval has been tested using INDRI (http://www.lemurproject.org/indri/) search engine.
Indri queries are build using the COMBINE operator and exact matching operator. Titles that have a clarification 
in brackets (eg. Grand Canal (Venice) ) are dispossessed of it. (eg. Grand Canal).

The rest of the nodes (categories and main articles), as well as the connections among the different
type of nodes, can be induced directly from Wikipedia.
