### summary
This directory contains EFT specific modifications and addons for cms-sw/genproductions which allow to prepare EFT gridpacks 

### instructions:  
 * execute setup_production.sh to checkout cms-sw/genproductions and merge dedicated EFT tools: 
 * run submit_madpack_ttbareft.sh to produce gridpacks 
   the script will copy card templates from  addons/cards/UFOMODEL_template and the corresponding UFO file in addons/models
   you can modify the copied cards according to your needs via sed in submit_madpack_ttbareft.sh
   afterwards jobs are submitted to lxplus condor 


