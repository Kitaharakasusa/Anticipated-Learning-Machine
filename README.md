# Anticipated-Learning-Machine
## Dataset
### Coupled Time-Variant Lorentz System
  This is a synthetic 90-dimension time-variant coupled Lorentz system. 
### Gene Dataset of Rats
This 31099-dimension dataset is based on gene expression profiles with Affimetrix microarray measured on the laboratory rat (Rattus norvegicus) cultured cells from SCN.
### Plankton Dataset
This 58-dimension dataset is collected from an optical plankton counter (OPC) and CTD mounted to a ScanFish platform that was towed and undulated behind the vessel.
### Ground Ozone Level Dataset
This 72-dimension dataset is collected from 1998 to 2004 at the Houston, Galveston and Brazoria area. Each variable represents a property of the observed area.
### Wind Dataset
This 155-dimension dataset is collected in Japan by the Japan Methodological Agency. Each variable represents the wind speed at different wind station.
### Stock Index Dataset
This 1130-dimension dataset is collected from 2018-05-01 to 2018-11-22 of different 1130 stock indexes with an interval of 1 day except Saturday and Sunday. Each stock index is a relative number of stock price statistics that measure and reflect the overall price level of the stock market and its changing trend.
### Traffic Dataset
This 207-dimension dataset contains traffic speed collected from 207 loop detectors in the highway of Los Angeles County. Each variable represents the traffic flow at different detectors.
### Satellite cloud image dataset
This 241-dimensional dataset comes from the satellite cloud image data recording the route of typhoon Marcus collected by National Institute of Informatics. Each variable represents the cloud image.

## Experiment Result
![image](https://github.com/AnticipatedLearningMachine/Anticipated-Learning-Machine/blob/master/gif/traffic.gif)
![image](https://github.com/AnticipatedLearningMachine/Anticipated-Learning-Machine/blob/master/gif/typhoon.gif)

## Requirements
* python 3.7
* pytorch 1.2.0 (important)
* numpy 1.16.4
* CUDA Version 10.2 (important)
* GPU & linux

Note that the version of pytorch and CUDA are important factors and the results vary slightly depending on the device.

It is noteworthy that the hyper-parameters setting remains to be sensitive in some of the experiments under the current framework. This is mainly due to strong nonlinearity or/and stochasticity of the dynamical systems also with the observed noisy data, and thus how to make more in-depth theoretical analysis and further develop an appropriate framework taking these issues into consideration is an open and interesting problem in future.

