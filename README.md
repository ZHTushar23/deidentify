# De-Identification of Personal Information on medical images

This program can detect a patient's confidential information in the top part of the medical images and replace it with a dark background. Also replaces name information from the folder and image filenames.

Prerequisite of running the exe file
32-bit Windows system
Enough computer storage space for modified images. For example, if you have 1 GB images, please make sure you have another 1 GB space to save the modified images. 
The image extensions supported: .jpg, jpeg, .png

Running the exe file
Place the deidentify32.exe inside the Image Folder. Then create a New Folder and place the Image Folder within the New Folder.

	New Folder:
	|	Image Folder:
	|	|	deidentify32.exe
	|	|	801-05-01-19_DIETRICH_Chuck
	|	|	4999-05-14-19_VANNAGELL_
	|	|	[new patient image folder to be placed here]
Make sure you have permission to edit the folders.
Run deidentify32.exe by double clicking it. Wait about 30 seconds until the program starts to run and displays its own window. Do not close the program while it is running. 
While the program is running, it will display which image has already been processed (if any) and then the number of files being processed.


At the end of the program, it will show the total number of images that are not modified and file names are saved in a csv file called ‘corrupted_files.csv’.
Once the program is finished, 'Deidentified' folder, ‘corrupted_files.csv’, and ‘deidentified.csv’ file will be generated, and press any key to end the program.
 
	New Folder:
	|	Image Folder:
	|	|	deidentify32.exe
	|	|	801-05-01-19_Zahid_Tushar
	|	|	4999-05-14-19_JOE_
	|	|	[new patient image folder to be placed here]
	|	Deidentfied:
	|	|	801-05-01-19_xxxxxxx_xxxx
	|	|	4999-05-14-19_xxx_
	|	|	[new deidentified patient image folder will be stored here]
	|	corrupted_files.csv
	|	deidentified.csv

A sample of the de-identified medical image: 


The patient’s name on the title of the image file is replaced with random digits. 


# License	
Licensed under the MIT LICENSE

# Contributors:
Zahid Hassan Tushar, Department of Information Systems, University of Maryland Baltimore County, ztushar1@umbc.edu
Sanjay Purushotham, Department of Information Systems, University of Maryland Baltimore County, psanjay@umbc.edu
