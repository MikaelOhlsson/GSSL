# GSSL
Group Structure Solution Landscapes

Data and analyses used in the manuscript *Variability of group structure solution landscapes in food webs*.

Analyses of empirical networks are found in $code/SolutionLandscapes.Rmd$. Knit to obtain an HTML document with the output, with the figures included in the manuscript. $code/BlockStructure.Rmd$ contains additional code and output to generate and analyze food webs with fixed block structures.

Required data is found in $data/$ for review purposes only. The Barents sea food web is from [Kortsch et. al 2018](https://doi.org/10.1111/ecog.03443), Kongsfjorden from [Cirtwill & Eklöf 2018](https://doi.org/10.1111/ele.12955), Reef from Opitz 1996 (Trophic Interactions in Caribbean Coral Reefs, ISBN 9718709606), St. Marks from [Christian & Luczkovich 1999](https://doi.org/10.1016/S0304-3800(99)00022-8) and Ythan from [Cohen et al. 2009](https://doi.org/10.1073/pnas.0910582106).

The group model code is from [Michalska-Smith et al. 2018](https://doi.org/10.1111/1365-2656.12782), available at [https://github.com/elsander/ParasiteGroupStructure], and is here located in $GroupModelAlgorithm/$. Run the $make$ command to compile the model if you want to run it yourself, preferably set up the group model iterations to run in parallel on a computer cluster if so. Result files from the group model iterations are however also available in $results/original/$ (for $SolutionLandscapes.Rmd$) and in $results/connectance/$ (for $BlockStructure.Rmd$) to save time. 


