DAY-1 	Inception of open-source EDA, OpenLANE and Sky130 PDK.

*Workshop 1- Find Floppy disk ratio*

To get the Floppy disk ratio, we first need to run Synthesis.

Step-1: First, we run the command 

![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.001.jpeg)./flow.tcl -interactive in the docker.



Step-2: Now, we run the command 

![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.002.jpeg)prep -design picorv32a after the first step. 



Step-3: The final step is to do the command run\_synthesis.

![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.003.jpeg)

Step-4: If we scroll a bit up now, we will find the heading ==picorv32a== . From this we can find the floppy disk ratio.

![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.004.jpeg)Floppy disk ratio = No. of Floppy disks ÷ Number of cells.




Step-5: The final thing to do is the division.

`             `= 1613 ÷ 14876

`		`= 0.108429

Percentage = 0.108429 x 100

![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.005.jpeg)![](Aspose.Words.79728b5c-1464-4f83-8c1a-43c6a37780ce.006.jpeg)			    = **10.8429.**










The ratio of Floppy Disks are **10.8429.**
