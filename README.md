# Bayesian Hierarchical Model (BHM)

In this repository, we use BHM to estimate parameters for value-based and confidence-based computational models. 

The code is written in modular form to analyze the model parameters from the following tasks: 
- CRDM: confidence and risky decision making 
- CDD: confidence and delay discounting
- CDD_nlh: CDD nonlinear hyperbolic
- CPDM: confidence and perceptual decision making

The code is also written to work for each of the studies that the Computational and Decision Neuroscience (CDN) lab is involved:
- IDM: interoceptive decision making
- SDM: States decision making
- SDAN: CDN's collaboration with SDAN

In order for the script to work, the datafiles need to be stored in the appropriate [BIDS](https://bids.neuroimaging.io/) format. We have the data located in a folder named `split` where each subject has a folder with the tasks they completed. Under each of the task directories, there is a spreadsheet with the naming convention `subjectname_task.csv`. Below you can see an example for how this looks like for the first 10 participants of the IDM project. 

![example BIDS format](img/BIDS_eg.png)


```python

```
