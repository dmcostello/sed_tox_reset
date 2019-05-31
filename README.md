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
|SEMAVSfOC|Bioavailable Cu|µmol Cu/g OM|
|SEMAVSfOC2|Corrected bioavailable Cu|µmol Cu/g OM|
|Count|Total count of living *H. azteca*|Number alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|


__Ni_Ha.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|SEMAVSfOC|Bioavailable Ni|µmol Ni/g OM|
|SEMAVSfOC2|Corrected bioavailable Ni|µmol Ni/g OM|
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
|SEMAVSfOC|Bioavailable Zn|µmol Zn/g OM|
|SEMAVSfOC2|Corrected bioavailable Zn|µmol Zn/g OM|
|Count|Total count of living *H. azteca*|Number alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|
|Tissue_Zn|*H. azteca* body Zn concentration|ng Zn/mg dw|

<<<<<<< HEAD
_Variable codes and notes_  
=======
_Variable codes and notes_
>>>>>>> a8e5c744a6334d276c871e23fe456fcfb1c75bb0
Treat: F = aged S = freshly spiked;  
SEMAVSfOC2: Correction was to set negative values (i.e., AVS in excess of SEM) to 1 to allow for log-linear regression;  
Count: A total of 10 *H. azteca* were added to each beaker  

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
|AVS|Acid-volatile sulfide concentration per gram of dry weight|umol/g dw|
|Mean_TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|TOT_Cu|Sediment total extractable Cu|µmol Cu/kg dw|
|TOT_Fe|Sediment total extractable Fe|µmol Fe/kg dw|
|TOT_Mn|Sediment total extractable Mn|µmol Mn/kg dw|
|SEM_Cu|Cu associated with metal sulfide|ug/g dw|
|SEM_Fe|Concentration of simultaneously extracted Fe|ug/g dw|
|SEM_Mn|Concentration of simultaneously extracted Mn|ug/g dw|
|ASC_Cu|Cu associated with amorphous oxides|ug/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|ug/g dw|
|ASC_Mn|Amorphous Mn oxide concentration|ug/g dw|
|DITH_Cu|Cu associated with total extractable metal oxides|ug/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|ug/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|ug/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Cu|Porewater Cu concentration|µg/L|
|Pore_Fe|Porewater Fe concentration|µg/L|
|Pore_Mn|Porewater Mn concentration|µg/L|
|Pore_DOC|Porewater dissolved organic carbon concentration|µg/L|

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
|AVS|Acid-volatile sulfide concentration per gram of dry weight|umol/g dw|
|Mean_TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|TOT_Ni|Sediment total extractable Ni|µmol Ni/kg dw|
|TOT_Fe|Sediment total extractable Fe|µmol Fe/kg dw|
|TOT_Mn|Sediment total extractable Mn|µmol Mn/kg dw|
|SEM_Ni|Ni associated with metal sulfide|ug/g dw|
|SEM_Fe|Concentration of simultaneously extracted Fe|ug/g dw|
|SEM_Mn|Concentration of simultaneously extracted Mn|ug/g dw|
|ASC_Ni|Ni associated with amorphous oxides|ug/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|ug/g dw|
|ASC_Mn|Amorphous Mn oxide concentration|ug/g dw|
|DITH_Ni|Ni associated with total extractable metal oxides|ug/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|ug/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|ug/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Ni|Porewater Ni concentration|µg/L|
|Pore_Mn|Porewater Mn concentration|µg/L|
|Pore_DOC|Porewater dissolved organic carbon concentration|µg/L|

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
|SEM_Zn|Zn associated with metal sulfide|ug/g dw|
|SEM_Fe|Concentration of simultaneously extracted Fe|ug/g dw|
|SEM_Mn|Concentration of simultaneously extracted Mn|ug/g dw|
|ASC_Zn|Zn associated with amorphous oxides|ug/g dw|
|ASC_Fe|Amorphous Fe oxide concentration|ug/g dw|
|ASC_Mn|Amorphous Mn oxide concentration|ug/g dw|
|DITH_Zn|Zn associated with total extractable metal oxides|ug/g dw|
|DITH_Fe|Total extractable Fe oxide concentration|ug/g dw|
|DITH_Mn|Total extractable Mn oxide concentration|ug/g dw|
|dw_corr|Sediment dry weight correction|
|Pore_Zn|Porewater Zn concentration|µg/L|
|Pore_Fe|Porewater Fe concentration|µg/L|
|Pore_Mn|Porewater Mn concentration|µg/L|

_Variable codes and notes_
**Left this here in case you want to add anything**

__Cu_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Cu|Nominal Cu treatment|mg Cu/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|Dis_Cu|Dissolved Cu concentration|µg/L|
|Cu_flux|Cu flux from sediment to porewater?|Units?|

__Ni_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|Dis_Ni|Dissolved Ni concentration|µg/L|
|Ni_flux|Ni flux from sediment to porewater?|Units?|

_Variable codes and notes_
**Left this here in case you want to add anything**

__Cu_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Cu|Nominal Cu treatment|mg Cu/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Cu|Mean sediment total extractable Cu|mg Cu/kg dw|
|Dis_Cu|Dissolved Cu concentration|µg/L|
|Cu_flux|Cu flux from sediment to porewater?|Units?|

__Ni_water.csv__

|Parameter     |Definition   |Units  |
| ------------- |-----------| -----|
|Sediment| Sediment type||
|Nom_Ni|Nominal Ni treatment|mg Ni/kg dw|
|Treat|Sediment preparation treatment|
|Day|Sampling day|
|Mean_TOT_Ni|Mean sediment total extractable Ni|mg Ni/kg dw|
|Dis_Ni|Dissolved Ni concentration|µg/L|
|Ni_flux|Ni flux from sediment to porewater?|Units?|

_Variable codes and notes_
**Left this here in case you want to add anything**