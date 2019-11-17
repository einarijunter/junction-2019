# Junction-2019 Project submission

Track: Data Economics

Challenges: The DNA of Helsinki, Social Impact with Finland's Open Data

Link to DEMO: https://app.powerbi.com/view?r=eyJrIjoiMmI1MzgxOWItMDNmMi00ZWY1LTk4YWQtNjYxMWFkMGUwZjczIiwidCI6IjlkOTc1MzBlLThmMjctNDEzNy1hMmE5LTVjYjRkY2YyNmYyZSIsImMiOjh9


### Introduction

Our mission was to find the "hearbeat of Helsinki", visualize its people flow and introduce AI-based soution for people flow forecasting.

The developed tool was done using cloud hosted services, utilizing Microsoft's Azure. The data for the challenge was one provided by Business Finland from their "Hypercell" API.


### Solution

Interacting with Hypercell-API was done using Python hosted on both Azure Notebooks and Azure Machine Learining Service using Jupyter notebooks. The scraped and refined data was stored on Azure and visualized using Microsoft Power BI.

The Jupyter notebooks can be found from `notebooks` folder, while the Power BI visualization file is located in `Power BI` folder.

Python code utilizes common open source libraries:
- numpy
- pandas
- requests
- json
- functools
- asyncio
- time
- datetime
- nest_asyncio

The Machine Learning based forecasts were made using Facebook's `fbprophet` package for time-series.

The Power BI visualization uses community Flowmap visualization from https://github.com/weiweicui/PowerBI-Flowmap/.





Source code for Junction 2019 submission. Challenges "The DNA of Helsinki" and "Social Impact with Finland's Open Data"
