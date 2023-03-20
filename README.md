# Python for R users

![Binder](https://mybinder.org/badge_logo.svg)

## A. Getting started

### 1. Fire up a new JupyterLab session 

*We'll be coding Python using JupyterLab hosted on one of Duke's Virtual Containers.*

* Navigate to https://cmgr.oit.duke.edu/containers & log in
* Find the entry for [Jupyter Containers](https://cmgr.oit.duke.edu/containers/Jupyter) and create your personal Jupyter environment.

> This JuptyerLab container is yours for the remainder of the semester. (OIT will send an email asking whether you want to renew it before destroying it.) You can access it at any time, from any browser via the link above. The session will pick up right where you left off. The data on these containers are NOT backed up - though, I've never lost any data on these things. However, there is no "recycle bin", so if you delete something, it's gone for good.



### 2. Clone the `PythonForRUsers` Git Environment

*I've put materials for this section on a separate GitHub repository. You can clone this repository directly into your JupyterLab container.* 

* Start a new Terminal session from within JupyterLab

  * If the Launcher is not already accessible via one of your tabs, click the :heavy_plus_sign: icon to open one. 
  * From the Launcher, click the Terminal button to open a new terminal tab.

* Enter the git clone command at the terminal window

  ```bash
  git clone https://github.com/ENV872/PythonForRUsers.git
  ```

  * You may be asked for your GitHub username and password...
  * This should add a new folder to your container



### 3. Open a Jupyter Notebook and start coding

*In the PythonForRUsers folder are a set of Jupyter Notebooks - an analog to R's Rmd files. We'll start with `A-Basic-Python.ipynb`.*

* Navigate into the `PythnonForRUsers` folder.
* Double-click the `A-Basic-Python.ipynb` notebook to open it . 
* Click the first code cell (shaded in gray) to activate it.
* Click the "►" button to run the code in the code cell (or use <ctrl>-<enter> from your keyboard)
* If you double click a text cell, it will open it up a raw markdown; just run the cell to return it to its formatted view.

---



## B. The lessons

The specific lessons in notebooks include explanations. The first two notebooks provide a quick introduction to the Python language and its basic data structures. The remaining three notebooks mimic the lessons we did in R, allowing easy comparison of Python commands to their R counterparts in terms of data wrangling.  

| Notebook                                | Rmd counterpart                       | Topics                      |
| --------------------------------------- | ------------------------------------- | --------------------------- |
| `01-Getting-Started`                    | *none*                                | Quick tour of JupyterLab    |
| `02-ReproducibilityCoding-Basics.ipynb` | `02_Reproducibility_CodingBasics.Rmd` | Basics of Python...         |
| `A-Basic-Python.ipynb`                  | *none*                                | Basics of Python...         |
| `03-Data-Exploration.ipynb`             | `03_DataExploration.Rmd`              | Data Exploration            |
| `03-Data-Exploration_II.ipynb`          | `03_DataExploration_Part2.Rmd`        | Exploration & Visualization |
| `04-Data-Wrangling.ipynb`               | `04_Part1_DataWrangling.Rmd`          | Data Wrangling              |
| `04-Data-Wrangling_II.ipynb`            | `04_Part1_DataWrangling.Rmd`          | More Data Wrangling         |
| `B-Web-Services-APIs-Python.ipynb`      | *none*                                | Scraping data               |

 
