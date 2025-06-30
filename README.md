# clinical-pipeline-deidentified
aDBS for PD

https://github.com/emilygzh/Analysis-rcs-data/blob/2003568e722ff30a4274b62ac6381941c736ba79/documentationFigures/RCS_DataFlow_Overview.png
UCSF pipeline, processing all done in matlab


in Python: 

1_ data sources:
    a_ load data
    b_ find missing packets, chunk data (?)
    
2_ align & harmonize time domain across all data streams

3_ combined data form? data that can be easily pulled and plotted, analyzed



data sources: 
|___device data
|   |___in clinic
|       |___accel data for activity classification
|       |___controller
|       |___time domain
|       |___power
|   |___at home
|       |___raw accel
|       |___raw FFT
|       |___raw power
|       |___raw time domain
|       |___time sync
|       |___stim log, event log, error log, diagnostics log, device settings, adaptive log
|
|___strive PD data
|   |___med state (discrete)
|   |___time since med (continuous)
|   |___dyskinesia prediction
|
|___apple watch data
|   |___accelerometer for tremor
|    
|___leap motion data (in clinic)


