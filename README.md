<!-- README.md is generated from README.Rmd. Please edit that file -->

# Ecosystem and Socioeconomic Profiles <img src="https://raw.githubusercontent.com/NOAA-EDAB/esp_data_aggregation/abby/hexes/NEespShiny_hex.png" align="right" width="120" /> 

[![](https://img.shields.io/badge/devel%20version-0.1.1-blue.svg)](https://github.com/NOAA-EDAB/NEespShiny)
[![](https://img.shields.io/github/last-commit/NOAA-EDAB/NEespShiny.svg)](https://github.com/NOAA-EDAB/NEespShiny/commits/dev)
[![](https://img.shields.io/badge/repo%20size-16.8%20MB-blue.svg)](https://github.com/NOAA-EDAB/NEespShiny)
[![](https://github.com/NOAA-EDAB/NEespShiny/workflows/gitleaks/badge.svg)](https://github.com/NOAA-EDAB/NEespShiny/actions/workflows/secretScan.yml)

## View current data products
https://noaa-edab.github.io/ESP_docs/docs

## Introduction
Ecosystem and Socioeconomic Profiles (ESPs) are a scientific product to support [Integrated Ecosystem Assessment](https://www.integratedecosystemassessment.noaa.gov/) (IEA). IEA seeks to improve understanding and management of fisheries through incorporating natural, social, and economic data into fisheries analyses and management plans. ESPs are a structured framework developed by the Alaska Science Center to integrate ecosystem and socioeconomic information into the stock assessment process.<sup>[1]</sup>


Here we adapt the ESP process for use in the management of Northeast stocks. Our scientific roadmap consists of these steps:

1. Gather existing data on ecology, biology, socioeconomics, and the human dimension of Northeast fisheries.

2. Conduct a risk analysis of Northeast stocks to determine which stocks are most vulnerable.

3. Create a detailed report for the most vulnerable stocks, incorporating data from the original risk assessment as well as detailed species-specific information.

## Shiny App
This repo houses a Shiny app that provides a Graphical User Interface (GUI) for ESP data visualization and report generation. 

## The Northeast ESP suite 
There are currently 4 github repos associated with the Northeast ESP initiative.

1. [`NOAA-EDAB/esp_data_aggregation`](https://github.com/NOAA-EDAB/esp_data_aggregation) is the original repo and currently houses development and exploratory work.

2. [`NOAA-EDAB/NEesp`](https://github.com/NOAA-EDAB/NEesp) houses an R package that contains relevant data, functions for low-level data analysis and plotting, and report templates.

3. [`NOAA-EDAB/NEespShiny`](https://github.com/NOAA-EDAB/NEespShiny) houses an R Shiny app (in the form of an R package) that provides a graphical user interface for creating reports with the `NEesp` package.

4. [`NOAA-EDAB/ESP_docs`](https://github.com/NOAA-EDAB/ESP_docs) houses reports on Northeast stocks and ecosystem/socioeconomic indicators.

## Next steps
We continue to synthesize existing data on Northeast stocks, environment, and socioeconomics. We are currently refining our data analyses and beginning the preliminary risk assessment process. 

[1]: https://meetings.npfmc.org/CommentReview/DownloadFile?p=8f5233fb-3b62-4571-9b49-8bb7ce675916.pdf&fileName=ESP_Shotwell.pdf

## Northeast ESP Developers

| [atyrell3](https://github.com/atyrell3)                                                         | [rtabandera](https://github.com/rtabandera)                                                                                                    |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| [![](https://avatars.githubusercontent.com/u/77738923?s=100&u=92e54f60ca179f3e41c1a3610fb3ecdb9e233434&v=4)](https://github.com/atyrell3) | [![](https://avatars.githubusercontent.com/u/64960823?s=100&u=ea5abeca602e43d461e964fe8283f703aef63c61&v=4)](https://github.com/rtabandera) |

#### Legal disclaimer

*This repository is a scientific product and is not official
communication of the National Oceanic and Atmospheric Administration, or
the United States Department of Commerce. All NOAA GitHub project code
is provided on an 'as is' basis and the user assumes responsibility for
its use. Any claims against the Department of Commerce or Department of
Commerce bureaus stemming from the use of this GitHub project will be
governed by all applicable Federal law. Any reference to specific
commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce.
The Department of Commerce seal and logo, or the seal and logo of a DOC
bureau, shall not be used in any manner to imply endorsement of any
commercial product or activity by DOC or the United States Government.*

#### Pkgdown site
The pkgdown site is being built from the `dev` branch.
