# Markov-Chain-with-Spatial-Dependencies
This code applies a variant of the Markov chain that explicitly incorporates spatial effects. It is an extension of the Markov class allowing a more complete analysis of the spatial dimensions of transition dynamics. The aim is to provide a methodology for applying the explicit model to spatial dependency analysis.
Here, the question is to study and quantify whether neighborhood context affects transitional dynamics. Rather than estimating a homogeneous law, the model requires the estimation of k transition laws each dependent on spatial neighbor state.

# Code explanation 
This article used published data on confirmed cases of Covid’19 in the 22 regions of Madagascar. These data were discretized to obtain a discrete state of propagation intensity.
This research was carried out with notebook Python and R :
1) The raw data used are in the file “covid_first_wave.xlsx” then classified in 3 three states in “per_week.csv”.
2) Data visualization on the map of Madagascar (a gapfile “features.json” containing the borders of the 22 regions of Madagascar) was performed in “carto.ipynb” and “Visualisation_data.ipynb”.
3) Residence time tests were then performed in “SMM_spatial.Rmd”. And the statistical spatial dependency test in “Moran'I Test.ipynb”, a Python notebook.
4) The semi-Markovian model with simulation has been coded in “Markov_spatial.ipynb”; and Bayesian inference in “Bayesian_inference.Rmd”.

# Help
Please direct all questions to stefanatsilefa@gmail.com
