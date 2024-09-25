# District-mapping-2001-2011-with-LGD-codes

This is a v small project to create a reliable concordance table with location codes. The database from Ministry of Panchayati Raj was slightly improved upon, by mapping newly formed districts post 2001, to their erstwhile districts. The database contains information on all present districts of India with their name, state name, district & state LGD codes, along with census 2001 / 2011 codes of the districts as they existed then. 

This repository has two xlsx files, 
1 - District concordance_with LGD codes
Sources for this mapping include district official websites and government notices as reported by newpapers. Please note, this mapping is done only for districts which had a 1:1 match to an ersthwile district, those new districts created by combining blocks from multiple districts were left unmapped [these can be removed by dropping districts where census 2001 codes are unavailable conditional on census 2011 being available]

2 - District concordance_with LGD codes parent
This is an updated version of the previous file, where the new districts with LGD codes created after 2011 are mapped to the erstwhile districts as on 2011, thereby 2001 as well. Similar to the previous file, 
this mapping is done only for districts which had a 1:1 match to an ersthwile district, those new districts created by combining blocks from multiple districts can be identified with `multiple' in place of their 2001, 2001 census codes. Additionally, this file has a column which states how the district was formed, this will come of use if you want to map districts with multiple parents to one of the parents. The comments are from either district official websites or government notices as reported by newpapers.

Though India has more than 800 official districts as of September 2024, the latest LGD district document from the LGD website has codes mapped to 785 districts, which are covered by both these concordance files. 
Hope this fetches you more leisure time :D
