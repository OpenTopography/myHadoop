[![NSF-0844530](https://img.shields.io/badge/NSF-0844530-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=0844530) 


*UPDATE*
myHadoop is no longer being updated here. Originally written by Sriram Krishnan at SDSC, it is currently being maintained at https://github.com/glennklockwood/myhadoop/ 

myHadoop
--------
myHadoop enables the use of Hadoop in a non-dedicated cluster environment,
being administered by typical batch scheduler. We are currently supporting
the PBS (Moab) and the Sun Grid Engine (SGE) schedulers, although a port to
a scheduler such as Condor would be very trivial.

The pbs-example.sh and sge-example.sh provide an example of how to use
myHadoop with PBS and SGE respectively. For more details, please read the
documentation in the "docs" directory.

Pre-requisites
--------------
myHadoop needs Apache Hadoop 0.20.2 and a batch scheduler such as PBS.

Other
-----
Work was funded by a grant from the NSF Cluster Exploratory (CluE) program (Award# IIS-0844530, PI: Baru, Co-PI Krishnan)
More info: 
http://nsf.gov/awardsearch/showAward?AWD_ID=0844530
