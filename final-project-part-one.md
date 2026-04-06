| [home page](https://passiripie.github.io/pbodhida-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.

# Outline
 
Social media accounts increasingly function as long-term digital identities, preserving personal memories, interactions, and data over many years. As Facebook users age and remain on the platform, a growing number of accounts will eventually belong to deceased individuals. This project explores how demographic trends and mortality projections may lead to a significant increase in deceased Facebook accounts and what that means for digital legacy and personal data ownership.

This topic is important because most users do not consider what happens to their digital presence after death. Deceased accounts continue to store personal information, photos, and interactions, raising questions about privacy, data ownership, and platform responsibility. Through data visualization, I aim to show the potential scale of this issue and increase awareness about digital legacy planning. The project will conclude by encouraging users to think about managing their online presence and understanding how their data may persist beyond their lifetime.

## One-Sentence Summary
As Facebook users age, the number of deceased accounts will grow, raising important questions about digital legacy and ownership of personal data after death.
## User Story
As a reader, I want to understand what happens to Facebook accounts as users age and pass away,
so that I can better manage my own digital legacy and understand how my personal data may persist after death.
I can do this by reviewing my social media account settings, assigning a legacy contact, and deciding what should happen to my data after I pass away.
## Project Structure / Story Arc
1. Introduction: How social media acts as digital memory storage
2. Facebook users are aging: Show age distribution of users and projected age shifting
3. The rise of digital ghosts: Show mortality rates by age group and projected growth of deceased accounts
4. Why this matters: Connect to digital legacy and privacy
5. Call to Action: Actionable takeaways

<img src="JPEG image-4057-93B4-9D-0.jpeg" width="700"/>

## Initial sketches 

<img src="JPEG image-4FDB-A015-4B-0.jpeg" width="1000"/>

These are 2 main charts, and I also plan to include information about mortality rates too, but still not sure about the format.

# The data
This project will use two main datasets: Facebook user demographics by age group and mortality rates by age. Facebook user distribution by age group will be obtained from publicly available demographic statistics such as Statista and Pew Research Center. Mortality data by age will be obtained from Our World in Data, which compiles demographic statistics from international sources. The dataset provides annual probability of death across age groups. I will approximate a 10-year mortality rate for each Facebook age group by converting annual mortality probabilities into cumulative probabilities over a 10-year period. These mortality rates will then be matched to the corresponding Facebook age groups.

To estimate the percentage of Facebook accounts that may belong to deceased users in the next ten years, I will multiply the share of Facebook users in each age group by the estimated 10-year mortality rate for that group. The contributions across all age groups will then be summed to produce an overall estimate. This approach allows me to visualize both the total projected share of deceased accounts and the relative contribution of each age group. The resulting visualizations will support the project’s goal of raising awareness about digital legacy and the persistence of personal data after death.

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|Statista Facebook age distribution |https://www.statista.com/statistics/187549/facebook-distribution-of-users-age-group-usa/     | Distribution of Facebook users by age group            |
|Our World in Data – Probability of dying by age |https://ourworldindata.org/grapher/probability-of-dying-by-age     | This dataset provides annual probability of death for each age group, expressed as a fraction. |
|      |     |             |

# Method and medium
I plan to use Tableau for generating data visuaulizatons, and Shorthand for story-telling presentation.


## References
Supporting methodology for mortality and life expectancy interpretation from Our World in Data: https://ourworldindata.org/life-expectancy

## AI acknowledgements
I used ChatGPT to help me with finding data sources and brainstorming on project structures.
