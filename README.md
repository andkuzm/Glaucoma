**Cardiovascular_Disease_Detection**

Author: Andrei Kuzmin


Goal: goal was creating a reliable model, which allows to detect the subject having cardiovascular disease, and as bonus goal, to also find out whether it is possible to get a good result with reduced amount of required data, to allow testing oneself with that data one could get at home alone.


Repository content: init.csv - initial dataset(allowed by license), tests.ipynb - the notebook which contains the way initial data was processed, all the models and grids tested, including final model and tests for reduces data, 


finalComplete.ipynb - notebook showing final model, and its scores, 


finalReduced.ipynb - notebook showing final model, and its scores, when given incomplete data, it is basically the same model, as training another one on incomplete dataset did not show any noticeable improvements, so it requires the same columns, but here the columns were changed, to simulate predicting for reduced amount and quality of data. 


Steps to get the result: by running the tests.ipynb (and pip installing necessary libraries) one will get the results based on which it is possible to differentiate efficency of different models, as for exact parameters in the models, they were gotten either by grid, if so this is also awailable to find in the notebook, or by manual tuning, where I basically changed some parameters and lookes how it chages the scores.
