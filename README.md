# Building Identification Survey Analysis (Rajashai - Bangladesh)

## Overview
This repository contains the data analysis conducted on the Building Identification Survey conducted in Bangladesh, focusing on Rajshahi. The primary objective of the survey was to understand the building footprints in Rajshahi, Bangladesh. More than 30,000 buildings spread over 5 wards were surveyed for the project. Each building surveyed was allocated a unique PSU ID for identification purposes. The data analysis primarily focused on identifying missing and duplicate PSU IDs at the initial stage, followed by identifying building footprints and other parameters (as requested by clients) upon completion of the survey.

## Description
A primary survey was conducted in Bangladesh to understand the building footprints for Rajshahi. More than 30,000 buildings spread over 5 wards in Rajshahi were surveyed for the project. Each building to be surveyed was allotted a unique PSU ID for its identification. The primary task in the data analysis was to identify the missing and duplicate PSU IDs at the initial stage. Upon completion of the survey, the data analysis was responsible for identifying building footprints and categories.

## Understanding the Dataset
The session provides a brief understanding of the columns in the dataset:
- Response Code: Unique identification number given to each survey point.
- Grid No (1): Name of Grid in which survey location was present.
- Building Code (1): PSU ID for a building
- Location of the Building (latitude): Latitude
- Location of the Building (longitude): Longitude
- What is the type of building?: Type of Building
- Building Category
- Uses of Holding
- No of floors/storey of the building

## Analysis Methodology
The analysis was conducted using Python programming language and various data analysis libraries such as pandas, NumPy, and Matplotlib. The following steps were performed during the analysis:
- Data preprocessing: Cleaning, filtering, and transforming the raw survey data to identify missing and duplicate PSU IDs.
- Data visualization: Creating visualizations to represent the distribution of building footprints and categories across different wards.

## Parameters Analysed
- Wardwise Missing & Duplicate PSU IDs
- Presence of a Building at location
- Type of Building
- Building Category
- Type of Building vs Building Category
- Use of Building
- Use of Building vs Building Category
- Use of Building vs No of Floors
- No of Floors vs Building Category vs Use of Holding
- No of Floors vs Building Category

## Results
The analysis identified missing and duplicate PSU IDs at the initial stage, ensuring the integrity of the survey data. Additionally,the analysis provided insights into the distribution of building footprints and categories across Rajshahi, facilitating urban planning and development initiatives in the region.

## About Files in Repository
- 

## Dependencies
To run the analysis code, the following Python libraries are required:
- pandas
- NumPy

## Usage
To use the analysis code for your own dataset, follow these steps:
1. Prepare your dataset in CSV format, following the same structure as the provided dataset.
2. Replace the path to the dataset in the analysis code with the path to your dataset.

## Contact Information
For any questions or feedback regarding this analysis, feel free to contact Prajwal More at moreprajwal22@gmail.com.

## Acknowledgments
We would like to thank the survey team and Ecosan Services Foundation (ESF) for their efforts in conducting the Building Identification Survey in Rajshahi, Bangladesh, and making the dataset available for analysis.

## Future Work
Potential future directions for this analysis include:
- Integration of additional data sources to enhance the analysis.
- Implementation of predictive modeling techniques to forecast building trends in Rajshahi.
- Collaboration with local authorities for urban planning initiatives based on the analysis findings.
