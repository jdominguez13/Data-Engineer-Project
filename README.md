# Data-Engineer-Project
Repository for the Tampa Bay Rays Data Engineer Project

## Overview
This repository includes a Jupyter Notebook that allows the user to create a baseball card for any baseball player

## Disclaimer
* This notebook includes the use of a Python wrapper specially designed for the MLB Stats API (https://github.com/toddrob99/MLB-StatsAPI) in order to save tipe developing a custom wrapper
* The notebook also includes the use of other modules such as openpyxl, urllib.request, PIL (Pillow), io, Pandas and urllib3 required for the data manipulation and Excel output design
* The module PIL (Pillow) gave me some issues after installing and loading it, but a reboot on my laptop solved that issue


## Output
The Notebook is divided in chunks of code that allows the user to preview different aspects of the baseball card as well of a final chunk of code that generates an output in the form of an Excel file (.xlsx extension).

## Challenges
* Due to the different stats utilized between pitchers and hitters, as well as the career length between different players, I refrained from further formatting the Excel file in order to keep the code shorter
* I could not find the logos in the MLB Stats API so I didn't include it in the card
* Whenever there are multiple players with the same name, David Peralta for example, the code runs into an error and stops. I didn't have time to work out a "try" "except" that would allow to select the player from a list when this happened 
