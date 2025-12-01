# Youetal2025
Version of the reltrans code used in You et al (2025), Nature Communications. This version includes the model flavour reltransCpF, which outputs a lag vs frequency spectrum between two given energy bands. The code was branched from older versions of reltrans, so is kept in a separate repository for version control reasons.
The genreal reltrans documentation can be found here: https://reltransdocs.readthedocs.io/en/latest/  
  
To use reltransCpF, load reltrans into xspec like usual (as is described in the link above), then the new model flavour can be called with the model command within xspec. The parameters are as follows:

|    | Parameter         | Unit     | Default Value |
|:---| :---------------- | :------  | :------------ |
|1   | h                 | Rg/Rh    | 6.0           |
|2   | a                 |          | 0.998         |
|3   | inc               |  deg     | 30.0          |
|4   | rin               | Rg/ISCO  | -1.0          |  
|5   | rout              | Rg       | 1000.0        |
|6   | z                 |          | 0.0           |  
|7   | Gamma             |          | 2.0           |  
|8   | logxi             |          | 3.0           |  
|9   | Afe               | solar    | 1.0           |
|10  | logNe             |          | 15.0          |  
|11  | kTe               | keV      | 300.0         |  
|12  | nH                | 10^22    | 0.0           |      
|13  | boost             |          | 1.0           |  
|14  | Mass              | Msun     | 10.0          |
|15  | Ea1               | keV      | 0.3           | 
|16  | Ea2               | keV      | 1.0           |
|17  | Eb1               | keV      | 1.0           |  
|18  | Eb2               | keV      | 4.0           |  
|19  | phiAB             | rad      | -0.2          |  
|20  | AB_exp            |          | 1.0           | 
|21  | g                 |          | 0.1           |
|22  | g_exp             |          | 1.0           |
|23  | norm              |          | 1.0           |

Parameters 1-20 are the same as in other model flavours. Parameters 21-24 define the two energy bands that the lag spectrum is taken between. 

