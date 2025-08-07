This README_RingingDataBorealBirds.txt file was generated on 2020-06-22 by TANJA LINDHOLM, MARIA HÄLLFORS, and LAURA ANTÃO


GENERAL INFORMATION

1. Title of Dataset: "Data for: Shifts in timing and duration of breeding for 73 boreal bird species over four decades"

2. Author Information
	A. Principal Investigator Contact Information
		Name: Maria Hällfors
		Institution: Faculty of Biological and Environmental Sciences, University of Helsinki
		Address: P.O. Box 65, FI-00014 University of Helsinki, Finland
		Email: maria.hallfors@helsinki.fi

	B. Associate or Co-investigator Contact Information
		Name: Aleksi Lehikoinen
		Institution: Finnish Museum of Natural History, University of Helsinki
		Address: P.O. Box 17, FI-00014 University of Helsinki, Finland
		Email: aleksi.lehikoinen@helsinki.fi

	C. Alternate Contact Information
		Name: Tanja Lindholm
		Institution: Helsinki University Library, University of Helsinki
		Address: PL 53 (Fabianinkatu 30), FI-00014 Helsingin yliopisto, Finland
		Email: tanja.lindholm@helsinki.fi

3. Date of data collection: (1975-01-01 - 2017-12-31) 

4. Geographic location of data collection: Finland, Northern Europe. Bounding coordinates: South West [-65890, 6613621], North East [740713, 7775419]. Projection: ETRS-TM35FIN, EPSG:3067.

5. Information about funding sources that supported the collection of the data: NA 


SHARING/ACCESS INFORMATION
1. Licenses/restrictions placed on the data: This work is licensed under a CC0 1.0 Universal (CC0 1.0) Public Domain Dedication license. This releases your work to the public domain for any use. 
2. Links to publications that cite or use the data: Hällfors M.H., Antão L.H., Itter M., Lehikoinen A., Lindholm T., Roslin T., Saastamoinen M. Shifts in the timing and duration of breeding for 73 boreal bird species over four decades (2020). In press. Proceedings of the National Academy of Sciences of the United States of America

3. Links to other publicly accessible locations of the data: NA

4. Links/relationships to ancillary data sets: Data derived from sources indicated in 5.

5. Was data derived from another source? Yes
	A. If yes, list source(s): 

Ringing data (166_species.csv and 73_species.csv):
The original data are a subset of the data in the 'Database of birds ringed in Finland and all reported encounters of the birds' (http://tun.fi/HR.48) which is available from the Finnish Biodiversity Information Facility (FinBIF) at https://species.fi. The primary database was queried by J. Valkama and M. Piha in summer 2018 to include only records of ringed nestlings. 
		
Traits (in Traits_73_species.csv):
Valkama, J. Saurola, P. Lehikoinen, A. Lehikoinen, E. Piha, M. Sola, P. and Velmala, W. (2014) The Finnish Bird Ringing Atlas. Vol. II. Finnish Museum of Natural History and Ministry of Environment, Helsinki.
Solonen, T. 1985 Suomen Linnusto: esiintyminen ja perusbiologiaa. Lintutieto. (In Finnish)
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol I, Ostrich to Ducks. Oxfords University Press 1977.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol II, Hawks to Bustards. Oxford University Press 1980.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol III, Waders to Gulls. Oxfords University Press 1985.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp. Vol IV, Terns to woodpeckers. Oxfords University Press 1985.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol V, Tyrant flycatchers to Thrushes. Oxfords University Press 1985.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol VI, Warblers. Oxfords University Press 1985.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Perrins. Vol VII, Flycatchers to Shrikes. Oxfords University Press 1985.
Handbook of the Birds of Europe, the Middle East and North Africa, The birds of the palearctic- Cramp and Simmons. Vol VIII, Crows to Finches. Oxfords University Press 1994.



6. Recommended citation for this dataset: Hällfors M.H., Antão L.H., Itter M., Lehikoinen A., Lindholm T., Roslin T., Saastamoinen M. (2020), Data for: Shifts in the timing and duration of breeding for 73 boreal bird species over four decades, Dryad, Dataset, https://doi.org/10.5061/dryad.wstqjq2ht

DATA & FILE OVERVIEW

1. File List: 
166_species.csv
73_species.csv
Name_key_166_species.csv
Traits_73_species.csv

2. Relationship between files, if important: Records in the different files can be linked via species name and/or abbreviation.

3. Additional related data collected that was not included in the current data package: NA

4. Are there multiple versions of the dataset? NO


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 

Raw original data: The Bird Nest Ringing Database is coordinated and curated by the Finnish Museum of Natural History. 
This database contains records for ringing events of individual bird nestlings (marked by unique Ring IDs) in Finland. These data are a subset of the data in the 'Database of birds ringed in Finland and all reported encounters of the birds' (http://tun.fi/HR.48), which is available from the Finnish Biodiversity Information Facility (FinBIF) at https://species.fi. The primary database was queried by J. Valkama and M. Piha in summer 2018 to include only records of ringed nestlings.  At the point of data extraction, the database contained over 3.6 million ringing records of nestlings for 166 species (data available from the Finnish Biodiversity Information Facility (FinBIF) at https://species.fi), which represents c. 66% of the 250 bird species known to breed in Finland. Ringing is done by experienced volunteer ornithologists who have received training in the procedure (Lokki H. (ed.) 2017: Rengastajan käsikirja. Version 1.0. Finnish Museum of Natural History, University of Helsinki. (In Finnish). Crucially, nestlings can only be ringed when of a certain size (which is species-specific), and thus the timing of ringing is tightly linked to the timing of egg-hatching (Møller et al. 2010: Climate change affects the duration of the reproductive season in birds. Journal of Animal Ecology https:/doi.org/10.1111/j.1365-2656.2010.01677.x; Lehikoinen 2011: Advanced Autumn Migration of Sparrowhawk Has Increased the Predation Risk of Long-Distance Migrants in Finland in PloS One, (2011) https:/doi.org/10.1371/journal.pone.0020001.). We therefore use the timing of ringing as an indicator for breeding time, since, within species, the possible timing of ringing is relatively constant in relation to egg-hatching, and has been identified as a functional phenological indicator (Møller et al. 2010). Additionally, ringing data has been shown to be a reliable estimate for breeding phenology (Eeva et al 2012: Breeding time trends of the Crested Tit (Lophophanes cristatus) in southern Finland: comparison of data sources. J Ornithol 153, 653-661). 

2. Methods for processing the data: 
To quantify changes in breeding period timing and duration of bird species in Finland, we use the Bird Nest Ringing Database coordinated and curated by the Finnish Museum of Natural History (see 1 above). 
In order to identify single ringing events per nest and day-of-year for each species, we took a number of processing steps with the raw data. First, we aggregated individual ringing events likely done in the same nest. We used a combination of unique Ringer ID, Species, Location (unique longitude and latitude) and Date (unique day, month and year) of ringing to identify unique ringing events per nest (RSLD combinations); this yielded 584 354 events which correspond to a ringing event occurring in separate nests by a given ringer on a given day of year for each species in the dataset. However, nestlings in several nests may have been ringed in the same locations (when nests are located very close to each other) and/or more than one ringer may have ringed nestlings cooperatively in the same nest, causing the same nest to occur multiple times in the database. Therefore, we further divided these records into three subsets (A, B and C), based on a brood number (i.e. each ringer’s personal chronological sequence of ringed broods) and an abundance value (i.e. number of nestlings observed per brood), when available. Specifically, a unique brood identifier was created based on the combination of Brood and the variables described above (RSLD+B=RSLDB). For each RSLDB identifier, we tallied the number of ringed nestlings (i.e. number of unique Ring IDs) and compared this to the reported abundance value. If these values matched, each of these unique broods was considered a unique nest and given a unique ID (subset A; 392 421 unique nests). In cases where the tallied number of ringed nestlings and the reported abundance value did not match (either because the ringer had not ringed all nestlings in the brood, or because either the brood number or abundance value was incorrectly reported - which of the two was the case we cannot separate) and/or abundance values were missing, we used the tallied number of ringed nestlings per unique RSLD and disregarded the reported abundance value by the ringer, which might or might not be correct. Next, the tallied number of nestlings was compared to the maximum brood size for each species (literature-based estimates; see traits below). When these values matched, the records were assigned a unique nest ID (subset B; 247 399 unique nests). For the remaining records, we calculated the potential number of nests for each RSLD, by dividing the number of ringed nestlings by the maximum brood size for each species. This step was used to calculate the required number of nests to 'accommodate” the recorded number of nestling ringed, which were given a unique ID (subset C; 294 284 unique nests). Subsets A, B, and C were then combined, yielding 934 104 records of ringing events in unique nests. Finally, we only included records after 1975, since records before this year were sparse and only represented a small subset of the bird species in the dataset. This processing resulted in 919 713 records of bird ringing events for 166 species, spanning 43 years and four bioclimatic zones in Finland (166_species.csv).
For the purposes of our analyses we further filtered the above data set (166_species.csv) through additional criteria. As some species had very sparse records, either within a specific bioclimatic zone or over time, we included only species-zone-year combinations with a minimum of 30 records. Next, we included only those species-zone combinations that had records from at least 10 years over our study period, and with at least one year with observations in the first and one in the last ten years of the study period. These relatively conservative inclusion criteria meant that many ringing events, and thus several species and species-by-zone combinations, were not included in the analysis. These steps were intended to ensure that: 1) there were sufficient records to estimate phenological metrics for each species in each zone and per year (i.e. enough records to represent the day-of-year distribution of nesting events); 2) there was a sufficient number of years sampled for each species and zone to reliably estimate shifts in the breeding period (i.e. at least 10 data points over time); and 3) the species analyzed were present in the beginning and end of our study period. We finally excluded one species (Columba oenas) as it breeds irregularly and several times throughout the season, and thus has an intermittent and varying breeding phenology that is not well-captured by ringing data. Finally, we removed apparent outliers in the data, i.e. ringing events clearly outside the general breeding season of birds in Finland, which most probably represent data entry errors (by inspecting the distribution of the nesting events over time for each species-zone combination). The final dataset that we used for our analyses contained 821 413 records of ringing events in unique nests for 73 species (73_species.csv). These data represent a large variety of species including birds of prey, waders, passerines, and owls that are characterised as Resident (R) or Short distance migrants (S) versus Long distance migrants (L) and single-brooded (1) versus multi-brooded (2) species (Traits_73_species.csv). 

3. Instrument- or software-specific information needed to interpret the data: NA

4. Standards and calibration information, if appropriate: NA

5. Environmental/experimental conditions: NA

6. Describe any quality-assurance procedures performed on the data: see Methods.

7. People involved with sample collection, processing, analysis and/or submission: 
The Bird Nest Ringing Database is coordinated and curated by the Finnish Museum of Natural History. This database contains records for ringing events of individual bird nestlings (marked by unique Ring IDs) in Finland. Ringing is done by experienced volunteer ornithologists who have received training in the procedure (Lokki H. 2017: Rengastajan käsikirja. Version 1.0. Finnish Museum of Natural History, University of Helsinki. (In Finnish)). At the point of data extraction (summer 2018), the database contained over 3.6 million ringing records of nestlings for 166 species. These data were processed, analysed, and submitted by the authors.

DATA-SPECIFIC INFORMATION FOR: 

[166_species.csv]
Identified single ringing events per nest and day-of-year for each species, see Methods.
1. Number of variables: 7
2. Number of rows: 919713
3. Variable List: 
NestID, A unique ringing event in a single nest on a specific day. This ID was created by the authors as described in the Methods.
Species, Abbreviation of species scientific names according to https://www.luomus.fi/fi/lintulajien-kuusikirjaimiset-lyhenteet. The key to their scientific names can be found in Name_key_166_species.csv 
BZ, Bioclimatic zone (from south to north: HB= Hemi-Boreal; SB= South-Boreal; MB= Mid-Boreal; NB= North-Boreal)
Day, Day of the month when ringing was performed 
Month, Month of the year when ringing was performed
Year, Year when ringing was performed
Dayofyear, Julian day of the year when ringing was performed
4. Missing data codes: NA
5. Specialized formats or other abbreviations used: Species are referred to by a six-letter abbreviation. The key to their scientific names can be found in Name_key_166_species.csv 
For each ringing event we report the bioclimatic zone within Finland (from south to north: HB= Hemi-Boreal; SB= South-Boreal; MB= Mid-Boreal; NB= North-Boreal; based on T. Ahti, L. Hämet-Ahti, J. Jalas, Vegetation zones and their sections in northwestern Europe. Ann. Bot. Fenn. 5, 169–211 (1968).)

[73_species.csv]
Final dataset for analysis. See Methods for species selection.
1. Number of variables: 9
2. Number of rows: 821413
3. Variable List: 
NestID, A unique ringing event in a single nest on a specific day. This ID was created by the authors as described in the methods.
Species, Abbreviation of species scientific names according to https://www.luomus.fi/fi/lintulajien-kuusikirjaimiset-lyhenteet. The key to their scientific names can be found in Name_key_166_species.csv 
XEUREF, Geographic coordinate. Coarsened (10 x 10 km) coordinates for unique nests, Projection: ETRS-TM35FIN, EPSG:3067
YEUREF, Geographic coordinate. Coarsened (10 x 10 km) coordinates for unique nests, Projection: ETRS-TM35FIN, EPSG:3067
BZ, Bioclimatic zone of the location (from south to north: HB= Hemi-Boreal; SB= South-Boreal; MB= Mid-Boreal; NB= North-Boreal)
Day, Day of the month when ringing was performed 
Month, Month of the year when ringing was performed
Year, Year when ringing was performed
Dayofyear, Julian day of the year when ringing was performed
4. Missing data codes: NA
5. Specialized formats or other abbreviations used: Species are referred to by a six-letter abbreviation. The key to their scientific names can be found in Name_key_166_species.csv 
For each ringing event we report the bioclimatic zone within Finland (from south to north: HB= Hemi-Boreal; SB= South-Boreal; MB= Mid-Boreal; NB= North-Boreal; based on T. Ahti, L. Hämet-Ahti, J. Jalas, Vegetation zones and their sections in northwestern Europe. Ann. Bot. Fenn. 5, 169–211 (1968).)

[Name_key_166_species.csv]
Name key for connecting species name abbreviations with the corresponding scientific name.
1. Number of variables: 3
2. Number of rows: 166
3. Variable List: 
Abbreviation, Abbreviations of bird species names used in Finland (generally 3x3 letter of scientific name, https://www.luomus.fi/fi/lintulajien-kuusikirjaimiset-lyhenteet)
Genus, Genus
Species, Species epithet
4. Missing data codes: NA
5. Specialized formats or other abbreviations used:  NA

[Traits_73_species.csv]
Traits and name key for the 73 species used in final analysis
1. Number of variables: 4
2. Number of rows: 73
3. Variable List: 
Abbreviation, Abbreviations used in Finland (generally 3x3 letter of Latin name, Abbreviation: Abbreviations of bird species names used in Finland (generally 3x3 letter of scientific name, https://www.luomus.fi/fi/lintulajien-kuusikirjaimiset-lyhenteet)
Scientific name, Scientific name of species
Broods, Number of broods. Variable with two levels (1 = one brooded species; 2 = species can have two or multiple broods (in Southern Finland)).	
Mig, Migratory strategy. Variable with three levels (R = Residents, S = Short-distance migrants, L = Long-distance migrants)	
4. Missing data codes: missing data are referred to with 'NA'
5. Specialized formats or other abbreviations used:  NA


