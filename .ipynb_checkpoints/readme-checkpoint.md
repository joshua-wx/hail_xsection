# Hail Cross Section Code

July 2022

This work is part of the following article: Soderholm, J, Kumjian, M, 2022: Automating the Analysis of Hailstone Layers. AMT (submitted).
For question, please contact the lead author (joshua) by posting an issue on this github repo

Data repository: 10.5281/zenodo.6831306

Paper doi: TBA

## Overview

This repo consistent of two set of scripts designed to produce the analysis and figures in the forementioned paper

For processing the cross section photos, the scripts begining with 'xsec' are used

For processing the HGTM dataset, the scripts begining with 'hgtm' are used

## Cross Section Photos Layer Analysis Technique (LAT)

The cross section analysis and figures are generated using three scripts in this order:

1. xsec_resize_img - renders the cross section images as figures for the construction of figure 4
2. xsec_analysis - LAT algorthim and figures 3, 5
3. xsec_stats - analysis of LAT outputs and figure 6

## Hail Growth and Trajectory Model (HGTM)

The hail growth and trajectory model output file (netCDF4) is supplied as part of 

1. hgtm_plots - generate circular hailstone cross sections figures used to construct figure 8
1. hgtm_stats - analysis of HGTM outputs to produce figures 7 and 9