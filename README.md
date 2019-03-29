# Assignment: Advanced QGIS
## Worth: 30 points
## Due: April 3, 2019, 11:59pm

## Background

QGIS allows you to programmatically access data layers and manipulate data, perform joins, change styles, etc. 
using Python either by running Python scripts in the `Processing Toolbox` or by building python `Plugins`. 
A thorough description of PyQGIS operations is given at https://docs.qgis.org/3.4/en/docs/pyqgis_developer_cookbook/. 
For those familiar with Python, reading this Cookbook will give you a good foundation to start working with PyQGIS. 
For those less familiar with Python, read Sections 1-6 of the Python Tutorial (https://docs.python.org/3/tutorial/) 
and skim the rest.

A note on using the Python Console in QGIS: When you first open the Python Console, click on the 
![python_editor_button.png](python_editor_button.png) icon to open the editor. Your Python console will be accompanied by an 
editor and will look like this:
![python_console_editor.png](python_console_editor.png)

While you _can_ type in the python console, if you attempt to do anything with much complexity at all it will be
very cumbersome and prone to syntax errors. Instead, you should put your python code in the editor and, when you are 
ready to run a block of code, click the "Run Script" button, which looks like a green triangle: 
![python_run_script_button.png](python_run_script_button.png).

I recommend taking it one step further and create/edit/save your Python from an external editor like `Notepad++`.

Additionally, you may want to look at the Log Messages by clicking:  `View` -> `Panels` -> `Log Messages`

## Assignment

### 1. Follow the tutorial at http://www.qgistutorials.com/en/docs/3/batch_processing.html

Deliverable:

From step 32, take a screenshot of your QGIS desktop showing the open layers and map of Africa and commit that to a
new branch named `pyqgis`

### 2. Follow the tutorial at http://www.qgistutorials.com/en/docs/3/getting_started_with_pyqgis.html

Deliverable:

Add the `airports.txt` file to the `pyqgis` branch of this repo.

### 3. Follow the tutorial at http://www.qgistutorials.com/en/docs/find_neighbor_polygons.html

Deliverable:

From step 8, Open the attribute table and show the `NEIGHBORS` and `SUM` field for Bolivia by adding a screenshot 
of your QGIS workspace wit the table opened and the row for Bolivia selected.

### 4. Finally, submit a *Pull request* to merge your assignment files with the `master` branch.
