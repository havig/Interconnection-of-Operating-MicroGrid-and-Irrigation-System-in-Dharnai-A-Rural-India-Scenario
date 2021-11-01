# Intelligent-Interconnection-of-Operating-Micro-Grid-and-Irrigation-System-in-Dharnai-A-Rural-Indian Scenario
Disclaimer: The work showcased in the repository is a miniaturized version of the original. This work has been accepted and presented at IEEE GHTC 2019, Seattle, Washington, USA.

The following codes have been uploaded:
1) Base Design for both the DMG and DIS : This calculated the base effeciency of the loads without implementing the SETA algorithm when the two micro-grid systems operate independently. NOTE: This code involves multiple iterations (Gauss-Seidel Method) and battery Degradation. 
2) Load Modelling for Irrigation system : This is done considering the pump efficiency, Rainfall parameters and Evapotranspiration of the various crops in the village. Can be customised to any similar irrigation system.
3) Domestic Load Modelling for the village Dharnai : This modelling considering the average day-day activities of the communitites in the vilage with factors like temperature and humidity playing a vital role. 
4) SETA (Smart Energy Transfer Algorithm) : Energy transfer without prioritising any Micro-Grids. The algortihm considers all the possible events as in Paper and transfers energy effectively. This is the main crux of the paper which can be applied for any two independently operating microgrid. 
