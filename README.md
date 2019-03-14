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
|Count|Total count of living *H. azteca*|NUmber alive|
|RGR|*H. azteca* relative growth rate|mg/mg/d|


Variable codes and notes
Treat: F = aged S = freshly spiked
SEMAVSfOC2: Correction was to set negative values (i.e., AVS in excess of SEM) to 1. Required for log-linear regression
Count: A total of 10 *H. azteca* were added to each beaker

