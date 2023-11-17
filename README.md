# Bayesian Hierarchical Model (BHM)

In this repository, we developed a Bayesian Hierarchical Model (BHM) to estimate parameters for value-based and confidence-based computational models. 

## Studies and data organization

The code was written to work for each of the studies that the Computational and Decision Neuroscience (CDN) lab is involved:
- IDM: interoceptive decision making
- SDM: States decision making
- SDAN: CDN's collaboration with SDAN (Dany Pine)

In order for the script to work, the datafiles need to be stored in the appropriate [BIDS](https://bids.neuroimaging.io/) format. The data is located under the study name in a folder named `split`. For example, the IDM study is located in the NIMH fileshare with the following path: `/Volumes/UCDN/datasets/IDM/split`. In the split directory, each subject has a folder with the tasks they completed. Under each of the task directories, there is a spreadsheet with the naming convention `subjectname_task.csv`. Below you can see the contents of the split directory for the first 11 participants of the IDM project, illustrating the organization described. 

<div style="text-align:center"><img src="img/BIDS_eg.png" /></div>

## Running the corresponding Jupyter notebooks

The code works in modular form to analyze the model parameters from the experiments/tasks in each study. The script `hierarchical_model.ipynb` under each task directory can be executed after editing the path to the study. There is a hyperlink below for each study that will take you to the corresponding task script. Otherwise you can navigate using the folders:

- [CRDM](crdm/hierarchical_model.ipynb): confidence and risky decision making
- [CDD](cdd/hierarchical_model.ipynb): confidence and delay discounting
- [CDD_nlh](cpdm/hierarchical_model.ipynb): CDD nonlinear hyperbolic
- [CPDM](cpdm/hierarchical_model.ipynb): confidence and perceptual decision making
