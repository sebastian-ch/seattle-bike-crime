# MAP675 Assignment 04
### Team: Sebastian Hancock & Michael McNeil

#### Data & Data Source(s)
* [City of Seattle Open Data Portal](https://data.seattle.gov/) -- mm
    * Seattle Police Precincts (polygons)
    * Seattle Thefts (points)
* [King County GIS Open Data](https://gis-kingcounty.opendata.arcgis.com/) -- mm

#### Terminal Commands
* npm init (to initialize npm to create package.json file) -- sh
* npm install -- mm
* npm start -- mm
* git add . -- mm
* git push origin master -- mm

#### Build Notes

##### 2017-11-02
* Sebastian created repo and added Michael and Rich as collaborators. -- sh
* Sebastian initialized npm to create the package.json file. -- sh

##### 2017-11-03
* Michael cloned repo to local machine. -- mm
* Created a michael-edits branch to work off the master. Will email Sebastian so he knows he can work off the master branch. -- mm
* Explored datasets available online and suggested Seattle for this assignment. -- mm
* Created a project-files directory. -- mm
* Added Seattle Police Precincts data to project-files directory. -- mm
* Added Seattle thefts data to project-files directory. -- mm
* Used framework of index.html from Part I of the assignment for this part of the assignment. -- mm
* merged michael-edits branch with master -- sh
* added libs folder --sh
* simplify/lower precision for thefts data and precincts --sh
* created data/ folder to hold our processed data -- sh
* tried to be fancy and use build scripts to extract vividcolors (didn't upload vividcolors.json to see if it works for you) --sh

##### 2017-11-06
* Michael created a new branch (michael-edits-20171106). -- mm

##### 2017-11-07
* Michael created a new branch (michael-edits-20171107). -- mm
* Troubleshot some data issues that were preventing the polygons from coloring correctly. Solved by manipulating the data into a numeric format. -- mm
* Used QGIS to do points-in-polygons analysis and assigned those numbers to a "count" field in the precinct polygon features. -- mm
* Used QGIS to delete point features outside polygon extents (used "select by location" tool). -- mm

##### 2017-11-08
* Michael created a new branch (michael-edits-20171108). -- mm
* Filtered the point data by EVENT = BICYCLE THEFT to improve page load time. Cut number of points down to ~4,000. -- mm
* After adding the marker cluster group, the page loads much faster! -- mm
* Merging branch into master now that most major things are complete. -- mm
* Added metadata. -- mm
* Removed vividecolors from .gitignore -- sh
* changed title of legend -- sh
* added white space to code -- sh
