Mapping artists of Last.fm to DBpedia
=======================
The hetrec2011-lastfm-2k dataset is released in the framework of the 2nd International Workshop on Information Heterogeneity and Fusion in Recommender Systems [HetRec 2011](http://ir.ii.uam.es/hetrec2011)
at the 5th ACM Conference on Recommender Systems [RecSys 2011](http://recsys.acm.org/2011) 

If you use the hetrec2011-lastfm-2k dataset please refer to:  
   http://ir.ii.uam.es/hetrec2011/datasets/lastfm/readme.txt  

The mapping files are formatted one entry per line as follows (tab separated, "\t"):  
artist_id	artist_name	DBpedia_URI  
An example of mapping is the following:  
1934	Adele	http://dbpedia.org/resource/Adele  

Version 1.2
=======================
This version is an improvement of the version 1.1, which contained some redirect links. 
We replaced those links with the actual ones. When a link redicted to a disambiguation page, we selected the correct link among the different redirects in that page.
The number of matched artists is the same of version 1.1, namely 11,180.

References
----------
If you use these mappings in your scientific work, please cite as  

~~~
@inproceedings{Fernandez-Tobias16,
  author    = {Ignacio Fern{\'{a}}ndez{-}Tob{\'{\i}}as and Paolo Tomeo and Iv{\'{a}}n Cantador and Tommaso {Di Noia} and Eugenio {Di Sciascio}},
  title     = {Accuracy and Diversity in Cross-domain Recommendations for Cold-start
               Users with Positive-only Feedback},
  booktitle = {Proceedings of the 10th {ACM} Conference on Recommender Systems, Boston, MA, USA, September 15-19, 2016},
  pages     = {119--122},
  year      = {2016},
  url       = {http://doi.acm.org/10.1145/2959100.2959175},
  doi       = {10.1145/2959100.2959175},
}
~~~
and
~~~
@article{DiNoiaOTS16,
  author    = {Tommaso {Di Noia} and Vito Claudio Ostuni and Paolo Tomeo and Eugenio {Di Sciascio}},
  title     = {SPrank: Semantic Path-Based Ranking for Top-\emph{N} Recommendations Using Linked Open Data},
  journal   = {{ACM} {TIST}},
  volume    = {8},
  number    = {1},
  pages     = {9:1--9:34},
  year      = {2016},
  url       = {http://doi.acm.org/10.1145/2899005},
  doi       = {10.1145/2899005},
}
~~~


Version 1.1
=======================

We used [DBpedia Lookup](https://github.com/dbpedia/lookup) to map each artist in the dataset with the corrisponding DBpedia resource (DBpedia 2015), using as QueryClass filter dbpedia-owl:Band and dbpedia-owl:MusicalArtist. We also implemented other filters to reduce the number of false positives in the final mapping. Finally, we manually checked all suspicious entities, if any, referenced by more than one dataset entry. For more detail about this procedure, see the references.
We found a match for 11,180 out of a total of 17,632 artists.


References
----------
   
If you use these mappings in your scientific work, please cite as  
~~~
@article{DiNoiaOTS16,
  author    = {Tommaso {Di Noia} and Vito Claudio Ostuni and Paolo Tomeo and Eugenio {Di Sciascio}},
  title     = {SPrank: Semantic Path-Based Ranking for Top-\emph{N} Recommendations Using Linked Open Data},
  journal   = {{ACM} {TIST}},
  volume    = {8},
  number    = {1},
  pages     = {9:1--9:34},
  year      = {2016},
  url       = {http://doi.acm.org/10.1145/2899005},
  doi       = {10.1145/2899005},
}
~~~
   

Version 1
=======================

The file contains the mappings between the artists in the hetrec2011-lastfm-2k dataset to the correspondent DBpedia resources (DBpedia v3.9). 

We did not find a mapping for all the artists in hetrec2011-lastfm-2k. We found a valid mapping for 8175 of them.  


References
----------
   
If you use these mappings in your scientific work, please cite as  

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
