# bayesian-double-bump-hunting

Original files were too long to be put here, therefore we have put a few sample of the original files to do the processing, and also the real final post-processed file "lhcdata.pkl".

## How to do the processing ?

- take the lhco file, for instance "signal.lhco"
- preprocess it with the c++ script "./lhco_to_csv.exe signal.lhco > signal.csv"
- idem for background
- then run the Python notebook: it colects the vents in these files, copmutes the invariant masses, selects events with both invariant masses in the signal region, and constructs a list with events passing cuts for signal and background.
- the file "lhcdata.pkl" is the complete output of this processing.
