# Overview
This repository contains the balanced annotated dataset referenced in the paper **"Unveiling Vaccine Hesitancy on Twitter: Analyzing Trends and Reasons during the Emergence of COVID-19 Delta and Omicron Variants"**.

The tweets have been extracted for two one-month periods, the first one starting on the date on which World Health Organization (WHO) reported that Delta is a variant of interest (namely April 4, 2021 – May 3, 2021) and the other starting on the date on which Omicron was reported as a variant under monitoring (November 24, 2021 – December 23, 2021).

The aim of the paper is to analyze the dynamics of the public opinion on Twitter concerning COVID-19 vaccination during the considered periods. The vaccine hesitancy reasons during these periods have been analyzed and put into connection with the reasons mentioned in other periods, that have been analyzed by previous studies.

Repository structure:
- dataset: 
  - covid-19-vaccine-stance-delta-omicron-339.csv: contains a balanced dataset with 339 tweets annotated in the categories "against" (0), "neutral" (1) and "in favor" (2) in the context of the present study;
  - covid-19-vaccine-stance-full-5715.csv: contains a balanced dataset with 5715 tweets annotated in the categories "against" (0), "neutral" (1) and "in favor" (2). The dataset has been created by combining the dataset that has been annotated (339 tweets) in the current study with the tweets in an existing dataset (5376 tweets). Further details are available in the paper.

# Usage
In accordance with the Twitter policy, in the annotated dataset, only the tweet ids have been provided. The tweets can be hydrated using a tool such as Twarc (https://github.com/DocNow/twarc) or Hydrator (https://github.com/DocNow/hydrator).
