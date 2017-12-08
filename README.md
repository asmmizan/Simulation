
                 How to run AQMUL Approach
-----------------------------------------------------------
-----------------------------------------------------------

Copy the AQMUL folder from  the Simulation folder to your suitable directory.
The AQMUL contains two folders named by DepthOne and Quartet Matching.
 

  How to run DepthOne
---------------------------------
---------------------------------

Now you have to run "DepthOne" first which will construct all depth one elements and 
make a list of all inconsistent quartets. To run "DepthOne" you have to go
"DepthOne" folder and need to modify all the directory in "TreeConstructionFromQuartets.exe" 
file. Please replace the path "C:\Users\Desktop" in all directory link in
"TreeConstructionFromQuartets.exe by indicating your local directory where you saved "AQMUL".
In "DepthOne" folder "Quartets.txt" file contains all quartets. Finally run 
"TreeConstructionFromQuartets" file under "DepthOne folder".

  How to run Quartet Matching
---------------------------------
---------------------------------
Now you have to run "Quartet Matching" which will construct Final Tree in Newick format 
(shown in "FinalTreeOutput" file) and show all inconsistent taxon (shown in "FinalWrongPositionOutput" 
file) with its pairs. To run "Quartet Matching" you have to go "Quartet Matching" folder and need to 
modify all the directory in "TreeConstructionFromQuartets.exe" file. Please replace the path 
"C:\Users\Desktop" in all directory link in "TreeConstructionFromQuartets.exe by indicating your 
local directory where you saved "AQMUL". Now go to the "DepthOne" folder and open "Quartets_DepethOne" 
file. Then coppy all DepethOne element from "Quartets_DepethOne" file and paste it to "DepethOne" file 
under "Quartet Matching folder". Again go to the "DepthOne" folder and open "Quartets_InConsistentQuatret" file. Then coppy all 
inonsistent quatrets from "Quartets_InConsistentQuatret" file and paste it to "InConsistentQuatrets" file 
under "Quartet Matching" folder. Finally run "TreeConstructionFromQuartets" file under "Quartet Matching" 
folder.
 
