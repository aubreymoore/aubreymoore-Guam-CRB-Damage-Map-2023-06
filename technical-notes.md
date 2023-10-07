# Technical Notes

* On GitHub:
	* Open the repo for the latest map
	* Open **Settings** and select **Template repository**
	* Go back to the main page of the repo
	* Click on the **Use this template button** then **Create a new repository**
	* Provide a name for the new repository
	* Edit **README.md** as necessary.
* On the local machine:
	* Clone the new GitHub repository onto the local machine
	* Open the repo directory on the local machine
	* Delete all files in the **output** subdirectories
	* Delete the **webmap** subdirectory
	* Copy the Spatialite database (**results.db**, for example) into the **output** folder.
	* Open the **code** folder and launch **Jupyter lab**
	* Open **edit_qgis_qgs.ipynb**, update constants, and run all cells.
	* Double-click on the new QGIS project file (*.qgs) to examine the new map.
	* Use QGIS to create a new webmap.
		* **Web | qgis2web | Create web map**
		* Open **Export** tab
		* Select **Export to folder** and specify the current project folder (**/home/aubrey/Desktop/Guam-CRB-Damage-Map-2023-04** for example)
		* Click the **Export** button
	* Change the name of the newly created webmap folder to **webmap** (from **qgis2web_2023_04_09-08_09_13_865708** to **webmap** for example)
	* Open **edit_webmap.ipynb**, update constants, and run all cells. This will add an abstract to the webmap stored in **webmap/insex.html**.
	* In the **webmap** folder, delete **index.html** and rename **new_index.html** as **index.html**
* Use **git** to commit changes to repo and push to **github.com**.
* Visit the **GitHub repo** (<https://github.com/aubreymoore/Guam-CRB-Damage-Map-2023-04> for example) and enable **GitHub Pages**
* The interactive webmap should be available online within a few minutes (at <https://aubreymoore.github.io/Guam-CRB-Damage-Map-2023-04/webmap> for example)
* Now update <https://github.com/aubreymoore/Guam-CRB-web-maps>. This repo acts as an index for all CRB web maps.

	
	


