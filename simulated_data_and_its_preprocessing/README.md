# bayesian-double-bump-hunting

## Pre-processing the data

Take the LHC-simulated data and convert it to lists with signal and background events, with only the relevant invariant masses in it

## How to do the processing ?

- take the lhco file, for instance "signal.lhco"
- preprocess it with the c++ script "./lhco_to_csv.exe signal.lhco > signal.csv"
- idem for background
- then run the Python notebook: it collects the outputs from the above files, computes the invariant masses, selects events with both invariant masses in the signal region, and constructs a list with events passing cuts for signal and background.
- the file "lhcdata.pkl" is the complete output of this processing.
