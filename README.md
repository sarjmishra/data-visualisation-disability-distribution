## Overview\
This project focuses on analysing the disabled population in India using datasets related to disability, employment, education, and the Unique Disability ID (UDID) initiative. The analysis answers the following key questions:\
\
1. How many people are categorised as disabled in India, and what are the different disability categories?\
2. What are the education qualifications of the disabled population?\
3. What percentage of the disabled population is working?\
4. How do gender and age group distributions compare among the disabled population?\
\
## Datasets Used\
The following datasets were used to answer the questions outlined above:\
\
1. **Disabled Population Among Main Workers, Marginal Workers, and Non-Workers**  \
   - Source: [Disabled Population Among Workers](https://www.data.gov.in/resource/disabled-population-among-main-workers-marginal-workers-non-workers-type-disability-age)\
   - Provides insights into the distribution of the disabled population based on employment status (main, marginal, and non-workers).\
\
2. **Disabled Population by Type of Disability, Educational Level, and Sex**  \
   - Source: [Disabled Population by Disability and Education](https://www.data.gov.in/resource/disabled-population-type-disability-educational-level-and-sex)\
   - Focuses on the categorisation of disabilities and educational levels across different genders.\
\
3. **Unique Disability ID (UDID) Dataset**  \
   - Source: [Unique Disability ID Data](https://www.data.gov.in/resource/district-wise-disability-wise-age-group-wise-gender-wise-unique-disability-id-udid-data)\
   - Provides data on the issuance of UDID cards to persons with disabilities (PwDs) across districts.\
\
## User Groups\
The dashboard created from this analysis can benefit the following user groups:\
\
- **Government Officials and Policy Makers**: The dashboard will help them understand the current situation of PwDs in India, evaluate the success of government schemes, and make informed decisions about improving the condition of the disabled population.\
- **Educational Institutions and Employers**: Institutions and employers can use the insights to design inclusive educational programs and create hiring practices that promote diversity and inclusion.\
- **Non-Governmental Organisations (NGOs)**: NGOs working for the rights of disabled individuals can leverage the dashboard to identify the areas where support is needed and launch appropriate campaigns and programs.\
\
## Data Operations\
The data operations performed on the datasets include:\
\
- **Disabled Population Among Workers Dataset**: \
  - Deleted irrelevant columns (e.g., Table Name, State Code, District Code).\
  - Split the "Area Name" column to extract state names.\
  - Converted state names to proper case for Tableau map compatibility.\
  - Removed rows with "Total" values to avoid incorrect calculations.\
\
- **Disabled Population by Type of Disability, Educational Level, and Sex Dataset**:\
  - Split the "Area Name" column based on delimiters such as "-" and "0", "1", "2", and "3" for clean extraction.\
  \
- **Unique Disability ID Dataset**:\
  - The dataset was clean with no missing values. A calculated field for the gender ratio was created in Tableau.\
\
## Insights\
1. **Disability ID Issuance vs. Total Disabled Population**:\
   - Uttar Pradesh has the largest disabled population (~4.9 million), but only 27% (1.33 million) have received UDID cards. Similar patterns are seen in states like Bihar, Rajasthan, and West Bengal, indicating that UDID issuance should be expedited to ensure more PwDs benefit from the scheme.\
\
2. **Gender Disparity in Education**:\
   - While the number of illiterate men and women is nearly the same, the number of literate females is significantly lower across various education levels (primary, secondary, graduate, etc.). This highlights that women with disabilities face greater challenges in accessing education.\
\
## Conclusion\
This analysis provides a comprehensive look at the disabled population in India, focusing on key areas such as disability categories, education, employment, gender, and age group distributions. The findings highlight areas that require immediate attention, such as improving the rate of UDID issuance and addressing gender disparities in education.\
\
## Files\
- `Disability_Distribution.twbx`\
- `Disabled Population Overview.png`\
- `UDID Issuance.png`\
- `README.md` \
\
## How to View\
1. Clone or download the repository.\
2. Open the `Disability_Distribution.twbx` file in Tableau Desktop or Tableau Public.\
3. Explore the interactive dashboard to visualise the findings.\
\
## Contact\
For any questions or further discussion on the findings, feel free to reach out!\
}
