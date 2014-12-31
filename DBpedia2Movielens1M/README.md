
DBpedia-To-MovieLens1m
=======================

Description
-----------

This file contains the mappings between the movies in the MovieLens1M dataset to the correspondent DBpedia resources (DBpedia v3.9). 
The MovieLens1M dataset is published by GroupLeans research group (http://www.grouplens.org/datasets/movielens/).

The MappingDBpedia2Movielens.tsv mapping file is formatted one entry per line as follows (tab separated, "\t"):  
ML_id	ML_name	DBpedia_URI  
An example of mapping is the following:  
858	Godfather, The (1972)	http://dbpedia.org/resource/The_Godfather   
	
We did not find a mapping for all the movies in MovieLens1M. We found a valid mapping for 3156 of them.

References
----------
   
If you use these mappings in your scientific work, please cite as

 @inproceedings{DiNoia:2012:LOD:2362499.2362501,  
 author = {Di Noia, Tommaso and Mirizzi, Roberto and Ostuni, Vito Claudio and Romito, Davide and Zanker, Markus},  
 title = {Linked Open Data to Support Content-based Recommender Systems},  
 booktitle = {Proceedings of the 8th International Conference on Semantic Systems},  
 series = {I-SEMANTICS '12},  
 year = {2012},  
 isbn = {978-1-4503-1112-0},  
 location = {Graz, Austria},  
 pages = {1--8},  
 numpages = {8},  
 url = {http://doi.acm.org/10.1145/2362499.2362501},  
 doi = {10.1145/2362499.2362501},  
 acmid = {2362501},  
 publisher = {ACM},  
 address = {New York, NY, USA},  
 keywords = {DBpedia, LinkedMDB, content-based recommender systems, freebase, linked data, movielens, precision, recall, semantic web, vector space model},  
}   

or

@inproceedings{Ostuni:2013:TRI:2507157.2507172,  
 author = {Ostuni, Vito Claudio and Di Noia, Tommaso and Di Sciascio, Eugenio and Mirizzi, Roberto},  
 title = {Top-N Recommendations from Implicit Feedback Leveraging Linked Open Data},  
 booktitle = {Proceedings of the 7th ACM Conference on Recommender Systems},  
 series = {RecSys '13},  
 year = {2013},  
 isbn = {978-1-4503-2409-0},  
 location = {Hong Kong, China},  
 pages = {85--92},  
 numpages = {8},  
 url = {http://doi.acm.org/10.1145/2507157.2507172},  
 doi = {10.1145/2507157.2507172},  
 acmid = {2507172},  
 publisher = {ACM},  
 address = {New York, NY, USA},  
 keywords = {dbpedia, hybrid recommender system, implicit feedback, learning to rank, linked data, top-n recommendations},  
}   

   If you use the Movielens dataset you should cite the original Movielens dataset from GroupLens research group, http://www.grouplens.org


Credits
-------

   This dataset was originally built by Vito Claudio Ostuni during his PhD at Polytechnic University of Bari http://sisinflab.poliba.it/ostuni/ 

Contacts
-------

   Tommaso Di Noia, tommaso [dot] dinoia [at] poliba [dot] it  
   Vito Claudio Ostuni, vitoclaudio [dot] ostuni [at] poliba [dot] it


