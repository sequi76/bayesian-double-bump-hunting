# Bayesian double bump hunting 

# Bayesian inference to study a signal with two or more decaying particles in a non-resonant background

You'll find in this repo all the files needed for the calculation in the paper "Bayesian inference to study a signal with two or more decaying particles in a non-resonant background"

1) [optional] Go to the directory "simulated_data_and_its_preprocessing" and run the c++ to convert lhco to csv, and then thenotebook to convert the csv to a list that conttains the invariant masses of the events passing the cuts. For signal and background.  This notebook creates the final output "lhcdata_test.pkl", which is a demo for the real file "lhcdata.pkl", which is already in the directory.  (Because of siz limits we  haven't put all the lhco files in the repo.)

2) Run the Dynesty sampler in the directory "posterior_sampling_with_dynesty".  You'll find a notebook that imports the file "lhcdata.pkl" (keep the repo directory structure!) and then makes a few plots to visualize the data.  You can then define how much data you want to run with, and how much signal fraction.  Then runs Dynesty dynamic nested sampler and obtains the posterior.  Then it has all the commands to create the plots as in the paper.

Thank you for reading!!!

Feedback: sequi@unsam.edu.ar

