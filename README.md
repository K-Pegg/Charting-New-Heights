# ![Airplane Composite](https://github.com/K-Pegg/Airline_Data_Project/blob/main/Images/lax-takeoff-02.jpg)

# Charting New Heights:
Perspective on Aircraft Investment & Risk Mitigation

## Overview
This project analyzes airplane accident data in order to determine which aircraft(s) are the lowest risk to begin a new business endeavor: operating private and commercial airplanes. The Undisclosed Company will be able to use this data to decide which aircraft will be their first investment.

## Business Understanding
A company is looking to invest in airplanes, and would like to know which airplanes would be the lowest risk to branch out to offering commercial and private travel options.


## Data 
Understanding: Accident data from the National Transportation Safety Board (NTSB) was used and analyzed. Each accident has an associated unique ID. The data file provides type of aircraft, severity of accident, damage to aircraft, and other characteristics involved with accidents.

Preparation: Our team begins the data cleaning process by investigating the values in the dataset, reviewing the data frame, and then we identify and focus on relevant elements. Then we remove the duplicates, normalize strings, and apply necessary filters to ensure consistency. The subsequent analyses are conducted on this refined dataset, enhancing data quality and facilitating meaningful insights.

## Analysis and Results

This project used Tableau for data analysis. This showed an overview of trends of airplane accidents over time and injured vs. uninjured in accidents per make.
![bubble chart of percentages of uninjured compared to accidents per make](https://github.com/K-Pegg/Airline_Data_Project/blob/katie/Images/01_Uninjured_Accidents.png)
This bubble chart shows the percentages of uninjured per make when involved in an accident. Cessna made up about 47% of the data, which points to Cessna being the safest if involved in an accident. Piper & Boeing are the next two largest values with 26% and 7% respectively.

![bar chart of average uninjured and purpose of flight](https://github.com/K-Pegg/Airline_Data_Project/assets/149449099/3d1f5af1-2fd0-441e-8c39-fa2f9113cfad)

This bar chart shows the average uninjured when compared to purpose of flight. Personal flights have a relatively low average of uninjured passengers when involved in an accident

![car chart of fatal injuries compared to phase of flight](https://github.com/K-Pegg/Airline_Data_Project/blob/katie/Images/03_Fatalities_Phase.png)
This bar chart shows the highest risk phase of flights. Cruise, approach, and takeoff have the highest fatality rate. This gives insight into where additional training and safety measures should be put in place.
 

## Conclusion

Through a comprehensive analysis of aviation accident data spanning various makes, flight types, and phases, we have derived insights that can guide strategic decisions for our aviation endeavor. The data-driven findings provide valuable perspective on safety, risk factors and potential opportunities within the aviation industry.

Cessna being a safe option for private travel as the planes are smaller and still the top choice as far as safety is concerned, with consideration for Boeing in the event that the company decides to go into larger aviation sector.

Exploring the personal flights category our analysis concluded that this sector has a relatively low average of uninjured passengers in accidents with the greatest potential for mainstream use.

Our findings underscore the importance of adopting a holistic appraoch to safety. By considering both aircraft makes and specific flight phases, we can tailor saftey measures and training programs to address the unique challenges associated with different scenarios.

## Next Steps
- Find return on investment comparing smaller & larger airplanes for our company’s entrance into the market
- Develop & implement extra training programs at high-risk flight phase points
- Further Analysis: Cost of repair or replacement, occurrence of accidents & why (pilot error, engine failure, etc.), and investigate airplanes equipped with extra safety features to protect our investment and the passengers aboard.

## Repo Structure
├── Data
├── Images
├── Notebooks
├── README.md
├── Charting_New_Heights.pdf
└── Final.ipynb
