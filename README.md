# OSeMOSYS-Sweden-Offshore-Wind
OSeMOSYS model of Sweden's electricity system including 4 bidding zones and the surrounding 6 countries, based on OSeMBE version 1.0.0 (OSeMBE) created by Hauke Henke, Francesco Gardiumi and Mark Howells. Further information on OSeMOSYS and OSeMBE can be found at https://github.com/OSeMOSYS and https://github.com/KTH-dESA/OSeMBE.

## Description
This is a modified version of the OSeMOSYS model used to model the electricity system of Sweden, specifically to assess the cost-effectiveness of different offshore wind farm locations, for the master's thesis "Swedish Offshore Wind: modelling development pathways to commercial viability" by Siddharth Iyer at the Swedish Royal Institute of Technology (KTH). The thesis research was carried out at ELS Analysis, Stockholm. Values from OSeMBE and aggregated average costs have been used instead of data deemed sensitive by ELS Analysis, including capital costs, operating costs and capacity factors for individual wind farms and electricity demands for Sweden and the surrounding 6 countries.

OSeMBE was modified to keep only Germany, Poland, Lithuania, Norway, Denmark and Finland. Sweden has been modelled as subdivided into its 4 electricity price areas/bidding zones. 15 planned and existing Swedish offshore wind farms amounting to 15 GW of capacity are individually modelled as separate electricity generation technologies within the relevant bidding zone. The actual transmission capacities between each country and Swedish bidding zone are modelled.

The datafile, along with an OSeMOSYS model file, can be converted into a Linear Program .lp file by using the GLPK Solver https://anaconda.org/conda-forge/glpk and then solved using a free or commercial solver such as IBM ILOG CPLEX Optimization Studio.

## Licensing
Following the licensing approach for OSeMBE, this datafile is released under the terms of a CC-BY-4.0 International License Agreement. The license text can be found in the LICENSE.
