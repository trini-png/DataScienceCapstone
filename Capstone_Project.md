## Proposed working project title:
“Modeling the Relationship between the Distribution of Acer saccharum (Sugar Maple) and Climate Variables Using WorldClim Data”. 

## Brief background:
As climate change continues to be an issue, studies such as this one can help us understand how different plant species and the environment are beginning to react 
to the changes. Additionally, analyzing how these species are reacting now can allow us to create educated predictions on how they will react to similar, more extreme 
changes in the future. The sugar maple is a foundation species in North American forest ecosystems (specifically in the Northeast) and it is very responsive to 
climate stressors. Using WorldClim bioclimatic variables, the goal of the project is to model the distribution of the species over time and see which variables have 
had a marked effect on the species' geographic distribution. From there, based on species abundance, we can predict how the species will react to potential climate 
stressors in the future. 

## Question:
Which climate variables impact the spatial and behavioral patterns for the species Acer saccharum (sugar maple) the most, and how will sugar maple environmental 
suitability change with the varying climate?

## Hypothesis & Predictions
  Hypothesis: Sugar maples will be more abundant in areas that have moderate temperature and precipitation (i.e. no extreme conditions)
  Prediction: Climatic variables will play a significant role in the distribution of a given species throughout a given region


## Weekly Notes 

# Week 3: Exploratory Data Analysis (EDA)
  - 4/1/26: finished setting up GitHub, both in GitHub website and in RStudio
  - 4/2/26: added and combined all of my data, started thinking about cleaning and EDA
  - 4/3/26: fixed a probelm with the join on my datasets, made my first table, found 5 sources for my intro, mapped out all of my graphs and tables for EDA
  - 4/6/26: finished all of my graphs and tables
    
# Week 4: Data Preprocessing
  - 4/11/26: Loaded all 19 WorldClim raster files, combined them into a stack, and labeled them BIO1–BIO19.
        - Combined GBIF and WorldClim variables into a new, cleaned dataset
        - Removed unnecessary GBIF metadata and redundant variables to reduce noise in the dataset.
        - Assessed missing values across all variables using column-wise NA counts.
        - Replaced missing values in individualCount with 1 to reflect occurrence presence.
        - Created longitude-based bins using 5-degree intervals (also have code for 2 and 10).
        - Aggregated the data by longitude band and year to create a modeling dataset.
        - Calculated total abundance and occurrence counts within each group.
  - 4/12/26:
  
