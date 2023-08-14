# Positioning and Power Demands During Cycling in a Sprint Triathlon World Championship

We analyzed power data from athletes in the front bike group of the 2020 sprint triathlon World Championship. Read our preprint on [SportRxiv]() and the  preregistration on the [OSF](https://osf.io/v4dg5).

## Repository

You can find the power and position raw data in the [data](https://github.com/smnnlt/trihamburg/tree/main/data) folder.

The [scripts](https://github.com/smnnlt/trihamburg/tree/main/scripts) folder contains the five analysis scripts. Note that some steps (e.g., Bayesian models) are commented in the scripts, such that the rendering is based on saved intermediate results. To fully reproduce the results, un-comment these sections, though then the processing may take some time.

The [plots](https://github.com/smnnlt/trihamburg/tree/main/plots) folder contains the manuscript plots as well as additional analysis plots (e.g., MCMC diagnostic plots).

You can rerun the analyses of this project using R (4.2.0) and Quarto (1.3.450). Simply download the repository, open it in R, and run the command `renv::restore()` to install all necessary packages.

## License 

The data in this repository are available under a [CC BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/2.0/) license. The code in this repository is additionally licensed under a [MIT](https://github.com/smnnlt/trihamburg/blob/master/LICENSE.md) license.

## Authors

This is a project by Simon Nolte and Jan Oliver Quittmann from the [Institute of Movement and Neurosciences](https://www.dshs-koeln.de/en/institute-of-movement-and-neurosciences/) of the [German Sport University Cologne](https://www.dshs-koeln.de/english/). It has been approved by the local ethics committee (196/2021).


