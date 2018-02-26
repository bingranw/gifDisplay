# gifDisplay

put this package under CMSSW_X_Y_Z/src

then cmsenv and compile 

cmsRun gifDisplay.py to produce event displays

1, in gifDisplay.py provide input using "process.source"
  input rootfiles must have RAW data to be unpacked, using edmDumpEventContent one should 
  see event has "FEDRawDataCollection" type
 
2, save event and chamber id for which you want make eventdisplay for in eventList.txt 
   FORMAT: eventNumber endcapID stationID ringID chamberID (note: use ringID=1 for both ME11a and ME11b)

3, ./runDisplay.sh, change path where you want to save plots in runDisplay.sh (plotdir="PLOTPATH")

* this version works under CMSSW_9_2_13, NOT tested in other version of CMSSW 

email hualin.mei@cern.ch if you have any suggestions and questions
