
### IPython Notebook for downloading and analyzing data from the manuscript: "_Indication of family-specific DNA methylation patterns in developing oysters_"

---

The repository includes a IPython notebook (.ipynb file) that can be downloaded and interactively executed. The code in the IPython notebook will download raw data and process data such that figures in the manuscript are reproduced (in theory). gl

---
To execute the IPython Notebook in its entirety you will need:   

* IPython - [install instructions](http://ipython.org/install.html)    
* BSMAP - [install instructions](https://code.google.com/p/bsmap/)   
* bedtools - [install instructions](https://github.com/arq5x/bedtools2/releases/tag/v2.22.0)    
* R - [install instructions](http://www.r-project.org/)  
* rpy2 (interface to R from Python) - [install instructions](http://rpy.sourceforge.net/)  

---
Sofware versions originally used in this analyses (on Mac OS X v10.7.5) are as follows: 

* IPython: 2.3.0   
* BSMAP: 2.74   
* bedtools: 2.17.0   
* R: 3.1.1  
* rpy2: 2.5.0   

---
Note the current version of the IPython Notebook can be viewed (not interactive) in any web browser at: 
<http://nbviewer.ipython.org/github/che625/olson-ms-nb/blob/master/BiGo_dev.ipynb>

----
##Instructions

**1) Download the repository zip file to a local directory and uncompress.** This can be done by clicking on the link in the right sidebar or directly downloading: <https://github.com/che625/olson-ms-nb/archive/master.zip>

**2) Launch IPython from the repository primary directory.** 
For example, using Terminal on MacOSX.


```
$ cd /Desktop/olson-ms-nb
$ ipython notebook

```
This will launch IPython in your web browser.  
   
>_screenshot_    
![nb](http://eagle.fish.washington.edu/cnidarian/skitch/Home_1A41E21F.png)

**3) Open notebook by clicking on `BiGo_dev.ipynb`**. This will open a new tab in your browser.

>_screenshot_  
![nb2](http://eagle.fish.washington.edu/cnidarian/skitch/BiGo_dev_1A41E5C5.png)  



**4) Execute cells in notebook** The first section of the notebook includes code to download raw data in `wd` subdirectory.  In theory, assuming all dependencies are installed

* BSMAP   
* bedtools   
* R   
* rpy2 (interface to R from Python)  

you could edit the cell near the top to provide the location of BSMAP on your machine, then run all cells (see screenshot). Raw data will be downloaded, and analyses carried out, producing figures (2) in manuscript. Please note data is very large (>20 GB) and analyses will take several hours depending on your machine.

>_screenshot_   
![nb3](http://eagle.fish.washington.edu/cnidarian/skitch/BiGo_dev_1A41EC5B.png)

In practice, you can execute cells individually with `shift-enter`.

---

We are actively trying to improve this realizing that we are likely missing dependancies, etc. Any suggestions and feedback is welcome. 

