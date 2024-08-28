# MycoTip_year1_HTS
Analysis of mycorrhizal root tip community from 2023 samples in The Morton Arboretum forestry plots

## HTS data processing performed by Peter Kennedy before receiving 
ITS raw data processing:
* table tidy'ed
* sequence and taxonomic datasets were separated in ASV table
* index bleed was accounted for using arbitrary 10 read minimum used by Lindahl et al. 2013 (we didn't have any positive or negative controls)
* Sample sequence count totals were assessed and samples with the lowest read counts were removed, i.e., we rarefied to a 1013 threshold
* Taxonomic dataframe was tidy'ed to match sequencing dataframe
* Add FungalTraits database to taxonomic dataframe (and traits of interest)
* Sample names cleaned up to match with mapping file
* Rarefied version of the sequencing dataset was created

18S raw data processing:
* Same process as above except rarification threshold was set at 472 and FungalTraits database not used
