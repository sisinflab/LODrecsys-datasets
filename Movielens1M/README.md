
Mapping artists of MovieLens1M to DBpedia
=======================
The MovieLens1M dataset is published by GroupLeans research group (http://www.grouplens.org/datasets/movielens/).

The mapping files are formatted one entry per line as follows (tab separated, "\t"):  
ML_id	ML_name	DBpedia_URI  
An example of mapping is the following:  
858	Godfather, The (1972)	http://dbpedia.org/resource/The_Godfather   


Version 1.2
=======================
This version is an improvement of the version 1.1, which contained some redirect links. 
We replaced those links with the actual ones. When a link redicted to a disambiguation page, we selected the correct link among the different redirects in that page.
The number of matched movies is the same of version 1.1, namely 3,300.

Version 1.1
=======================

We used [DBpedia Lookup](https://github.com/dbpedia/lookup) to map each artist in the dataset with the corrisponding DBpedia resource (DBpedia 2015), using as QueryClass filter dbpedia-owl:Band and dbpedia-owl:MusicalArtist. We also implemented other filters to reduce the number of false positives in the final mapping. Finally, we manually checked all suspicious entities, if any, referenced by more than one dataset entry. For more detail about this procedure, see the references.
We found a match for 3,300 out of a total of 3,883 movies.


References
----------
   
    If you use these mappings in your scientific work, please cite as  
~~~
@Article{DOTD16, 
  author = {Tommaso {Di Noia} and Vito Claudio Ostuni and Paolo Tomeo and Eugenio {Di Sciascio}}, 
  title = "SPRank: Semantic Path-based Ranking for Top-N Recommendations using Linked Open Data", 
  journal = "ACM Transactions on Intelligent Systems and Technology (TIST)", 
  year = "2016", 
  note = "to appear", 
  url = "http://sisinflab.poliba.it/sisinflab/publications/2016/DOTD16" 
}
~~~
   

Version 1
=======================

This file contains the mappings between the movies in the MovieLens1M dataset to the correspondent DBpedia resources (DBpedia v3.9). 

	
We did not find a mapping for all the movies in MovieLens1M. We found a valid mapping for 3156 of them.

References
----------
   
If you use these mappings in your scientific work, please cite as

~~~
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
keywords = {DBpedia, LinkedMDB, content-based recommender systems, freebase, linked data, movielens, precision, >recall, semantic web, vector space model},
} 
~~~

or

~~~
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
~~~



Credits
-------
   
   The version 1.2 is an improvement of the previous version made by Paolo Tomeo.
   
   The version 1.1 was built by Paolo Albano and Tommaso Di Noia.

   The version 1.0 of this mapping was built by Vito Claudio Ostuni.


Contacts
-------

   Tommaso Di Noia, tommaso [dot] dinoia [at] poliba [dot] it  
   
   Paolo Tomeo, paolo [dot] tomeo [at] poliba [dot] it 
   
   Vito Claudio Ostuni, vitoclaudio [dot] ostuni [at] poliba [dot] it  
