# 872EDA-Final-Project

## Summary

This repository explores what listed firms with great ESG performance look like for the purpose of finishing the final report of Spring 2022 ENV872 Environmental Data Analysis (EDA) Course at Duke University. This final report is finished by Min Ruan and Suad Muradov. We identified the research question, retrieved and wrangled the data, do the visualization and run multiple regressions to answer two questions:

* Are ESG scores from different rating agencies consistent without significant divergences?
* How can these ownership structure factors (ownership concentration, blockholders' ownership, independent board ratio, chairman duality) affect ESG performance?

## Investigators

Min Ruan, IMEP Second-year Graduate Student at Duke University, Email: min.ruan\@duke.edu
Suad Muradov, IMEP Second-year Graduate Student at Duke University, Email: suad.muradov\@duke.edu

## Keywords

ESG Ratings, Listed Firms, Ownership Structure, Leadership

## Database Information

**Firm_wind.xlsx**: collected from Wind database including basic characteristics, and financial statement information of 4912 listed firms during 2010-2021 in China.
**ESG.xlsx**: obtained ESG scores from five ESG rating companies from their own databases


## Folder structure, file formats, and naming conventions 

"rawdata" folder: contains two excel files with raw data

"FinalProject.Ruan.Muradvo_files" folder: contains all figures shown as pdf documents and generated by latex

"project templates" folder: contains all templates shared by our EDA professors 

"final report" folder: contains a rmd file including all codes and content, a knitted pdf file and a latex file generated by running the rmd file.

## Metadata

**Firm_wind.xlsx**: one spreadsheet contains basic characteristics, and financial statement information of 4912 listed firms during 2010-2021 in China

Name: Stock name

stockcode: stock ID

IPO_date: the date when listed firms passed IPO

CompanyType: the types of company (state-owned, foreign, public, private, etc.)

Province: the location of the headquarter of listed firms

City: the location of the headquarter of listed firms

IndustryName: the chinese names of industry sectors

IndustryCode: the english code of industry sectors

top1.2021-top1.2010: the shareholdering ratio of the largest shareholder during 2010-2021

top2.2021-top2.2010: the shareholdering ratio of the 2nd largest shareholder during 2010-2021

top3.2021-top3.2010: the shareholdering ratio of the 3rd largest shareholder during 2010-2021

top4.2021-top4.2010: the shareholdering ratio of the 4th largest shareholder during 2010-2021

top5.2021-top5.2010: the shareholdering ratio of the 5th largest shareholder during 2010-2021

top6.2021-top6.2010: the shareholdering ratio of the 6th largest shareholder during 2010-2021

top7.2021-top7.2010: the shareholdering ratio of the 7th largest shareholder during 2010-2021

top8.2021-top8.2010: the shareholdering ratio of the 8th largest shareholder during 2010-2021

top9.2021-top9.2010: the shareholdering ratio of the 9th largest shareholder during 2010-2021

top10.2021-top10.2010: the shareholdering ratio of the 10th largest shareholder during 2010-2021

Chairman2021-Chairman2010: the name of chairman during 2010-2021

GM2021-GM2010: the name of general manager during 2010-2021

Board2021-Board2010: the number of board members during 2010-2021

IndepBoard2021-IndepBoard2010: the number of independent board members during 2010-2021

ROA2010-ROA2021: the return on assets of listed firms during 2010-2021

ROE2010-ROE2021: the return on equity of listed firms during 2010-2021

ROIC2010-ROE2021: the return on invested capital of listed firms during 2010-2021

ROP2010-ROP2021: the return per employee of listed firms during 2010-2021

LEV2010-LEV2021: the debt-to-asset ratio of listed firms during 2010-2021

CurrentRatio2010-CurrentRatio2021: the current ratio of listed firms during 2010-2021

**ESG.xlsx**: five spreadsheets contain five ESG ratings for publicly listed firms in China

Name: Stock name

stockcode: stock ID

2010-2020: ESG scores during the period of 2010-2020

## Scripts and code

The folder "final report" include all codes and content (FinalProject.Ruan.Muradvo.rmd, FinalProject.Ruan.Muradvo.pdf, FinalProject.Ruan.Muradvo.tex). It is comprehensive and one "knit" click can generate a tidy report.

## Quality assurance/quality control

We used packages named `readxl`, `tidyverse`, `lubridate`, `dplyr`, `ggplot2`, `agricolae`, `corrplot`, `PerformanceAnalytics`, `RColorBrewer`, `dummies`, `knitr`, `stargazer`, `psych`, `viridis`, `hrbrthemes`, `plotly`, `cowplot`. The referred websites are many, including but not limited to these below.

<https://www.dataone.org/best-practices/develop-quality-assurance-and-quality-control-plan>
<https://www.dataone.org/best-practices/ensure-basic-quality-control>
<https://www.dataone.org/best-practices/communicate-data-quality>
<https://www.dataone.org/best-practices/identify-outliers>
<https://www.dataone.org/best-practices/identify-values-are-estimated>