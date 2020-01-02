# DAAN846 project
 R analysis on a dataset of cocaine smugglers in 2009 Madrid

Individually directed project portion of the DAAN 846 (network and predictive analytics for socio-technical systems https://bulletins.psu.edu/university-course-descriptions/graduate/daan/)

The objective was simply to select a dataset, run various techniques learned from the class on it, and use that to draw conclusions or plans of action.

In this case, the data set contained 51 individuals, and I made my objective to see how best to fragment the network, which in the real world would be done via various law enforcement methods. The end result I arrived at is that action taken to remove 5-6 players - EHJ, RMP, LGM, RJZZ, and either V or CAPV. This reduces the group down to several isolated groups that are cut off from the core players and may wither out. 

That core group however was so strongly knit that the group would survive removal of any key player. So instead, I decided that heavy surveillance of the central figure - OJSR - would be an action likely to yield information on the entire group that could then lead to a spat of arrests.

The project was done within R Studio, so the raw R code is mixed within notes and details on the process (thus R notebook...). 

Due to the images being stitched together at the end, to run it as is would require an installation of ImageMagick (7.0.7-Q16) and a copy of the CSV --  found here as noted in the project itself:  https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/cocainesmuggling
