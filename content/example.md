
# Example Use Case

Primary actor: NN, conflict researcher
Goal: Compare novel predictions to canonical ViEWS predictions
Scope: Interaction with research community
Stakeholders: NN, ViEWS Team

Trigger: 
NN has just produced a dataset containing predictions on GED Fatalities at the
PRIO-GRID-level, using an exotic new modelling technique. They want to compare
these predictions to the canonical ViEWS prediction ensemble, to figure out if
they are better. NN has read about ViEWS offering plotting and metrics which
are useful for comparing predictions from various models.

Workflow:
Actors:
   a) NN - An external conflict researcher
   b) compare.views.com - A front for the ViEWS Team

a) goes to compare.views.com

b) NN is not registered, present NN with a login page

a) Clicks "register" and fills out some metadata, submit

b) Present NN with an upload box, and a form for specifying the kind of data being uploaded 

a) NN enters "PRIO-GRID month" as the UOA and selects the outcome variable

a) NN clicks the upload box and finds the .CSV file containing their new predictions 

b) Validates data
>> Breakpoint, b) validates the data, if there's something wrong, see exp. 1 

b) Infers the geographic span and time span of the data

b) Fetches canonical predictions on the outcome, for the UOA span

b) Store external predictions, associate with NN as author

b) Creates plots, graphs, metrics comparing the two sets of predictions

b) Present NN with a dashboard containing ROC-plots with curves for both models, as well as several metrics

b) Also present NN with download options for plots and tables, in several formats

a) NN is thrilled to see that their predictions are much better than the official ViEWS predictions

a) Download graphs and tables in proper format

NN has now achieved their goal of figuring out whether their predictions are
better than the canonical ViEWS ensemble.

ViEWS Team now has a set of external predictions that are associated with a
user profile, providing new insight into how to create good conflict
predictions.

The End
