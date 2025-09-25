| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


## Final Project Outline: The International Student's American Dream - A Data Story

# High-Level Summary
This project, "The International Student's American Dream: A Data Story," explores the increasingly difficult career path for international students in the United States. While U.S. universities attract a growing number of talented individuals from around the globe, the post-graduation landscape presents a formidable challenge. The core of this story lies in the stark contrast between the promise of a world-class American education and the reality of securing a work visa in a highly competitive environment.Through a narrative-driven data visualization, this project will weave together data on rising international student enrollment, the staggering financial investment required, and the slim, lottery-based odds of obtaining an H-1B work visa. The goal is to provide a data-backed perspective on the immense pressures and uncertainties facing this ambitious group. The target audience includes prospective international students seeking to manage their expectations, current students navigating their career options, and policymakers or advocates interested in U.S. immigration and labor market dynamics.



# User Stories:
As a prospective international student, I want to see the historical trends of H1B visas so I can realistically assess my chances of working in the U.S. after graduation.
As a current international student, I want to understand the current visa landscape and how my job prospects are tied to broader economic and immigration policies.
As an immigration advocate, I want a clear, data-driven narrative to demonstrate the challenges and inefficiencies of the current U.S. work visa system.


## Initial sketches
# Sketch 1: The Dream Begins
Key Header: The Promise of a U.S. Education: A Rising Tide of Global Talent
Visualization: An area chart showing the total number of new international student enrollments from 2009-2024. A key annotation will point out the post-pandemic rebound, emphasizing the enduring appeal.
Message: This visual establishes the story's foundation: the increasing number of individuals who are starting this journey.
![WechatIMG947](https://github.com/user-attachments/assets/4a5f302a-1f6d-45e9-ade0-b24efb51daa7)

# Sketch 2: The Great Funnel
Key Header: The Bottleneck: Soaring Ambitions Meet a Hard Limit
Visualization: A dual-axis combination chart.
Bars: Represent the total number of H-1B registrations each year, showing a dramatic upward spike.
Line: A stark, flat reference line at 85,000, representing the annual H-1B visa cap.
Message: This is the story's central conflict. The widening gap between the bars and the line provides an immediate, powerful visual of the supply-and-demand crisis.
![WechatIMG948](https://github.com/user-attachments/assets/1ee9ed59-4d58-44cc-a8fd-0ac004f14695)

# Sketch 3: A Roll of the Dice
Key Header: Your Odds of Success Are...
Visualization: A line chart showing the calculated probability of securing an H-1B visa over time (Calculated as (85,000 / Total Registrations) * 100%). The line will show a steep decline. An overlapping line will show the U.S. unemployment rate to explore potential correlations.
Message: This chart translates the abstract competition from Sketch 2 into a personal, sobering statistic, directly answering the user's question: "What are my chances?"
![WechatIMG949](https://github.com/user-attachments/assets/3424113a-d867-4ae4-b2f8-3f94d1751f10)

# The data
H1B Registration and Selection Data: I will manually collect historical data from the USCIS website's annual news releases and alerts. This involves navigating to specific fiscal year updates and compiling the number of registrations and selections into a CSV file. The file will be uploaded to my GitHub repository.
International Student Enrollment Data: I will use the "Open Doors Data" portal provided by the Institute of International Education (IIE). The website offers downloadable datasets that I can use to track enrollment numbers by academic level and field of study over time. A direct link to the data portal will be provided.
U.S. Unemployment Rate Data: I will source this data from the Macrotrends website, which compiles historical data from the U.S. Bureau of Labor Statistics (BLS). This data is available in a clean table format that can be easily copied and pasted or scraped into a CSV. A link to the specific data page will be included.

| Name | URL | Description |
|------|-----|-------------|
|International Student Enrollment|[https://opendoorsdata.org/](https://opendoorsdata.org/)|Sourced from the Institute of International Education's Open Doors Report. This will be used to show the rising number of students beginning this journey.|
|H-1B Registration Data|[https://www.uscis.gov/working-in-the-united-states/temporary-workers/h-1b-specialty-occupations/h-1b-electronic-registration-process](https://www.uscis.gov/working-in-the-united-states/temporary-workers/h-1b-specialty-occupations/h-1b-electronic-registration-process)|Compiled from USCIS press releases. This data is the core of the story, used to illustrate the "bottleneck" of soaring applications vs. a static visa cap.|
|U.S. Unemployment Rate|[https://www.macrotrends.net/datasets/global-metrics/countries/usa/united-states/unemployment-rate](https://www.macrotrends.net/datasets/global-metrics/countries/usa/united-states/unemployment-rate)|Sourced from Macrotrends (compiling BLS data). This provides economic context to see how the job market correlates with visa competition.|

# Method and medium
This project will be developed as a stand-alone, interactive data story using Tableau. I will specifically leverage Tableau's "Story Points" feature to create a guided narrative, moving the audience sequentially through each phase of the story as outlined in the sketches. This approach avoids a static dashboard and instead creates an immersive, explanatory experience.

The final deliverable will be a publicly accessible link to the completed project on Tableau Public. This link will be embedded directly into the project's GitHub page, ensuring the story is interactive and widely accessible to anyone with a web browser, with no specialized software required.

## References
Institute of International Education. (2024). "New International Student Enrollment, 2008/09 - 2023/24." Open Doors Report on International Educational Exchange. Retrieved from https://opendoorsdata.org/.

Macrotrends. (n.d.). U.S. Unemployment Rate 1991-2024. Retrieved from https://www.macrotrends.net/countries/USA/united-states/unempolyment-rate.

U.S. Citizenship and Immigration Services. (n.d.). H-1B Electronic Registration Process. Retrieved from https://www.uscis.gov/working-in-the-united-states/temporary-workers/h-1b-specialty-occupations/h-1b-electronic-registration-process. (Note: Data was compiled from annual news releases linked from this page).

## AI acknowledgements
I used an AI assistant (Google's Gemini) to help complete this project outline. The AI helped refine and structure my high-level summary and project descriptions into clearer, more concise language. While the AI provided assistance with structure and language, the core project concept, data sourcing, narrative arc, and final analysis are my own.
