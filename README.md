# Mass Shooting Data Analysis

This study analyzes mass shooting data in the United States, based on the Mother Jones mass shooting database compiled by Follmann et al. (2012, 2024). The dataset covers mass shootings from 1982 through 2023, adhering to the FBI's definition of mass shootings. The data provides a foundation for exploring various aspects of these tragic events, with a particular focus on general trends, visualizations, and an analysis of white shooters aged 20-25.

## Project Structure

The project is organized into several sections:

1. **Data Preprocessing**
    - Standardization of race, location, mental health, and gender labels.
    - Conversion of date and age columns to appropriate data types.
    - Exclusion of incomplete data for the year 2024.

2. **General Analysis**
    - Exploration of gender distribution among shooters.
    - Correlation analysis of numerical features such as the number of fatalities, injuries, etc.
    - Mean analysis of the dataset.

3. **Visualization**
    - Prevalence analysis: time series plot of mass shootings per year.
    - Location analysis: pie chart showing the distribution of shooting locations.
    - Ethnicity analysis: bar plot displaying the percentage of incidents by the shooter's race.
    - Age distribution histograms for white, black, and Asian shooters.

4. **Specific Analyses**
    - Location by Ethnicity: Analyzing the type of locations where shootings occurred by race.
    - Mental Health by Ethnicity: Distribution of prior signs of mental health issues among different races.
    - Random Sampling: Sampling white shooters between 20 and 25 years for qualitative analysis.

5. **Statistical Analysis**
    - Poisson regression to model the number of mass shootings per year.
    - Confidence interval calculation for the proportion of a sample of shooters.

## Data

The dataset used in this study contains information on 149 mass shootings in the United States from 1982 to 2023. It includes variables such as the date of the shooting, the shooter's race, gender, age, location of the shooting, number of fatalities, and whether the shooter exhibited prior signs of mental health issues.

### Data Preprocessing

- **Race Mapping**: Standardizes different representations of race labels.
- **Location Mapping**: Ensures consistency in location data.
- **Mental Health Mapping**: Unifies the representation of mental health issue indicators.
- **Gender Mapping**: Handles variations in gender identification, including cases with transgender identifiers.

## Analysis

The study delves into various aspects of the mass shooting data:

- **Gender Distribution**: The percentage of male, female, and mixed-gender shooters.
- **Correlation Analysis**: Correlation matrix for numerical features with significance indicated.
- **Prevalence**: Trends over time in the frequency of mass shootings.
- **Ethnicity and Age**: Age distribution by race, particularly focusing on white, black, and Asian shooters.
- **Mental Health**: Analysis of prior mental health indicators by ethnicity.

## Visualization

The project includes various visualizations to illustrate the data:

- Bar charts, pie charts, and histograms are used to represent distributions and relationships within the data.
- A time series plot shows the trend of mass shootings over time.
- A Poisson regression model is used to predict the number of shootings over time.

## Qualitative Analysis

The study also includes a qualitative analysis focusing on white shooters aged 20-25. Random sampling is used to select cases for detailed analysis, with a particular focus on mental health indicators.

## Statistical Inference

A confidence interval is calculated to estimate the proportion of shooters within a specific demographic, providing a statistical perspective on the data.

## Conclusion

This project highlights the complex nature of mass shootings in the United States, focusing on different aspects such as gender, race, location, and mental health. The analysis shows that mass shootings are a significant but only partial representation of the broader issue of gun violence in the U.S.

## How to Use

- Clone this repository: `git clone <repository-url>`
- Navigate to the project directory: `cd <project-directory>`
- Install required dependencies: `pip install -r requirements.txt`
- Run the Jupyter Notebook or scripts to reproduce the analysis.


