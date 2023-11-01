__Public Transportation Efficiency Analysis - IBM Cognos__

Dataset link: https://www.kaggle.com/datasets/rednivrug/unisys?select=20140711.CSV

To run the code snippets in these notebooks (DAC_Phase2, DAC_Phase3 and DAC_Phase4), download this dataset and the notebooks and integrate them in your Jupyter workspace. 
Alternatively, open a notebook in the kaggle dataset itself using your kaggle account and try running these snippets in order.

__To produce visualisations__

1. Sign up or Sign in to your IBM Cognos account: https://www.ibm.com/account/reg/us-en/signup?formid=urx-34710
2. Compress the cleaned dataset and upload it into “My Content”
3. Create dashboard and explore visualisations
4. Just drag and drop columns onto visualisation fields.

__Sample visualisations__

A bar chart visualizing the noOfBoardings for each route for RouteID ranging from 100 to 288:

![first](https://github.com/yasvinippriyaa/public-transportation-analysis/assets/139134650/b4de561f-22a6-4eb6-af99-ccd8fb32db29)

__Insights__

RouteID 222.0 has the highest total NumberOfBoardings due to WeekBeginning 2013-07-21.
NumberOfBoardings is unusually high when RouteID is 222 and 300.

Visualizing NoOfBoardings by StopName:

![sec](https://github.com/yasvinippriyaa/public-transportation-analysis/assets/139134650/a58cfcb8-70af-4b20-92a5-0bccd1b6336b)

__Insights__

NumberOfBoardings is unusually high when StopName is X1 King William St.

A heat map representing NoOfBoardings by TripID for the WeekBeginning from 7/7/2013 to 8/25/2013:

![third](https://github.com/yasvinippriyaa/public-transportation-analysis/assets/139134650/a87f91e5-02fa-4e40-9b08-9f93a0a4be96)
