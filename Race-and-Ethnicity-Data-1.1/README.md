# Broadstreet COVID-19 Data Project

# Health Equity

In March of 2020, COVID-19 spread through the United States. To combat the absence of data in the pandemic, the COVID-19 Data Project was developed by the Broadstreet team. Initially, the project included daily numbers data. It has since expanded to include data on race and ethnicity, hereon referred to as Health Equity, policy information, and various other intern-led research projects related to  the COVID-19 pandemic. That information can be found here:



*   [COVID-19 Data Project Home](https://covid19dataproject.org/)
*   [Daily Numbers](https://github.com/BroadStreet-Health/daily-numbers) GitHub
*   [Policy](https://github.com/BroadStreet-Health/policy) GitHub
*   [Special Interest Projects Gallery](https://covid19dataproject.org/special-interest-projects/)

The Centers for Disease Control and Prevention (CDC) reports social inequality and health systems issues as a cause for an increased risk of health and socioeconomic impacts as a result of COVID-19 for these groups<sup>1</sup>. Data reporting for race began in early April, with Louisiana being the first to report data<sup>2</sup>. Immediately, disparities in mortality deaths were noticed, and a June 2020 report by the CDC confirmed this disparity was widespread<sup>3</sup>. The need for the aggregate collection of race and ethnicity data became apparent, and the Health Equity team for the COVID-19 Data Project was created in mid-June. The process is ongoing with more counties being added to the dataset each month.

The purpose of the Health Equity team is to collect and report all race and ethnicity data for confirmed cases of COVID-19 across the United States.We publish our data monthly. We report this dataset to include the disparate impacts  of COVID-19 on different racial and ethnic groups.


## Structure of the Dataset


### Definitions



*   Race = a social grouping of people who have similar physical or social characteristics that are generally considered by society as forming a distinct group<sup>4</sup>
*   Ethnicity = a social group that shares a common and distinctive culture, religion, language, or the like<sup>5</sup>


### Dataset


#### Data Entry

Each day, volunteer interns on the Health Equity team enter counts of confirmed cases for the United States counties that are reporting race and ethnicity data. Each county has its own column with race and ethnicity data for each day. To limit errors and increase ease of use, weeks are broken up into separate sheets. The team relies on quality assurance of other team members to ensure there are no lapses in data. As an extra layer of assurance, an additional team member checks all counties and keeps a back-up of any county that does not keep historic data. For some counties, historic data is available and can be retrieved. Once a month, team leads do a sweep of data and engage team members to fill all gaps with historic data sets. 


#### Data Source

Interns collect data from health department sites at both state and county levels, depending on the level of data collection and reporting that the county and state utilize.


#### Data Collection & Input

Data is collected every day for each county in the United States that is reporting at least some race and ethnicity data. To ensure all reporting counties are included, new recruits sweep for new counties at the start of each month.

Data is collected as a cumulative count rather than a daily count. When encountered, only residential data is recorded. Multiracial and biracial categories are included in the “2+ races” category with a note added denoting this discrepancy in categorization. When counties report “Refused to Answer,” this is recorded in “Other” and a note is added to that county’s data going forward.

When counties report data as a percentage, the percentage for each category is multiplied by the total number of confirmed cases to determine the raw data.

When data is not available, often from lack of collection for that category, a - symbol is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder.


#### Coding:


##### Table 1. Race Data


<table>
  <tr>
   <td>Variable Name
   </td>
   <td>Variable Description
   </td>
  </tr>
  <tr>
   <td>White
   </td>
   <td>A person having origins in any of the original peoples of Europe, the Middle East, and North Africa<sup>6</sup>
   </td>
  </tr>
  <tr>
   <td>Black/ African American
   </td>
   <td>A person having origins in any of the black racial groups of Africa<sup>6</sup>
   </td>
  </tr>
  <tr>
   <td>Asian
   </td>
   <td>A person having origins in any of the original peoples of the Far East, Southwest Asia, or the Indian subcontinent<sup>6</sup>
   </td>
  </tr>
  <tr>
   <td>American Indian/ Alaska Native
   </td>
   <td>A person having origins in any of the original people of North and South America (including Central America) and who maintains tribal affiliation of community attachment<sup>6</sup>
   </td>
  </tr>
  <tr>
   <td>Native Hawaiian/ Pacific Islander
   </td>
   <td>A person having origins in any of the original peoples of Hawaii, Guam, Samoa, or other Pacific Islands<sup>6</sup>
   </td>
  </tr>
  <tr>
   <td>2+ Races
   </td>
   <td>A person with parents from two or more races<sup>7</sup>
   </td>
  </tr>
  <tr>
   <td>Other
   </td>
   <td>A person identifying as any other race
   </td>
  </tr>
  <tr>
   <td>Unknown
   </td>
   <td>A person whose race is not known, identified, and/ or recorded
   </td>
  </tr>
</table>



##### Table 2. Ethnicity Data


<table>
  <tr>
   <td>Variable Name
   </td>
   <td>Variable Description
   </td>
  </tr>
  <tr>
   <td>Hispanic
   </td>
   <td>A person of Cuban, Mexican, Puerto Rican, South or Central American, or other Spanish culture or origin, regardless of race<sup>8</sup>
   </td>
  </tr>
  <tr>
   <td>Non-Hispanic
   </td>
   <td>A person not of Cuban, Mexican, Puerto Rican, South or Central American, or other Spanish culture or origin, regardless of race
   </td>
  </tr>
  <tr>
   <td>Not Specified
   </td>
   <td>A person whose ethnicity is not known, identified, and/or recorded
   </td>
  </tr>
</table>


*Ethnicity data is inclusive of all race categories.


##### Table 3. State-Specific Information


<table>
  <tr>
   <td>State
   </td>
   <td>Data Lag
   </td>
   <td>Historic Data
   </td>
   <td>Reporting Anomalies
   </td>
  </tr>
  <tr>
   <td>Alabama
   </td>
   <td>Not updated on weekends
   </td>
   <td>No
   </td>
   <td>Race: only white, black, and other
   </td>
  </tr>
  <tr>
   <td>Arizona
   </td>
   <td>-
   </td>
   <td>Yes
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>California
   </td>
   <td>Yes
   </td>
   <td>No
   </td>
   <td>Each county updates differently (use county websites)
   </td>
  </tr>
  <tr>
   <td>Colorado
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Delaware
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Florida
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>Automated
   </td>
  </tr>
  <tr>
   <td>Georgia
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Idaho
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Illinois
   </td>
   <td>-
   </td>
   <td>Yes (about 10 days)
   </td>
   <td>Race: no multiracial
<p>
Ethnicity: only Hispanic
   </td>
  </tr>
  <tr>
   <td>Indiana
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>Data Entered through Scripts
   </td>
  </tr>
  <tr>
   <td>Iowa
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Kansas
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Kentucky
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>Each county updates differently (use county websites)
   </td>
  </tr>
  <tr>
   <td>Louisiana
   </td>
   <td>Updates only on Wednesdays
   </td>
   <td>No
   </td>
   <td>Race: only white, black, other, and unknown
   </td>
  </tr>
  <tr>
   <td>Maryland
   </td>
   <td>County Variation: some update weekly, irregularly, or not at all
   </td>
   <td>No
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Michigan
   </td>
   <td>Not updated on Sundays
   </td>
   <td>No
   </td>
   <td>Race: Asian and Pacific Island are combined
<p>
Ethnicity: no data
   </td>
  </tr>
  <tr>
   <td>Mississippi
   </td>
   <td>-
   </td>
   <td>Yes
   </td>
   <td>Race: No mutliracial or Hawaiian; data is separated by ethnicity
   </td>
  </tr>
  <tr>
   <td>Missouri
   </td>
   <td>Daily updates with a 3-day lag
   </td>
   <td>No
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Nebraska
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>North Carolina
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Ohio
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>Race & Ethnicity: Combines Refused to Answer and Unknown into “Unknown”
   </td>
  </tr>
  <tr>
   <td>Oklahoma
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>Race: Multiracial and Other combined into “Other,” no Hawaiian
<p>
Ethnicity: no data
   </td>
  </tr>
  <tr>
   <td>Oregon
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Pennsylvania
   </td>
   <td>County Variation: some update irregularly
   </td>
   <td>No
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>South Carolina
   </td>
   <td>-
   </td>
   <td>Yes
   </td>
   <td>Race: Does not include multiracial; combines Asian, American Indian, and Native Hawaiian into “Asian”
   </td>
  </tr>
  <tr>
   <td>Tennessee
   </td>
   <td>County Variation: some update weekly, irregularly, or not at all
   </td>
   <td>No
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Texas
   </td>
   <td>County Variation: some update on a weekly basis
   </td>
   <td>No
   </td>
   <td>Each county updates differently
   </td>
  </tr>
  <tr>
   <td>Virginia
   </td>
   <td>-
   </td>
   <td>Yes
   </td>
   <td>Automated
   </td>
  </tr>
  <tr>
   <td>Washington
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>West Virginia
   </td>
   <td>-
   </td>
   <td>No
   </td>
   <td>Race: Only white, black and other
   </td>
  </tr>
  <tr>
   <td>Wisconsin
   </td>
   <td>-
   </td>
   <td>-
   </td>
   <td>-
   </td>
  </tr>
</table>



### Methodology


#### Challenges


##### Reporting Method Variation

The first challenge the team encountered was the discrepancies in reporting between counties. This includes the reporting of data as both raw data counts and percentages of the total confirmed cases. In addition, there are variations in categorization and reporting. For instance, some counties report 2+ races as biracial or multiracial or do not report one of our designated categories at all.


##### Data Releases

The next challenge interns face is the complications of a technology-based reporting system. Throughout the project, there have been technical difficulties with sites crashing, unclear reporting times based on test-updates. There is also wide variation in when counties report ranging from weekly to hourly updates. For that reason, we record data daily and those counties reporting less frequently are denoted.


### References



1. Centers for Disease Control and Prevention. Health Equity Considerations and Racial and Ethnic Minority Groups. Centers for Disease Control and Prevention website. Accessed September 15, 2020. [https://www.cdc.gov/coronavirus/2019-ncov/community/health-equity/race-ethnicity.html](https://www.cdc.gov/coronavirus/2019-ncov/community/health-equity/race-ethnicity.html)
2.  Villarosa L. ‘A Terrible Price’: The Deadly Racial Disparities of COVID-19 in America. _The New York Times. _April 29, 2020. Accessed September 15, 2020. [https://www.nytimes.com/2020/04/29/magazine/racial-disparities-covid-19.html](https://www.nytimes.com/2020/04/29/magazine/racial-disparities-covid-19.html)
3. Stokes EK, Zambrano LD, Anderson KN, et al. Coronavirus Disease 2019 Case Surveillance -- United States, January 22-May 30, 2020. MMWR Morb Mortal Wkly Rep 2020;69:759-765. [http://dx.doi.org/10.15585/mmwr.mm6924e2](http://dx.doi.org/10.15585/mmwr.mm6924e2)
4. Barnshaw,J.Race. InSchaefer,RichardT.,ed._EncyclopediaofRace, Ethnicity, and Society_. 1. Thousand Oaks, CA: SAGE Publications; 2008:1091.
5. Dictionary.com. Ethnicity. Dictionary.com website. Accessed August 20, 2020. [https://www.dictionary.com/browse/ethnicity](https://www.dictionary.com/browse/ethnicity)
6. United States Census Bureau. Race. United States Census Bureau website. Accessed September 15, 2020. 		 	 	 https://www.census.gov/topics/population/race/about.html
7. Merriam-Webster. Biracial. Merriam-Webster website Accessed August 20, 2020. https.//[www.merriam-webster.com/dictionary/biracial](http://www.merriam-webster.com/dictionary/biracial)
8. UNited States Census Bureau. Ispanic or Latino Origin. United States Census Bureau website. Accessed September 18, 2020. https://www.census.gov/quickfacts/fact/note/US/RHI725219	


### Suggested Citation

When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)


### Contributors

[Tom Schmitt, PhD](https://www.linkedin.com/in/broadstreet/), [Tracy Flood, MD, PhD](https://www.linkedin.com/in/tracy-flood-md-phd/), [Sabrine Benzakour](https://www.linkedin.com/in/sabrine-benzakour-72bb79169/), [Aisha Saleem](https://www.linkedin.com/in/aisha-saleem-13b7b11b5/), [Sydney Myers](www.linkedin.com/in/sydney-myers-609137128). A full list of the Broadstreet Covid-19 Data Project volunteers can be found here: [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

