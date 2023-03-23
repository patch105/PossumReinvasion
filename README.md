# PossumReinvasion

<a href="https://zenodo.org/badge/latestdoi/617738118"><img src="https://zenodo.org/badge/617738118.svg" alt="DOI"></a>

The primary aim of this project is to assess repopulation rates of an invasive mammal, the common brushtail possum (Trichosurus vulpecula) on a peninsula adjacent to an urban centre across management scenarios that emphasise differen repopulation-prevention methods. 

The project aims, methods, results, and discussion are presented in our paper entitled: "Eradicating an invasive mammal requires local elimination and reduced reinvasion from urban source population" Ecological Applications (In Review). Patterson C.R., Lustig, A., Seddon P.J., Wilson D.J. and Y. van Heezik.

The data/code presented here include:
- Model code/model_code_06_22.py : python source code of the agent-based population dynamics model, which simulates pest dynamics (reproduction, dispersal and natural mortality) within a raster grid and the python source code of the module giving the probability of an animal being caught at a particular location with a given local trap density.
- Model code/habitat_suitability.py : python source code of diverse functions used to read and reformat input raster grid cells. 
- Scenarios : python source code to run all scenarios presented in our study.
- Data/DHM_FOREST_FRAGpeninsula_kmap_ascii_06_22.asc : The landscape carrying capacity layer of the model (methods to generate this layer described in paper and Appendix S1).
- Data/study_area_updated_21_11_ascii : The layer delineating the peninsula treatment area and the area of the source population.

Trap density layers for maintenance and buffer trapping scenarios:
- Data/Maintenance_traps_150_buffer_150_ASCII.asc
- Data/Maintenance_traps_500_buffer_150_ASCII.asc
- Data/Maintenance_traps_500_buffer_500_ASCII.asc
- Data/trap_locations_150_raster_ascii.asc
- Data/trap_locations_300_raster_ascii.asc
- Data/trap_locations_500_raster_ascii.asc

All model outputs are saved in the 'Model output' folder

All code used to create figures and tables in the paper is presented in the R Markdown document: 
"Possum_reinvasion_Otago_Peninsula.html"

Contact Charlotte Patterson at crpattrsn@gmail.com for queries.
