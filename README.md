# gifDisplay

cmsRun gifDisplay.py to produce event displays

1, in gifDisplay.py provide input using "process.source"
  input rootfiles must have RAW data to be unpacked, using edmDumpEventContent one should 
  see event has "FEDRawDataCollection" type
  
2, output name is controled by "rootFileName = cms.untracked.string"

3, "chamberType" to control which chamber type to use: ME1/1 or ME2/1

in eventList.txt provide list of events for which event displays are needed

displays are saved in "tmpDisplay"
