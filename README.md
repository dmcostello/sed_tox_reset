# Homogenization resets toxicity of metal-amended sediment

Data and code associated with the manuscript:
DM Costello, AM Harrison, CR Hammerschmidt, RM Mendonca, and GA Burton Jr. *Hitting reset on sediment toxicity: Sediment homogenization alters the toxicity of metal-amended sediments*.

Data files include:
* *Hyalella azteca* toxicity data
  * Cu_Ha.csv
  * Ni_Ha.csv
  * Zn_Ha.csv
* Sediment geochemistry data
  * Cu_sedchem.csv
  * Ni_sedchem.csv
  * Zn_sedchem.csv
* Water chemistry data
  * Cu_water.csv
  * Ni_water.csv

Code files include:
* Estimates of toxicity curves and point estimates (i.e., EC10 and LC50)
  * Tox_stats.Rmd
* Sediment geochemistry statistical analyses
  * Sed_chem_stats.Rmd

Metadata:

__Cu_Ha.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Cu|Nominal Cu treatment|mg Cu/kg dw|
|Treat|Sediment preparation treatment|
|TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|SEMAVSfOC|Bioavailable Cu|µmol Cu/g C|
|SEMAVSfOC2|Corrected bioavailable Cu|µmol Cu/g C|
|Count|Total count of living *H. azteca*|Number alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|


__Ni_Ha.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|SEMAVSfOC|Bioavailable Ni|µmol Ni/g C|
|SEMAVSfOC2|Corrected bioavailable Ni|µmol Ni/g C|
|Count|Total count of living *H. azteca*|Number alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|
|Tissue_Ni|*H. azteca* body Ni concentration|ng Ni/mg dw|

__Zn_Ha.csv__
(Raisin sediment only)

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Nom_Zn|Nominal Zn treatment|mg Zn/kg dw|
|Treat|Sediment preparation treatment|
|TOT_Zn|Mean sediment total extractable Zn|mg Zn/kg dw|
|SEMAVSfOC|Bioavailable Zn|µmol Zn/g C|
|SEMAVSfOC2|Corrected bioavailable Zn|µmol Zn/g C|
|Count|Total count of living *H. azteca*|Number alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|
|Tissue_Zn|*H. azteca* body Zn concentration|ng Zn/mg dw|

__Cu_sedchem.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Cu|Nominal Cu treatment|mg Cu/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Depth|Sediment depth treatment|
|Sed_pH|pH of sediment samples|
|LOI| Organic matter content from loss-on-ignition|%|
|AVS|Acid-volatile sulfide concentration per gram of dry weight|µmol/g dw|
|Mean_TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|TOT_Cu|Sediment total extractable Cu|µmol Cu/kg dw|
|TOT_Fe|Sediment total extractable Fe|µmol Fe/kg dw|
|TOT_Mn|Sediment total extractable Mn|µmol Mn/kg dw|
|SEM_Cu|Cu associated with metal sulfide|µg/g dw|
|ASC_Cu|Cu associated with amorphous oxides|µg/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|µg/g dw|
|DITH_Cu|Cu associated with total extractable metal oxides|µg/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|µg/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|µg/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Cu|Porewater Cu concentration|µg/L|

__Ni_sedchem.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Depth|Sediment depth treatment|
|Sed_pH|pH of sediment samples|
|LOI| Organic matter content from loss-on-ignition|%|
|AVS|Acid-volatile sulfide concentration per gram of dry weight|µmol/g dw|
|Mean_TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|TOT_Ni|Sediment total extractable Ni|µmol Ni/kg dw|
|TOT_Fe|Sediment total extractable Fe|µmol Fe/kg dw|
|TOT_Mn|Sediment total extractable Mn|µmol Mn/kg dw|
|SEM_Ni|Ni associated with metal sulfide|ug/g dw|
|ASC_Ni|Ni associated with amorphous oxides|µg/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|µg/g dw|
|DITH_Ni|Ni associated with total extractable metal oxides|µg/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|µg/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|µg/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Ni|Porewater Ni concentration|µg/L|

__Zn_sedchem.csv__
(Raisin sediment only)

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Nom_Zn|Nominal Zn treatment|mg Zn/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Depth|Sediment depth treatment|
|Sed_pH|pH of sediment samples|
|LOI| Organic matter content from loss-on-ignition|%|
|AVS|Acid-volatile sulfide concentration per gram of dry weight|umol/g dw|
|Mean_TOT_Zn|Mean sediment total extractable Zn|mg Zn/kg dw|
|TOT_Zn|Sediment total extractable Zn|µmol Zn/kg dw|
|TOT_Fe|Sediment total extractable Fe|µmol Fe/kg dw|
|TOT_Mn|Sediment total extractable Mn|µmol Mn/kg dw|
|SEM_Zn|Zn associated with metal sulfide|µg/g dw|
|ASC_Zn|Zn associated with amorphous oxides|µg/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|µg/g dw|
|DITH_Zn|Zn associated with total extractable metal oxides|µg/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|µg/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|µg/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Zn|Porewater Zn concentration|µg/L|
|H2O_Zn|Surface water Zn concentration|µg/L|  

__Cu_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Cu|Nominal Cu treatment|mg Cu/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|Dis_Cu|Dissolved Cu concentration|µg/L|
|Cu_flux|Cu flux from sediment to surface water|µg Cu/cm<sup>2</sup>/d|

__Ni_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|Dis_Ni|Dissolved Ni concentration|µg/L|
|Ni_flux|Ni flux from sediment to surface water|µg Ni/cm<sup>2</sup>/d|

_Variable codes and notes_  
Treat: F = aged; S = freshly spiked  
SEMAVSfOC2: Correction was to set negative values (i.e., AVS in excess of SEM) to 1 to allow for log-linear regression  
Count: A total of 10 *H. azteca* were added to each beaker  
Day: 0 = sediment added to beaker for all tests; 10, 7, 1 = *H. azteca* added to beaker for Cu, Ni, and Zn tests, respectively; 38, 35, and 28 = experiment terminated for Cu, Ni, and Zn tests respectively  
Depth: surface = 0-1 cm, deep = 1-3 cm  
"NA" cell = sample collected, but no good analytical data; blank cell = no data collected
