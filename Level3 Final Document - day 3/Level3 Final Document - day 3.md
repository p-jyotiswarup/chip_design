DAY-3 Design library cell using Magic Layout and ngspice characterization.

TASK-1: Obtain *magic* for the following.

Step-1: Run the command *magic -T sky130A.tech sky130\_inv.mag & ,* In the directory */Desktop/work/tools/openlane\_working\_dir/openlane/vsdstdcelldesign$ .*

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.001.jpeg)

Step-2: The result in then obtained.



![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.002.jpeg)





![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.003.jpeg)A closer look of the *magic* is- 









![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.004.jpeg)																																																																																																																																		

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.005.jpeg)






Task-2: Obtain *ngspice.* 

Step-1: To obtain ngspice, we must extract the magic we have obtained from the previous task.

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.006.jpeg)

Step-2: Now, we must edit the file (sky130\_inv.spice) using the command vim.

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.007.jpeg)

Step-3: Edit the obtained output.

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.008.jpeg)

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.009.jpeg)

We have now successfully obtained *ngspice.* 

Task-3: Plot a graph in *ngspice.* 

Step-1: First, we run *ngspice* with the command ngspice sky130\_inv.spice. 

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.010.jpeg)

Step-2: We plot a graph using the command plot y vs time a. 

![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.011.jpeg)![](Aspose.Words.4d6f6185-8cc3-4232-8510-2db9b746ad11.012.jpeg)



