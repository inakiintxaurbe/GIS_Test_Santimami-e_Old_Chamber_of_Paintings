# Test for script "paleospeleology"
This repository contains some files to allow checking that the code "Script.py," published in the DOI, works correctly. 
Unfortunately, due to the enormous volume of data generated in the above-mentioned study, it is not currently possible to upload the data from the 500 GU analyzed.
Here he have left some partial 3D models of the cave of Santimamiñe (see: https://www.sciencedirect.com/science/article/pii/S2352409X23003942#f0005), specifically the "Old Chamber of the Paintings".
In the folder "0_Input", you'll find the necessary files to make the script work.
You must create a folder named as "C/Paleospeleology" in your "C" Folder, and paste the files found in the "0_Input" folder, along with the code.
To find the code: https://github.com/inakiintxaurbe/spatial-organization-patterns-related-to-magdalenian-cave-art/blob/master/1%20GIS/Script.py

<img width="1134" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/d4da7e3c-71e2-4a6a-86b5-90eb44e213a6">

To make it work, you need to install the script "paleospeleology.py" in ArcGIS Catalog.

<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/ed4adac9-64e7-46ed-8e52-fcc0051d7694">
<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/9833b795-40b0-4983-9ad8-3f7988f8f831">

Next, we launch the code:

<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/76ad9b47-7e31-42f1-a79e-9bc112a7c8f7">
<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/026f0820-17b6-4c4b-923a-a5e04f21c190">

After the analysis, we will obtain 5 folders with different files.

<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/6700aeda-1910-4482-8de8-ca376c14d9a5">

The first folder called "Accessibility" contains some files of interest.

<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/4c721c23-1f79-4d91-93f3-448a96d50d79">

The file "EstimatedPositionArtist.shp" contains the data for the "Distance to ground" (Distance) and "Posture" (Posture) variables:

<img width="611" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/313c38dc-759a-4a80-961f-6492f30fca75">

The "Time.shp" file contains the data for the "Estimated Time of Arrival" (Minutes) variable:

<img width="438" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/d9f97bc1-7941-43ab-9530-8f114ff5de26">

The "LCP.shp" file contains the data for the variables "Difficulty value of access" (PATHCOST) and "Least cost path lentgh" (SLength):

<img width="642" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/ae847331-9195-49fa-8de7-ca3647447ee8">

The fifth folder called "Visibility and Capacity" contains other files of interest.

<img width="1280" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/af5ca2e8-0832-49e6-a802-ef5be99267f3">

The files "VisibilityStanding.tif", "VisibilityStooping.tif" and "VisibilityLyingDown.tif" contain the data for the variables "Viewers upright",	"Seated viewers" and	"viewers lying down" (Occupancy).
The "Total viewers" variable is the sum of the last three variables. In the atribute table, the "Value" 1 is considered a low value of visibility (from that position can be seen between 0.01 and 33.33 % of the GU),
the "Value" 2 is considered a medium value of visibility (from that position can be seen between 33.33 and 66.66 % of the GU) and 3 is high value (between 66.66 and 100 % of the GU).
To count a person, we round a number: 4.58 vould be considered as minimun 5 viewers.

<img width="1279" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/9f386624-ca60-4944-991b-754e519e7a6e">

The other 3 folders "Rock-Art", "Metadata" and "Topography" contain other interesting files to perform other studies (e.g., the file "Slope.tif" creates a plan of the ground, and the "LSSelect.shp" show the selected Lines of Sight in ArcScene.

<img width="795" alt="image" src="https://github.com/inakiintxaurbe/GIS_Test_Santimami-e_Old_Chamber_of_Paintings/assets/88764409/55905df8-6a1c-4a07-9e13-3276c5669f18">

There are other files in the folders.

We have not uploaded the other folders, because of their weight.

You can find instructions for installing the file at the following link: https://static-content.springer.com/esm/art%3A10.1007%2Fs10816-022-09552-y/MediaObjects/10816_2022_9552_MOESM1_ESM.pdf.




