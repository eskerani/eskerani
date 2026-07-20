## Hello!

Welcome to my profile. My name is Emery Kerani - here are some fast facts about me!

* I use he/they pronouns
* I'm fluent in both R, Python, and SQL
* I'm currently a Master's in Data Science student at Willamette University
* I completed my undergraduate studies in Sociology and Data Science, while minoring in Public Health
* I play rugby and watch *a lot* of sports in my free time; I also enjoy photography, drawing, painting, and other creative pursuits


![20250726_203823](https://github.com/user-attachments/assets/6becd2fd-4391-4131-a178-5eb866a35513)

This is me staring directly into the sunset in Forks, WA. 

***

To learn more about some of the projects I've worked on, you can scroll down or jump to what you want to explore:

* [Graduate Projects](#graduate-projects)
* [Environmental Health Hazards and Threats](#environment-health-hazards-and-threats-ehhts)
* [Racial differences in *FIFA* Stats](#racial-differences-in-fifa-stats)
* [Fall Data Challenge 2024](#fall-data-challenge-2024)

***

## Graduate Projects

All of the classes I've taken at the graduate level have culminated in a project focusing on the topic of the class. All are linked below in chronological order, along with a summary of the class and major project findings:

* **Data Ethics:** for this discussion- and writing-based class about the ethical considerations of data science, I contributed to a [group paper about data governance strategies and dilemmas in public health and Indigenous use-cases](https://docs.google.com/document/d/1NPv6ti2NrnaoWvY_HyKukt3pLxtsneZbefKcsdJ50FQ/edit?usp=sharing). My section of the paper (starting on page 17) focuses on the qualities of data that make them difficult to govern and outlines how a commons framework could address these qualities while benefitting those who data are collected about.
* **Python for Data Science:** this class focused on the application of data cleaning and analysis tools in Python, with particular attention paid to pandas, NumPy, and seaborn. My final project (completed with a partner) looked into how [healthcare spending in Oregon](https://docs.google.com/document/d/1yMBY5LJyM52fv01dBceh6UXb3JoeckoBLo_ak1w6LmU/edit?usp=sharing) compares with that in the rest of the country; we found that Oregon's spending in relation to other states varied wildly, with OR spending significantly more than average in some categories (e.g. dental care) and much less than average in others, like prescription drugs. This project emphasized the importance of context and specificity when analyzing large-scale data, as well as challenging us to think of new ways to display a whole lot of data at once.
* **Data Engineering:** after a semester of learning about SQL and data engineering principles, I worked with a group to combine and analyze data about SNAP participation rates, SNAP retailers, and migration at the county level in the US. We [found](https://docs.google.com/document/d/1jN6vYPGy-e2im1nQGZ3tHA1PQGIKy6u6XyY8ubcgcHM/edit?usp=sharing) that when normalized according to a county's population, none of these factors were particularly correlated with each other, suggesting that the presence of SNAP retailers is not necessarily related to the actual poverty rate in a given area. Further, we found a significant divide between counties based on rurality, with rural counties generally having more outmigration and a higher proportion of their populations utilizing SNAP.
* **Machine Learning:** alongside several groupmates I examined [how machine learning performs on real-world data collected by OSHA](https://github.com/eskerani/Grad-projects/blob/main/machine_learning_project%20_final.ipynb). We compared several of the methods we had learned about in class (K-Nearest Neighbors, Support Vector Machines, and Random Forests) to predict whether workplace injuries resulted in hospitalization, and compared model performances using both categorical and text data about injuries. Interestingly, we found that predictions made using narratives about injuries performed almost as well (if not better, in one case) as OSHA-provided categorical variables, confirming that these narratives are an important source of information about injuries.
* **Data Visualization:** completed entirely in R, this class focused on applying principles of accessibility and design to data visualizations. My final project evaluated equity in college athletics through [four interactive visualizations](https://rpubs.com/eskerani/1422641). These visualizations exposed several of the areas where the NCAA is lagging behind in gender equality (namely scholarship allocation, coaches' salaries, and investment in programs). 
* **Capstone:** this project is currently ongoing as of writing! For my final MS project, I'm working solo to analyze the predictive power of several social factors in relation to national incarceration rates, in order to answer the question of whether crime rates or factors like spending on police are better predictors of incarceration rates. In order to answer this question, I've had to combine elements of data engineering, machine learning, visualization, and ethics; the work-in-progress repo can be found [here](https://github.com/eskerani/prison-predictor-capstone). 

***

## Environmental Health Hazards and Threats (EHHTs)

Over the summer of 2024 I worked alongside a team of student and faculty researchers from Willamette's Public Health and Environmental Science departments to complete a community health assessment concerning climate change resilience in Marion and Polk Counties, OR. I was charged with analyzing the results of a survey which was distributed among the counties' communities and garnered over 600 responses. 

### Key findings:

<img width="1501" height="885" alt="image" src="https://github.com/user-attachments/assets/99d30d3c-a6db-4871-81ac-6d216e762168" />

The past EHHTs that had the highest general impact (encompassing overall disruptions to daily life) on the community were the 2021 winter storm and a period of poor air quality caused by wildfire smoke in 2020. These events, along with the 2021 heat wave, also impacted a much larger swath of the community than localized events such as wildfires. Health impacts of these events were generally less clear, but the 2020 wildfire smoke episode was cited as having a significant impact by the largest proportion of respondents.

***

<img width="1436" height="847" alt="image" src="https://github.com/user-attachments/assets/998acd98-6fd5-4bf5-b753-c79c1c11a355" />

Community members were also asked about their concern for future events. These results mirror what we found about impact: respondents were most concerned about wildfire smoke and air quality (72% and 65%, respectively, of respondents chose a 4 or 5 on a Likert scale for these events). Over half of respondents also indicated that they were very concerned about weather-related power outages (58%), severe winter storms (60%), long and hot summers (59%), heatwaves (55%), and wildfires (55%). Events that were of less concern included poor water quality, high levels of pollen, drought, vector-borne diseases, and flooding, indicating that more community education is needed surrounding these events given that they are only going to get worse in the future.

When asked to provide information about a specific event, both the 2020 wildfire smoke event and 2021 winter storm received over 150 responses, demonstrating just how serious these events were for those who experienced them.

***

<img width="944" height="583" alt="image" src="https://github.com/user-attachments/assets/4c304947-d7d9-478c-958a-e7accb67c09e" />

Included in the event-specific section were two questions asking respondents to rate the helpfulness and how difficult it was to find information released about a given event. We found that the difficulty and helpfulness ratings were generally correlated across events, suggesting that information that is more readily available may also be easier to understand (or vice versa). Certain events were harder to find information about than others, including the 2018 Detroit Lake algal bloom, 2021 wildfires, and 2021 winter storm; however relatively few respondents indicated that information for any event was actively difficult to locate.

If you would like to go even more in-depth or look at the findings for individual events, the final report from this project can be found [here](https://docs.google.com/document/d/1hxCkrpYy_8Cn3iKEdeXQWzPdU-dWD5UZ/edit?tab=t.0)!

## Racial Differences in *FIFA* Stats

During the Spring 2025 semester I studied abroad in the UK! While there, I took a class on football (soccer) and society. For one of my assignments for that class, I looked into how football/soccer players' stats differ in *FIFA* based on race.

***

<img width="1342" height="740" alt="image" src="https://github.com/user-attachments/assets/d7cd9bba-21ad-43e4-ad83-316b9d0ae9e5" />

This first graph is based on data gathered by [Campbell & Maloney](https://doi.org/10.1080/14660970.2022.2109805), who analyzed the skill distributions of *FIFA 20*'s top 100-ranked players. I plotted the average difference they found in each skill between Black and white players; this shows that Black players uniformly outperformed white players in defending and physicality - two overall skill groups that are primarily based on physical prowess - as well as every skill which was individually categorized as "physical" type. However, in every category except defending, white players' technical skills were rated more highly than Black players'. 

***

<img width="1027" height="566" alt="image" src="https://github.com/user-attachments/assets/4a2b5ca2-d2be-4879-bb06-af340f9ca93b" />

I also plotted data gathered by [Anderson](https://doi.org/10.1177/21674795231190398), who took a slightly different approach by categorizing players in *FIFA 23* along a continuum of light, medium, or dark skin tone. This complicates the binary representations of the original study, which did not leave room for the effects of colorism or stereotyping about other races. By using a continuum, Anderson revealed that medium-skinned players actually performed *better* on average than white athletes in the mental skills category, while dark-skinned athletes were rated significantly worse than both light- and medium-skinned players; however, both medium- and dark-skinned players performed better than light-skinned players in all physical skill categories, with dark-skinned players being rated the highest. These results suggest that proximity to whiteness plays a significant role in how athletes' play is characterized.

## Fall Data Challenge 2024

In 2024 I worked with a team of two other students to compete in the Fall Data Challenge, which tasked teams with analyzing police call data. We chose to focus on arson-related calls from Portland and Seattle in 2023.

***

<img width="1124" height="640" alt="image" src="https://github.com/user-attachments/assets/50352cbe-d01e-4873-aad5-e961703dcdb9" />

Our initial finding was that Seattle had had significantly more arson calls than Portland, even when adjusted for population using 2020 census data. This was somewhat surprising, as the cities are usually considered pretty comparable to each other. We wondered whether the cities would have any other major differences or similarities in reporting patterns...

***

<img width="1112" height="634" alt="image" src="https://github.com/user-attachments/assets/d807a36c-0916-45de-b061-b1522224fbe6" />

...So we next looked into the distribution of arson calls across the months of 2023. Interestingly, though the initial pattern certainly holds - Seattle *always* had more calls in any given month than Portland - the cities followed very similar call patterns across time. In both cities, calls fell from the beginning of the year until Feb/March, rose until April/May, fell again in June, peaked in July, then fell once again until a smaller uptick in November. This suggests that similar factors (likely weather-related) may have influenced the number of calls made in a given month.

***

<img width="1470" height="614" alt="image" src="https://github.com/user-attachments/assets/7ca0e548-3a89-435d-90e9-bf85e14b25bb" />

Finally, we investigated the spatial distribution of arson calls. What's fascinating here is that while both cities appeared to have clusters of calls near their downtown areas, Seattle also has a cluster that extends southward from its downtown along MLK Jr. way, which is a highway between two neighborhoods. Both of these spatial groupings suggest that industrial/commercialized areas may be more likely to be targeted by arson.

***

Of course, there are several caveats to these data - calls made don't necessarily represent actual numbers of arsons, we had no way of tracking whether the same individual was committing multiple arsons, calls may have simply been about fires and were mislabelled, etc. With all of that being said, we still had a lot of fun and gained some insight into arson patterns in these two cities! Our major recommendation was that both cities figure out what's going on in July to cause such a massive peak, and find some way to prevent whatever it is. 

<!--
**eskerani/eskerani** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
