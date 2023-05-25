# Long Ztautau exercise for the CMS DAS school 2023 at CERN

Repository with code for CMS DAS tau ID efficiency long exercise (June 2023). 

In "Analysis" there is the code to make flat trees from NanoAOD.

In "Analysis2" there is the code to analyze the flat trees.

## CMSSW setup
```
cmsrel CMSSW_10_6_27
cd CMSSW_10_6_27/src
cmsenv

#setup nanoAOD-tools
git clone https://github.com/cms-nanoAOD/nanoAOD-tools.git PhysicsTools/NanoAODTools
scram b -j 8

#This package
git clone https://github.com/cecilecaillol/CMSDASCERN2023_LongZTT.git
scram b -j 8
```


