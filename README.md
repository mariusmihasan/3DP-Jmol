**3DP-Jmol** is a Jmol-based script that automatically generates 3D printable molecular models from structural data.

Have you ever wanted/needed a model of a macromolecule from PDB but were unable to find a suitable printable file? Did not have the time and patience to learn ChimeraX or PyMol to make it yourself? Then **3DP-Jmol** is something you need to try. 

The most user-intensive step in generating 3D printable models of macromolecular structures is by far the conversion of the structural data into the stl file. This step is key not only for the printability of the model but also for its success as an educational or demonstration material. Important key information related to the target molecule such as size, atoms, and bond dimensions must be correlated with the final dimensions of the physical model and printing hardware. Hence we started developing 3DP-Jmol – a script that automatically generates 3D printable molecular models from structural data based on very minimal user input.  

**3DP-Jmol** is currently under development and new features are added constantly. Although we expect things to run smoothly, your experience may vary.

# **Brief instructions**
1. Download and unzip [JMol](https://jmol.sourceforge.net/), an open-source Java viewer for chemical structures in 3D;
2. Access the GitHub for  3DP-Jmol and under Assets download the  Source code (zip) file;
3. Unzip it and open the  3DP-JMol.v.xxxxx file with your prefered text editor;
4. Edit the first lines of the file as indicated to select your molecule of interest and other relevant parameters. Read carefully and only edit the lines indicated. 
5. Open the previously unzipped  Jmol application and navigate in the menu to File>Console….  A new window entitled Console will open; 
6. Copy the entire content of the text file edited in step 4 and paste it in the Console window using the Ctrl-V  keyboard combination (or Cmd+V for Mac);
7. Wait patiently until JMol generates your printable file. This should be signaled by the appearance of a text similar to: 
       `OK 20527284 Stl /Users/mariusmihasan/test.stl
       Time for running the script version alfa.public is: 4956ms`
8. Check the instructions in the Console and, if required, based on the indications and your choice, come back to step 4 and repeat. The path for the test.stl  file generated is indicated before the last line in the Console. Print it and enjoy!

# **Contributors**: 
- [Dr. Marius Mihasan](https://modelemoleculare.ro/), Biology Department, Alexandru Ioan Cuza University of Iasi, Carol I Bvd., No.11, 700506, Iaşi, Romania, (www.modelemoleculare.ro)
- [Dr. Angel Herráez](https://biomodel.uah.es/), Biochemistry and Molecular Biology, Dept. of Systems Biology, University of Alcalá, E-28805 Alcalá de Henares  (Madrid), Spain 

# **Contact**: 
Marius Mihasan, marius.mihasan@uaic.ro

-------------------------------------------
Development supported by EDUMOL3D, Project PN-IV-P7-7.1-PED-2024-0343 financed by the Ministry of Research, Innovation and Digitization, UEFISCDI, Romania.
