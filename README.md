# Deforestation Exploration

ForestQuery, a fictitious non-profit organization, is on a mission to reduce deforestation around the world and to raise awareness about the importance of this environmental subject. <br><br>
The goal of this project is to help ForestQuery management understand the global deforestation overview between 1990 and 2016. Three tables of data have been found online: forest area, land area, and regions.<br><br>
The task is to present a report to ForestQuery management about the global situation, regional outlook, and country-level details of deforestation as well as recommendations. In the appendix, all SQL queries should be presented according to the SQL formatting guidelines. 

## Steps to Complete
1. Create a View called “forestation” by joining all three tables - forest_area, land_area, and regions in the workspace.
2. The forest_area and land_area tables join on both country_code AND year.
3. The regions table joins these based on only country_code.
4. In the ‘forestation’ View, include the following:
  - All of the columns of the origin tables
  - A new column that provides the percent of the land area that is designated as forest.
5. Keep in mind that the column forest_area_sqkm in the forest_area table and the land_area_sqmi in the land_area table are in different units (square kilometers and square miles, respectively), so an adjustment will need to be made in the calculation you write (1 sq mi = 2.59 sq km).
