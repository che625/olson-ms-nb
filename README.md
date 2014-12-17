
### _IPython Notebook for downloading and analyzing data in preprint: "Indication of family-specific DNA methylation patterns in developing oysters"_ - [biorxiv.org/content/early/2014/12/16/012831](http://biorxiv.org/content/early/2014/12/16/012831)

---

The repository includes a IPython notebook (.ipynb file) that can be downloaded and interactively executed. The code in the IPython notebook will download raw data and process data such that figures in the manuscript are reproduced (in theory). 

---
To execute the IPython Notebook in its entirety you will need:   

* IPython     
* BSMAP   
* bedtools   
* R   
* rpy2 (interface to R from Python)   

---
Note the current version of the IPython Notebook can be viewed (not interactive) with any web browser at:

----
###Instructions

1) Download the repository zip file to a local directory and uncompress.

2) Launch IPython from the repository primary directory. 
For example, using Terminal on MacOSX.

```
$ cd /Desktop/git-repos/olson-ms-nb
$ ipython notebook

```
This will launch IPython in your web browser.  
    
![nb](http://eagle.fish.washington.edu/cnidarian/skitch/Home_1A41E21F.png)

3) Open notebook by clicking on `BiGo_dev.ipynb`. This will open a new tab in your browser


----

The notebook is divided into 5 sections 

* [Downloading data](#Downloading-Files) 

* [Read aligning: BSMAP](#Running-BSMAP) 

* [Global differences: methylkit](#Global-Differences:-methylkit)  

* [Differentially methylated loci: methylkit](#Differentially-methylated-loci)  

* [Genomic location of DMLs: bedtools](#Genomic-location-of-DMLs)   


Please post any comments and questions in issues.