# Homgenization resets toxicity of metal-amended sediment

Data and code associated with the manuscript:
DM Costello, AM Harrison, CR Hammerschmidt, RM Mendonca, and GA Burton Jr. *Hitting reset on sediment toxicity: Sediment homogenization alters the toxicity of metal-amended sediments*.

Data files include:
* *Hyalella azteca* toxicity data
  * Cu_Ha.csv


Code files include:
* Estimates of toxicity curves and point estimates (i.e., EC10 and LC50)
  * Cu_stats.Rmd

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


_Variable codes and notes_
Treat: F = aged S = freshly spiked;
SEMAVSfOC2: Correction was to set negative values (i.e., AVS in excess of SEM) to 1 to allow for log-linear regression;
Count: A total of 10 *H. azteca* were added to each beaker

