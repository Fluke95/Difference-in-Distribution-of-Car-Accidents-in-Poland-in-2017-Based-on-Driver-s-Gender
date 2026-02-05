# Difference-in-Distribution-of-Car-Accidents-in-Poland-in-2017-Based-on-Driver-s-Gender

There is common belief that male are better drivers than female. Intuition says that male may cause more car accidents because they are more risk-takers than female, and more male have driving licence than female. Is it true? In this project I'll attempt to answer this question using Polish car accidents data.

## Key Findings

- **Normalized Data**: When focusing on the number of accidents per 10,000 driving license holders (rather than absolute numbers), the accident rate is significantly higher for males than for females.
- **Statistics**: In 2017, there were approximately **16 accidents per 10,000 male drivers** compared to **7 accidents per 10,000 female drivers**.
- **Significance**: The Chi-Square test confirmed that the difference is statistically significant (p-value < 2.2e-16).

## Methodology

To ensure a fair comparison, the analysis follows these steps:

1. **Data Normalization**: Instead of comparing total accident counts, I calculated the ratio of accidents to the total number of active driving licenses for each gender.
2. **Age Group Breakdown**: Analyzed how driving licenses are distributed across different age and gender groups.
3. **Statistical Testing**: Used the **Chi-Square Test for Independence** to determine if there is a significant association between a driver's gender and the probability of causing an accident.

## Data Sources

The project uses official Polish data from 2017:

1. **Polish Police**: Annual reports on road accidents ([statystyka.policja.pl](https://statystyka.policja.pl/st/ruch-drogowy/76562,Wypadki-drogowe-raporty-roczne.html)).
2. **Central Register of Vehicles and Drivers (CEPiK)**: Data on driving licenses and other permissions ([cepik.gov.pl](http://www.cepik.gov.pl/statystyki)).
