# Assess Potential Risk

This step requires the use of a documented method to assess the risk that small numerators or small denominators may result in conditions that put individuals at risk of being re-identified.

Assessment of potential risk for a given data set must take into account a range of contributing considerations. This includes understanding particular characteristics of a given data set that is being released. For example, if the potential values for a specific personal characteristic, such as race, results in many small numbers in data set A but does not in data set B, then the risk may be low for data set B and high for data A if the groupings of the personal characteristics include the same categories. For this reason, each department or program may set different values for risk based on the underlying distribution of these variables in the data sets of interest.

There are many methods\[1] used to assess potential risk. Many of the methods that are in use throughout the country are described in the various references provided in Section 15. While each department will document the method(s) chosen for use, all the CalHHS departments are directed to use the following description of the Publication Scoring Criteria as an example and as a method to assess potential risk.

## Publication Scoring Criteria: Example of tool to assess potential risk

The Publication Scoring Criteria is used to identify the presence of small values that are considered sensitive in order to facilitate the assessment of potential risk. The Publication Scoring Criteria combines a number of conditions that increase the risk of a given data table and allows the department to evaluate those risks in combination with each other. The variables included in the Publication Scoring Criteria are those variables routinely used to publish data but are not all inclusive.

A variable is a symbol representing an unknown numerical or categorical value in an equation or table. A given variable may have different ranges assigned to it. Ranges assigned to the variable may be defined many ways which may increase or decrease the risk of identification of an individual represented in the table. This is seen in the Publication Scoring Criteria in that ranges for variables which will produce smaller groupings have a higher score.

The Publication Scoring Criteria in Figure 6 quantifies with a score two identification risks: size of potential population and variable specificity. The Publication Scoring Criteria is used to assess the need to perform statistical masking as a result of a small numerator, small denominator, or both. The Publication Scoring Criteria takes into account both variables associated with numerators, such as Events, and with denominators, such as Geography.

This method requires a score less than or equal to 12 for the data table to be released without additional masking of the data. Any score over 12 will require the use of statistical masking methods described in section 4.4 or documentation regarding the specific characteristics of the data set that mitigate the risk.

When identifying the score for each variable, use the highest scoring criteria. For example if a table had age groups of 0 to 11 years, 12 to 14 years, and 15 to 18 years then the score for the “age range” variable would be +5 because the smallest age range is 12 to 14, which is an age range of three years.&#x20;

If a variable has greater granularity than the score listed, use the highest score listed. For example, if the variable “Time” has a frequency of “weekly” then the score would be +5 which is the maximum score associated with the most granular level (monthly) of the variable in the Publication Scoring Criteria.

In addition to assessing the granularity of each variable, the interaction of the variables is also important. As discussed later in section 6.5, decreasing the granularity or the number of variables are both techniques for increasing the values for the numerators. The final criteria in Figure 6 is that for Variable Interactions. This provides for subtraction of points if the only variables presented are the events (numerator), time, and geography, and an addition of points for including more variables in a given presentation. With respect to the subtraction of points, the score is based on the minimum value for the Events variable. For example, if the smallest value for the Events is 5 or more, then the score would be -5. However, if the smallest value for the Events is 2, then the score would be 0. This is discussed in more detail in Section 6.2.

In assessing risk, scoring can be part of the justification to release or not release data but should not by itself be an absolute gateway to the release data. The review must take into account additional considerations including those that are discussed in this document in addition to the scoring.

## Publication Scoring Criteria Tables by Variable

### Events (Numerator)

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>1000+ events in a specified population</td><td>+2</td></tr><tr><td>100-999 events</td><td>+3</td></tr><tr><td>11-99 events</td><td>+5</td></tr><tr><td>&#x3C;11 events</td><td>+7</td></tr></tbody></table>

### Age Range

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>>29-year age range</td><td>+1</td></tr><tr><td>11-29 year age range</td><td>+2</td></tr><tr><td>6-10 year age range</td><td>+3</td></tr><tr><td>3-5 year age range</td><td>+5</td></tr><tr><td>1-2 year age range</td><td>+7</td></tr></tbody></table>

The following two tables can be used for data that complies with current OMB standards (which combines race/ethnicity into one variable) and data that complies with previous 1997-2024 OMB standards (which separated race and ethnicity into two variables) as the risk assessment is the same for both.

### Race or Race/Ethnicity

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African</td><td>+2</td></tr><tr><td>White, Asian, Black or African American, Hispanic or Latino, Middle Eastern or North African, American Indian or Alaska Native, Native Hawaiian or Other Pacific Islander, Mixed</td><td>+3</td></tr></tbody></table>

### Detailed Race or Race/Ethnicity Combined

<table><thead><tr><th>Characteristics</th><th width="100" align="center">Score</th></tr></thead><tbody><tr><td><p>Detailed Ethnicity with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td align="center">+1</td></tr><tr><td><p> Detailed Race with Population 300,001 – 4,000,000</p><p><em>e</em>.<em>g., Chinese, Filipino, German, Asian Indian, Italian, Korean, Salvadoran, Guatemalan</em></p></td><td align="center">+2</td></tr><tr><td><p>Detailed Race with Population 100,001 – 300,000</p><p><em>e.g., Japanese, Armenian, Iranian, Aztec, Portuguese, Taiwanese, Hmong, Puerto Rican, Peruvian</em></p></td><td align="center">+3</td></tr><tr><td><p>Detailed Race with Population 20,001 – 100,000</p><p><em>e.g., Cambodian, Dutch, Pakistani, Egyptian, Thai, Maya, Afghan, Nigerian, Indonesian, Fijian, Native Hawaiian, Jamaican, Cuban, Colombian, Argentinean</em></p></td><td align="center">+5</td></tr><tr><td><p>Detailed Race with Population ≤20,000</p><p><em>e.g., Tongan, Chamorro, Bangladeshi, Sri Lankan, Brazilian, Mixtec, Kenyan, Zapotec, Malaysian, Belizean, Chumash, Sudanese, Pomo, Inca, Pipil</em></p></td><td align="center">+7</td></tr></tbody></table>

Use the following two tables to assess risk for the ethnicity variable, which will be present in data that follows pre-2024 OMB standards.

### Ethnicity Only

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>Hispanic or Latino - yes or no</td><td>+1</td></tr></tbody></table>

### Detailed Ethnicity

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td><p> Detailed Ethnicity with Population >4,000,000</p><p><em>e.g., Mexican</em></p></td><td>+1</td></tr><tr><td><p>Detailed Ethnicity with Population 300,001 – 4,000,000</p><p><em>e.g., Salvadoran, Guatemalan, Central American, South American</em></p></td><td>+2</td></tr><tr><td><p>Detailed Ethnicity with Population 100,001 – 300,000</p><p><em>e.g., Puerto Rican, Spaniard, Peruvian, Nicaraguan, Honduran</em></p></td><td>+3</td></tr><tr><td><p>Detailed Ethnicity with Population 20,001 – 100,000</p><p><em>e.g., Cuban, Colombian, Argentinean, Dominican, Panamanian</em></p></td><td>+5</td></tr><tr><td><p>Detailed Ethnicity with Population ≤20,000</p><p><em>e.g., Bolivian, Uruguayan, Paraguayan</em></p></td><td>+7</td></tr></tbody></table>

### Language Spoken

<table><thead><tr><th>Characteristics</th><th width="100">Score</th></tr></thead><tbody><tr><td>English, Spanish, Other Language</td><td>+1</td></tr><tr><td><p>Detailed Language with Population 300,001 – 4,000,000</p><p><em>e.g., Chinese, Tagalog, Vietnamese, Korean</em></p></td><td>+2</td></tr><tr><td><p>Detailed Language with Population 100,001 - 300,000</p><p><em>e.g., Persian, Hindi, Arabic, Russian, Japanese, French</em></p></td><td>+3</td></tr><tr><td><p>Detailed Language with Population 20,001 - 100,000</p><p><em>e.g., German, Portuguese, Hmong, Hebrew, Bengali, Polish</em></p></td><td>+5</td></tr><tr><td><p>Detailed Language with Population ≤20,000</p><p><em>e.g., Haitian, Navajo</em></p></td><td>+7</td></tr></tbody></table>

### Sex, Sexual Orientation, and Gender Identity

<table data-full-width="false"><thead><tr><th>Variable</th><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>Sex</td><td>Male or Female</td><td>+1</td></tr><tr><td>Sexual Orientation</td><td>Straight, Gay or Lesbian, Bisexual, Asexual</td><td>+2</td></tr><tr><td>Gender Identity</td><td>Man/Male, Woman/Female, Transgender or Non-Binary </td><td>+3</td></tr><tr><td>Gender Identity</td><td>Man/Male, Woman/Female, disaggregation of Transgender/Non-Binary category into more specific identities (e.g., Genderqueer, Two-Spirit, etc.) </td><td>+5</td></tr></tbody></table>

### Intersex

<table><thead><tr><th>Variable</th><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>Intersex (asked as separate question)</td><td>Yes or No</td><td>+2</td></tr><tr><td>Intersex (combined with Sex question)</td><td>Male, Female, Intersex</td><td>+2</td></tr></tbody></table>

### Expected Payer

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>Medi-Cal, Medicare, Private Insurance</td><td>+1</td></tr><tr><td>Medi-Cal, Medicare, Private Insurance, Self-Pay/Uninsured </td><td>+2</td></tr></tbody></table>

### Immigration Status

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>U.S. Citizen, Foreign Born (can be characterized into Naturalized Citizen, Noncitizen) </td><td>+1</td></tr><tr><td>U.S. Citizen, Foreign Born (can be characterized into Naturalized Citizen, Noncitizen), Lawful Permanent Resident </td><td>+2</td></tr><tr><td>Detailed Immigration Status with Disaggregation of Noncitizen Statuses (Lawful Permanent Resident, Nonimmigrant), with Disaggregation of Nonimmigrants (Temporary Workers, Students, Exchange Visitors, and Refugees and Asylees) </td><td>+7</td></tr><tr><td>Undocumented Immigrants – Refer to High-Risk Populations </td><td>N/A</td></tr></tbody></table>

### Time – Reporting Period

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>5 years aggregated</td><td>-5</td></tr><tr><td>2-4 years aggregated</td><td>-3</td></tr><tr><td>1 year (e.g., 2001)</td><td>0</td></tr><tr><td>Bi-Annual</td><td>+3</td></tr><tr><td>Quarterly</td><td>+4</td></tr><tr><td>Monthly</td><td>+5</td></tr></tbody></table>

### Residence Geography\*

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>State or geography with population >2,000,000</td><td>-5</td></tr><tr><td>Population 1,000,001 - 2,000,000</td><td>-3</td></tr><tr><td>Population 560,001 - 1,000,000</td><td>-1</td></tr><tr><td>Population 250,000 - 560,000</td><td>0</td></tr><tr><td>Population 100,000 - 250,000</td><td>+1</td></tr><tr><td>Population 50,001 - 100,000</td><td>+3</td></tr><tr><td>Population 20,001 - 50,000</td><td>+4</td></tr><tr><td>Population ≤ 20,000</td><td>+5</td></tr><tr><td>Population ≤ 4,000</td><td>+7</td></tr></tbody></table>

### Service Geography\*

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>State or geography with population >2,000,000</td><td>-5</td></tr><tr><td>Population 1,000,001 - 2,000,000</td><td>-4</td></tr><tr><td>Population 560,001 - 1,000,000</td><td>-3</td></tr><tr><td>Population 250,000 - 560,000</td><td>-1</td></tr><tr><td>Population of reporting region 20,001 - 250,000</td><td>0</td></tr><tr><td>Population of reporting region ≤20,000</td><td>+1</td></tr><tr><td>Address (Street and ZIP)</td><td>+3</td></tr><tr><td>Address in rural[1] area</td><td>+5</td></tr><tr><td>Address in frontier [2], [3] area</td><td>+7</td></tr></tbody></table>

### Variable Interactions

<table><thead><tr><th>Characteristic</th><th width="100">Score</th></tr></thead><tbody><tr><td>Only Events (minimum of 5), Time, and Geography (Residence or Service)</td><td>-5</td></tr><tr><td>Only Events (minimum of 3), Time, and Geography (Residence or Service)</td><td>-3</td></tr><tr><td>Only Events (no minimum), Time, and Geography (Residence or Service)</td><td>0</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 1 variable</td><td>+1</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 2 variable</td><td>+2</td></tr><tr><td>Events, Time, and Geography (Residence or Service) + 3 variable</td><td>+4</td></tr></tbody></table>

\* If the geography of the reporting is based on the residence of the individual, use the “Residence Geography”.  If the geography of the reporting is based on the location of service, use the “Service Geography”.

***

\[1] U.S. Census Bureau, 2020 Census ”Urban and Rural” Classifications, [https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html)

\[2] Rural Health Information Hub, ”Health and Healthcare in Frontier Areas”,  https://www.ruralhealthinfo.org/topics/frontier#definition

\[3] U.S. Department of Agriculture Economic Research Service, ”Frontier and Remote Area Codes”, https://www.ers.usda.gov/data-products/frontier-and-remote-area-codes.aspx

***

\[1] Garfinkel, et al., “De-Identifying Government Datasets: Techniques and Governance”, National Institute of Standards and Technology Special Publication 800-188, https://doi.org/10.6028/NIST.SP.800-188
