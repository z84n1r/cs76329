java c
Assignment 1: ArcGIS Pro Familiarization and Intro GPS
1. Objectives
When you complete this assignment:
You should be able to assemble geographic data in ArcGIS Pro (ArcGIS for short), configure layer ordering, style. layers, create layouts, and print your map.
You should be able to collect tracks using a hand-held GPS or a mobile device and add these to an ArcGIS project.
2. Data Provided
This compressed file (.zip) (https://q.utoronto.ca/courses/361521/files/33088371?wrap=1) (https://q.utoronto.ca/courses/361521/files/33088371/download?download_frd=1) contains the following geographic data layers in Shapefile format:
Natural Resources Canada, 2014, available from http://geogratis.gc.ca
(http://geogratis.gc.ca:) :
water_lines.shp
water_polygons.shp
OpenStreetMap Project, 2016, available from http://openstreetmap.org (http://openstreetmap.org:) :
roads.shp
sports_facilities.shp
footpaths.shp
wooded_areas.shp
City of Toronto Open Data, 2017 (search “toronto open data”):
buildings.shp
Glenn Brauen, 2019:
construction_zones.shp
Some of these files are a bit outdated (e.g., the construction zones are mostly complete now), but we will work with them regardless. You must completely unpack the zip file to create a folder of shapefiles before beginning to work with these in ArcGIS. The data folder contains more than one file for each data layer because each "Shapefile" is in fact a collection of files sharing the same root name (e.g., “buildings”) and different file name extensions (.cpg, .dbf, .prj, .sbn, .sbx, .shp, .shp.xml, .shx). Some of these files are required (others optional) but the root name must be exactly the same for GIS systems to recognize the set of files as being a "single shapefile." Following the procedures in Section 4.1 you will place this folder inside the ArcGIS Pro project folder the software will create for your project.
3. Assignment Submission
Your assignment will be submitted in two parts.
A. Printed maps and write-up
These must be submitted to the essay drop box for the course (near the 2nd floor entrance to the main staircase in Highland Hall). Item #2 below requires you to submit digital copies of your GPS tracks in Quercus but only the GPS tracks will be accepted that way. Your maps and write-up will be marked only if submitted in paper to the essay drop box. Required
paper materials include:
Map 1: Your campus map layout described in Section 4 (8 marks). This will be one (1) page. This map must be created using the data layers provided with this assignment as your base map. Do not use layers that appear as defaults in the GIS software or any other layers not described above.
Map 2: A map layout of part of the UTSC campus showing the GPS tracks you created using a hand-held GPS or a mobile device with an installed GPS app (6 marks). This will be one (1) page.
This map will not be marked unless a digital copy of the GPS data is submitted on Quercus.
Your GPS map should be a modified version of your campus map and must use the same base layers provided for this assignment.
A brief write-up: neatly word processed and double spaced, answering each of the following questions (4 Marks):
Your earth writing and the tools you used.
I. What character symbols have you “written” using your GPS track? Is your writing legible on the map? Which direction is the writing oriented (i.e., what geographic direction should be “up” when I read your writing)?
II. What tools (both device and software, as appropriate) did you use to create your GPS tracks? What problems, if any, did you have with the data collection procedures?
What does “accuracy” mean with respect to the GPS tracks you have created? Did your GPS device indicate a level of accuracy in the location measurements you did while creating your tracks? Are there parts of your created tracks where inaccuracy in measurements is most apparent? If so, what do you think it was about the place(s) where problems occurred that caused reduced accuracy?
B. Digital copies of your recorded GPS tracks (2 marks)
These must be uploaded using the Quercus assignment upload link. I expect your GPS track(s) as either GPS Exchange Format (GPX) or a Keyhole Markup Language (KML) files, depending on the device and app you used. Upload only the GPS track(s)
This assignment is designed to get you working with ArcGIS, working with some of the online help pages, and demonstrating that you can assemble and print a map or export it. Marks will be reserved to reward students that have followed basic formatting guidelines (see Sections 4.1– 4.4) and for students who have created maps with clear, legible text boxes and map elements that are well balanced across the map. The write-up for this assignment may be brief but must be clear, legible, written in complete sentences, and typed.
If your GPS tracks look roughly like the character symbols requested and you submit matching digital GPS track data, you have done well. Getting really legible tracks on your map takes some effort and planning (see lecture slides). If your GPS writing is unrecognizable, you will lose some marks.
4. Create and Print a Map Layout using ArcGIS
Your task in this part of the assignment is to create and print a map layout similar to the sample attached to this assignment handout. As shown in that sample, yo代 写Assignment 1: ArcGIS Pro Familiarization and Intro GPSMatlab
代做程序编程语言u should be able to distinguish different types of objects by colour. Choose colours that make sense to you and don’t worry about trying to create a replica of the sample by using the same colours.
Include all of the following map elements:
Title
Legend
North arrow
Scale bar (sized so that it shows round number distances)
Data source list
Your name and student number
It may be well worth your time to look at the ArcGIS online help before proceeding. For example, the following help sections may be particularly useful for this assignment:
1. Introducing ArcGIS Pro (https://pro.arcgis.com/en/pro-app/latest/get-started/introducing-arcgis-pro.htm) . In particular, this help page discusses the following topics that you will need to understand to create your map:
An overview of the ArcGIS Pro user interface, including the default layout of project panels and the organization of contextually-sensitive menus.
How ArcGIS Pro organizes different views within a project, in particular the basic project map view and map layout views.
Map layers and the project Table of Contents.
The Catalogue window, used to organize your project files.
2. Create a Project (https://pro.arcgis.com/en/pro-app/latest/get-started/create-a-project.htm) . Note that when creating a project or when adding a map to a project, depending on the template you select while starting the software, ArcGIS by default adds map layers to the project. These are almost never useful and for this course, unless you are explicitly instructed to keep them, you should remove them immediately. For example, in these instructions (Section 3) you are told to use only layers provided for you with this assignment.
3. Add Data to a Project (https://pro.arcgis.com/en/pro-app/latest/get-started/add-data-to-your-project.htm) . This tutorial touches on using several different data formats with ArcGIS. You will be working with shapefiles in this assignment.
4. This slide deck (https://q.utoronto.ca/courses/361521/files/33106485?wrap=1) (https://q.utoronto.ca/courses/361521/files/33106485/download?download_frd=1) on how to create a portable ArcGIS project for your course work.
In each of the ESRI documentation pages above, notice that when the specified page is open in a browser, the left panel shows the current page in a table of contents for the ArcGIS documentation. This is useful for finding additional information in surrounding pages.
4.1 Download Data and Set Up ArcGIS Project
1. Download the assignment data from Quercus. Once you have the data, ensure that you fully extract the data files and folders from the downloaded zip file. ArcGIS will not work properly if you try to access the shapefiles when they are still inside a zip file even if Microsoft windows makes it appear that the files are accessible while in the zip file. All campus computers have 7-zip utilities that will open zip files and extract data. Right-click on the zip file and use the 7-zip sub-menu.
2. Follow the instructions in the slide deck (https://q.utoronto.ca/courses/361521/files/33106485?wrap=1) (https://q.utoronto.ca/courses/361521/files/33106485/download?download_frd=1) . Following that procedure will result in you creating a working folder for this assignment with an ArcGIS Pro project file inside it.
For the purpose of these instructions, I will assume you have named the project “assignment1” (without the quotes), resulting in a working folder called assignment1 and an ArcGIS project configuration file inside that folder called assignment1.aprx.
Notice that there are no spaces in the project (and folder) name suggested. In general, it is very good practice with ArcGIS to avoid spaces and punctuation characters in folder and file names. Use underscores (_) if you really feel you must add spacing in a file or folder title (e.g., assignment_1).
Copy the downloaded and unzipped data folder into the assignment1 folder just created.
3. If it is not already running, start ArcGIS Pro by double-clicking on the project file (assignment1.aprx, if following the instructions above). If the project contains an empty map, meaning a map tab is shown but no layers have been added to it, you are ready to go.
If your project does not contain a map, select Insert on the ribbon and then select New Map.
If your project contains a map tab and that contains layers showing all of Canada (plus Alaska and Greenland), then remove the the default layers added to the map.
Right-click on a layer title in the Contents panel of the project when the map tab is active and select Remove. Repeat this step for every layer in the map — there should be two such layers.
4. Select Insert on the ribbon and then select New Layout. You will be offered a variety of page sizes and orientations. Select Letter in the ANSI - Portrait section. This will create a new layout tab in your project with a letter paper sized page in portrait orientation.
5. Resave your project. The interface should now look something like Figure 1. Notice that the Folders category in the Catalogue panel has been opened, showing the assignment folder and its contents, including the unpacked data folder provided for this assignment. Each level of the Content panel’s hierarchy can be opened or closed by clicking on the small triangle to the left of the title.



         
加QQ：99515681  WX：codinghelp
