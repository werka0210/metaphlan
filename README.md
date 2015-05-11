# Tutorial7-Metaphlan
A tutorial for using Metaphlan


1. Clone the GitHub repo into a main folder
2. Create a folder called VirtualPy containing the requirements.txt file into the main folder
3. Run configure_metaphlan.sh by typing ./configure_metaphlan.sh
	This will create a Python Virtual Environment containing all the modules needed to run MetaPhlAn
	See below for more info on Virtual Environments
4. Download MetaPhlAn from the internet while inside directory Tutorial7-Metaphlan
```
hg clone ssh://hg@bitbucket.org/nsegata/metaphlan

```

5. Run datafastq.txt to populate the Data directory
	by typing qsub "".txt
6. Run MetaBowtie2.txt to run Bowtie and save results
7. Run Graphics4.txt to merge files and create heatmaps
8. Download GraPhlAn from the internet while inside directory metaphlan
```
hg clone ssh://hg@bitbucket.org/nsegata/graphlan
```






*Python Virtual Environments
The configure_metaphlan.sh script takes 30 min to run.
