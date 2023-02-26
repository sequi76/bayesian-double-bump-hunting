In this directory one can find the notebook to run a toy model.  

First we create fake data.  Where fake data means that data is sampled from PDFs (instead of being simulated).  The workflow is as follows:

- Create fake data
- Bias the parameters of the used PDFs to provide a biased prior to the inference process
- Perform the inference process (using Dynesty)
- Verify that the inference process gets back te correct parameters.  (this works out fine for all parameters amazingly, except for $sigma_{bb}$. However it is still within the allowed posterior.)  

Check the plots that say much.
