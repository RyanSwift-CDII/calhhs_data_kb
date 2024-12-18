---
icon: file-chart-column
---

# Types of Reporting

CalHHS programs develop a wide range of information based on different types of data. This is reflected in the various categories shown on the entry page for the CalHHS Open Data Portal, which include:

* Diseases and Conditions
* Facilities and Services
* Healthcare
* Workforce
* Environment
* Demographics
* Resources

Various types of reporting may or may not have a connection to personal characteristics that would create potential risk of identifying individuals.

***

## Budgets and Fiscal Estimates

Budget reporting may include both actuals and projected amounts. Projected amounts, although developed with models that are based on the historical actuals, reflect activities that have not yet occurred and, therefore, do not require an assessment for de-identification. Actual amounts do need to be assessed for de-identification. When the budgets reflect caseloads, but do not include personal characteristics of the individuals in the caseloads, then the budgets are reflecting data in the Providers and Health and Service Utilization Data circles of the Figure 2 Venn Diagram and do not need further assessment. However, if the actual amounts report caseloads based on personal characteristics, such as age, sex, race or ethnicity, then the budget reporting needs to be assessed for de-identification.

***

## Facilities, Service Locations, and Providers

Many CalHHS programs oversee, license, accredit or certify various businesses, providers, facilities and service locations. As such, the programs report on various metrics, including characteristics of the entity and the services provided by the entity.

* Characteristics of the entity are typically public information, such as location, type of service provided, type of license and the license status.
* Services provided by the entity will typically need to be assessed to see if the reporting includes personal characteristics about the individuals receiving the services. Several examples are shown below.

{% hint style="info" %}
a) Reporting number of cases of mental illness treated by each facility – if the facility is a general acute care facility then the reporting of the number of cases does not tell you about the individuals receiving the services.

b) Reporting number of cases of mental illness treated by each facility – if the facility is a children’s hospital then the reporting of the number of cases does tell you about the individuals receiving the services.

c) Reporting number of psychotropic medications prescribed by a general psychiatrist does not tell you about the patients receiving the medications.

d) Reporting number of psychotropic medications prescribed by a general psychiatrist to include the number of medications prescribed by the age group, sex or race/ethnicity of the patients receiving the medications does tell you about the patients receiving the medications.
{% endhint %}

In (a) and (c) above, assessment for de-identification is not necessary as there are no characteristics about the individuals receiving the services. However, in (b) and (d) above, the inclusion of personal characteristics which may be quasi-identifiers, especially when combined with the geographical information about the provider, does require an assessment for de-identification.

***

## Mandated Reporting

CalHHS programs are required to provide public reporting based on federal and California statute and regulations, court orders, and stipulated judgments, as well as by various funders. Although reporting may be mandated, unless the law expressly requires reporting of personal characteristics, publicly reported data must still be de-identified to protect against the release of identifying or personal information which may violate federal or state law.

***

## Survey Data

Survey data, often collected for research purposes, are collected differently than administrative data, and these differences should be considered in decisions about security, confidentiality, and data release.

Administrative data sources (non-survey data) such as vital statistics (e.g., births and deaths), health care administrative data (e.g., Medi-Cal utilization; hospital discharges), reportable disease surveillance data (e.g., measles cases) contain data for all persons in the population with the specific characteristic or other data elements of interest. Most of the discussions in this document pertain to these types of data.

On the other hand, surveys (e.g., the California Health Interview Survey) are designed to take a sample of the ,population and collect data on characteristics of persons in the sample, with the intent of generalizing to gain knowledge suggestive of the whole population.

The sampling methodology developed for any given survey is generally developed to maximize the sample size with the available resources while making the sample as un- biased (representative) as possible. These sampling procedures that are a fundamental part of surveys generally change the key considerations for the protection of security and confidentiality and give an extra layer of masking which can decrease the risk of re-identification. Given the world of artificial intelligence, increased availability of data on social platforms, increased incidences of data hacking, and the passage of new laws on data sharing, there is a much higher risk to re-identify an individual when small numbers are released. Thus, the Publication Scoring Criteria should be used to assess the potential risk and the same Data De-Identification Guidelines should be applied to the survey data..

Also, it is in the context of surveys that issues of statistical reliability often arise—which are distinct from confidentially issues, but often arise in related discussions. We recommend that the estimates be considered statistically unreliable and suppressed if the denominator is based on fewer than 30 sample cases.

A few national and state surveys have adopted various guidelines to de-identify their survey data and various thresholds for the reliability of sample sizes\[1]. If any state or national survey has not adopted its own guidelines to de-identify data and/or threshold of statistical reliability and if the survey is not included in the list of Appendix D, then the above mentioned CalHHS Data De-Identification Guidelines and threshold of 30 sample cases should be observed by the CalHHS departments.

***

## Variables



The following two lists of variables are important to consider when preparing data for release.

{% tabs %}
{% tab title="Personal Characteristics" %}
* Age
* Sex
* Sexual Orientation and Gender Identity
* Intersex
* Race
* Ethnicity
* Language Spoken
* Immigration Status
* Location of Residence
* Education Status
* Financial Status
{% endtab %}

{% tab title="Event Characteristics" %}
* Sexual Orientation and Gender Identity
* Intersex
* Race
* Ethnicity
* Language Spoken
* Immigration Status
* Location of Residence
* Education Status
* Financial Status
{% endtab %}
{% endtabs %}

As stated previously, variables that are personal characteristics may be used to determine a person’s identity or attributes. When these characteristics are used to confirm the identity of an individual in a publicly released data set, then a disclosure of an individual’s information has occurred. Individual uniqueness in the released data and in the population is a quality that helps distinguish one person from another and is directly related to re-identification of individuals in aggregate data. Disclosure risk is a concern when released data reveal characteristics that are unique in both the released data and in the underlying population. The risk of re-identifying an individual or group of individuals increases when unique or rare characteristics are “highly visible”, or otherwise available without any special or privileged knowledge. Unique or rare personal characteristics (e.g., height above 7 feet) or information that isolate individuals to small demographic subgroups (e.g., American Indian Tribal membership) increase the likelihood that someone can correctly attribute information in the released data to an individual or group of individuals.

Variables that are event characteristics are often associated with publicly available information.

Therefore, increased risk occurs when personal characteristics are combined with enough granularity with event characteristics. One could argue that if no more than two personal characteristics are combined with event characteristics then the risk will be low independent of the granularity of the variables. This hypothesis will need to be tested using various population frequencies to quantify the uniqueness of the combination of variables both the in the potential data to be released as well as in the underlying population.
