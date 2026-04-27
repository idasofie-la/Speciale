This README.md file was updated on 19 Jan 2024 by Robert Montgomeriee

# **GENERAL INFORMATION**

1. **Paper information Citation**: Lassen E, Pacey A, Skytte A-B, Montgomerie R (2024) Recent decline in sperm motility among donor candidates at a sperm bank in Denmark MANUSCRIPT in press at HUMAN REPRODUCTION

2. **Brief abstract**: From 2017 to 2019, semen volume, sperm concentration, and total sperm count in the ejaculates of applicants increased by 2-12%. Then, from 2019 to 2022, declined by 1-6%, but none of the year-to-year variation in sperm concentration or total sperm count was statistically significant. In contrast, the motile sperm concentration and TMSC declined significantly by 13 and 16%, respectively, between 2019 and 2022. Thus, the concentration of motile sperm in applicants declined from 25.0 [95% CL: 23.5, 26.5] million/mL in 2019 to 21.8 [20.6, 23.1] million/mL in 2022, and TMSC declined from 87.3 [82.0, 92.9] million per ejaculate in 2019 to 73.1 [68.7, 77.6] million per ejaculate in 2022. 

3. **Originators**
Robert Montgomerie, Department of Biology, Queen's University, Kingston, ON K7L 3N6, CANADA. 
EMAIL: mont@queensu.ca


4. **Contact information**
Robert Montgomerie
Department of Biology
Queen's University
Kingston
ON K7L 3N6 
Canada
email: mont@queensu.ca

5. **Date of data collection**
2017-2022

6. **Geographic location of data collection**
Cities in Denamrk: Aaalborg, Aarhus, Copenhagen, Odense

7. **Information about funding sources that supported the collection of the data**: 

**Canada: **
Natural Sciences and Engineering Research Council (RGPIN/05711-2014) to RDM
Queen's University Research Chair award to RDM

**Denmark:**
Cryos International

# ACCESS INFORMATION

### 1. **Licenses/restrictions placed on the data**: 
CC-BY-NC-SA 4.0
Attribution-NonCommercial-ShareAlike

### 2. **Data derived from other sources**.
Meonthly temperature data from Danish Meteorological Institute (Copenhagen, Denmark)

# DATA & CODE FILES
This data repository consist of 3 data files, 1 R code script, and this README document, with the following data and code filenames and variables

## Data files and variables

### **DATAdonors.csv**
data from accepted sperm donors from four cities in Denmark

* DonorID	= anonymized donor identification
* City	= city where sperm donated at Cryos facility: AAL=Aalborg, AAR = Aarhus, CPH = Copenhagen, ODE = Odense
* DOByr = year that donor was born
* EjacYR	= year of donation
* EjacMO	= month of donation
* EjacDate	= date of donation [year-month-day
* EjacDAY	= day of donation in the EjacMo
* EjacDOY	= day of the year of donation
* ManAge	= dopnor's age when donation was made
* EjacVol	= ejaculate volume (mL)
* TSconc	= total sperm concentration (millions/mL) in ejaculate
* TMSconc	= total concentration of motile sperm (grades a and b) in ejaculate (millions/mL)
* GDaConc	= concentration of grade a sperm in ejaculate (millions/mL)
* GDbConc	= concentration of grade b sperm in ejaculate (millions/mL)
* GDcdConc	= concentration of grades c and d sperm in ejaculate (millions/mL)

### **DATAapplicants.csv**
data from applicants to be sperm donors from four cities in Denmark

Same variables as for DATAdonors.csv

### **DATAtempDEN.csv**
monthly temperature data for Danish cities Aarhus, Aalborg, Copenhagen and Odense

* year = year of temperature record
* month = month of temperature record
* Dept = city where temperature was recorded: AAL=Aalborg, AAR = Aarhus, CPH = Copenhagen, ODE = Odense
* tempL = mean of daily low temperatures
* tempH = mean of daily average temperatures
* tempM = mean of daily high temperatures


# Code scripts and workflow 
1. **RdanishSpermMotility.r**: all the analyses for results for OLS models reported in the paper and Supplementary Material.

### SOFTWARE VERSIONS
R version 4.2.3

loaded packages:
    
    • car_3.1-2
    • visreg_2.7.0
    • correlation_0.8.3
    • DescTools_0.99.48
    • lme4_1.1-32
    • performance_0.10.2
    • psych_2.3.3
    • sjPlot_2.8.14 
    • ggplot2_3.4.2 
    • tidyverse_2.0.0 
    • MuMIn_1.47.5


# REFERENCES
