Esther Valentin 

IS 340 Spring 2026 

May 14, 2026 

INTRODUCTION

The Chicago Public School System is one of the largest educational systems in the country. Ranking the third largest for eleven years but recently becoming the fourth largest in 2022, CPS serves as a critical steppingstone for over 300,000 students (Vevea & Peña, 2023). Considering Chicago’s rich history, it is necessary to consider the political, physical, and institutionalized disparities against students of color, who contemporarily dominate the makeup of the CPS student’s demographic. For example, in 1863 a city ordinance required Black and White students to attend separate schools, and it was not until over 100 years later that Chicago Public Schools finally did undertake a court-ordered desegregation plan in the early 1980s (Chicago Public Schools and Segregation a Historical View of How Education Decisions Have Perpetuated Segregation, n.d.). As an attempt to counter the historical implications for marginalized students of color, my approach to this project starts with the creation of a web application tool as an accessible, educational, and interactive outlet of information. Our website provides users with a user-friendly platform to explore information provided about schools, application timelines, and further statistics. Influential visualizations will be implemented across the site, with the additional feature of allowing users to personalize a visualization by selecting different schools and/or filters. After, users could select a school, and a visualization dashboard will provide further statistics on the selected school. In addition, a small survey will be available to users to directly receive feedback and implement improvements to the website. Users will gain a deeper understanding of 6th–12th grade education in Chicago and be better equipped to navigate their educational options. 

MOTIVATION

The motivation for this project deeply stems from my personal experience and upbringing in Chicago. As a Chicago native who went through multiple types of Chicago Public School Systems including a charter school, academic center, and ultimately a selective enrollment high school, the trajectory of my college career heavily relied on the education and systemic structures I have navigated. Because of the diverse makeup of my education, I was able to experience and perceive the disparities in resource distribution and investments into schools, which correlates with Chicago’s history as a segregated city. My interest and passion for this project and previous analysis stems from my belief in education that began in elementary school, where I immediately knew as a young person, that I wanted to pursue higher education. But for first generation Latinos in my neighborhood, this objective was not quite emphasized or thought of as relevantly tangible. My personal experiences then led me to pursue further research into contemporary statistics.  

Previous exploratory data analysis I’ve conducted on a publicly available CPS dataset revealed startling statistics that projected the extreme difference in possible results, which further motivated me to establish this exploratory tool. The specific dataset I conducted an analysis on was provided by the City of Chicago data catalog, with the title of the dataset reading “Chicago Public Schools – School Progress Reports SY2425”: a report on the 2024 to 2025 academic school year (Chicago Public Schools - School Progress Reports SY2425 | City of Chicago | Data Portal, 2026).  

For example, the visualization below (created by myself on Visual Studio Code) represents the dropout rates of Chicago Public High Schools. Although the visualization could be improved, within the graph the highest dropout rate was 48.65%, whilst the lowest dropout rate was 0.25%. Interestingly enough, the types of schools by their category (military, charter, selective enrollment, etc.) created a notable difference in dropout rate, with the highest dropout rates being amongst certain charter school networks, and the lowest dropout rates among selective enrollment high schools, military schools, and other charter school networks.  

<img width="3941" height="1421" alt="Dropout" src="https://github.com/user-attachments/assets/3e893da9-eab3-4751-b034-31964ec99e74" />

After having conducted the exploratory analysis, I had deeply questioned the proximity of these dropout rates to my life. If I had not attended a selective enrollment high school, where would I have been? Would I even be in college? I am grateful to have the opportunity now to apply my personal experiences and technical understandings to my passion and advocacy for education, access and equity. Our project in particular would approach 6th – 12th grade serving schools as the dramatic decrease from viable high school options in comparison to elementary education. Thus, the Chicago Public School Exploratory Tool is meant to act as a platform that can hopefully improve the understanding and trajectory of the educational careers for further incoming students into the Chicago Public School system.  


PROJECT STATEMENT 

The purpose of the project will be to act as a resource for information and awareness surrounding Chicago Public School Systems and schools. Chicago is a diverse city with varying school systems but at the same time, Chicago is historically one of the most segregated cities in the US, which has limited marginalized communities at an infrastructural, financial, and social level. Under resourced communities are disproportionately affected in their day to day lives, and the youth are often times most vulnerable. Education acts as a resource of change, opportunity, and knowledge, and the quality of education we receive throughout our lives, influences our behaviors, career paths, and life outlooks.  

This Chicago Public School Exploratory project will develop a web application that serves as an exploratory and interactive tool for anyone interested in learning more about Chicago's diverse school systems. Through default and personalized visualizations (based on user-selected options), visual timelines, and a quiz feature, users will gain a deeper understanding of 6th–12th grade education in Chicago and be better equipped to navigate their educational options. 

TARGET AUDIENCE (Split into primary and secondary users) 

Primary Users 

This tool is particularly targeted toward under-resourced communities in the city of Chicago. The interface design is intended to be accessible and useful for students in 6th through 12th grade, their parents, and their families as they navigate the often complex and confusing process of selecting a school or understanding what educational options are available to them. Given Chicago's history of segregation and uneven resource distribution across neighborhoods, many families in under-resourced communities do not have access to the guidance counselors, private consultants, or social networks that could otherwise help them navigate the school system. This tool is designed to fill that gap by providing clear, visual, and interactive information that does not require prior knowledge of how the CPS system works. 

 

Secondary Users  

The tool, established as a public resource is to shared, there is also possibility for collaboration of use amongst community resources, leaders, and programs. Specific roles such as school counselors, nonprofit workers, and local leaders who regularly assist families in making educational decisions could also use this tool as a resource. Organizations such as the Illinois Coalition for Immigrant and Refugee Rights (ICIRR) and Chicago Public Libraries represent potential secondary users who could integrate the tool into their existing community outreach and support programming. 

 

DEVELOPMENT METHODOLOGY (OPEN-SOURCE DEVELOPMENT) 

The Chicago School Exploratory Tool will be developed using an open-source methodology, meaning the codebase, data sources, and documentation will be made publicly available and open to community contribution. This approach is intended to maintain the accessible nature of this project because it emphasizes transparency, community accountability, and iterative improvement over time. The technical stack selected for this project consists of React.js on the frontend, Python and Flask on the backend, D3.js for data visualizations, and PostgreSQL for data storage. These tools were chosen for their accessibility to developers, strong community support, and compatibility with one another. 

Open-source development also aligns with the project's mission in a broader sense. As the tool aims to democratize access to information about Chicago schools, the open-source development model democratizes access to the project itself, individuals with the relevant skills can review the code, suggest improvements, or build on the work that has already been done. Contributor channels for this project include the CPS Open Data Portal, the Illinois Report Card, and the ISBE database, all of which are freely available but require time investment to understand, clean, and structure properly. Other community channels include potential outreach to Chicago public libraries, local nonprofits, and school counselors who could serve as early adopters and feedback sources. 

WORKFLOW MAPPING AND EXPLANATION OF EACH MILESTONE 

The development of the Chicago School Exploratory Tool is organized into four milestone phases, each catalyzed by a condition check that must be satisfied before the project can advance. This structure was informed by the process development workflow chart created for the project, which uses a trigger-condition-action-terminator framework to formalize the logic of each phase. 

Milestone 1: Data Sourcing and Cleaning 

 The trigger for this phase is the confirmation of the project's scope, including an established purpose statement and the identification of CPS data sources. The condition check asks whether the identified data sources are accessible, openly licensed, and up to date which is verified through the CPS Open Data Portal, Illinois Report Card, and ISBE database. If the condition is met, the action phase begins and datasets are downloaded, then data cleaning, normalization, analysis, and storage are carried out. If the condition is not met, alternative sources must be identified before proceeding. 

Milestone 2: Front-end Design and Prototyping 

 This phase is conditioned on whether the data from Milestone 1 has been properly normalized and validated, which checks for missing values, schema errors, and completeness. If the data meets quality standards, the action phases of UI/UX design in Figma and backend setup in Flask and PostgreSQL begin in sequence. If not, the workflow returns to Milestone 1. 

Milestone 3: Completing features for a Minimum Viable Product 

 This phase involves the development of React pages, D3.js visualizations, the quiz feature, and the timeline visualization component. It represents the core technical development work of the project and draws on the front-end and back-end infrastructure established in Milestone 2. 

Milestone 4: Documentation and Deployment 

The condition check here asks whether the MVP meets user needs and reaches the target audience, assessed through user testing and survey feedback. If the condition is met, the final actions include fixing bugs, establishing a GitHub README, completing a version-control audit, and releasing the tool publicly. If not, the project returns to a revision and retest cycle. The terminator for the entire workflow is a publicly accessible and fully documented website. 

 

MANAGING TECHNICAL DEPT  

Throughout the development, deployment, and use of the Chicago School Exploratory Tool, technical debt will be accrued primarily through the choice of a lightweight stack that prioritizes accessibility and speed of development over long-term scalability. The core tools being React.js on the frontend, Python and Flask on the backend, D3.js for visualizations, and PostgreSQL for data storage, each carry their own debt profile. Flask in particular was designed for small-to-medium applications and does not scale well under heavy traffic, meaning a more robust framework would become necessary if the tool were ever adopted at a city-wide level. D3.js introduces debt through its API volatility across major versions, meaning custom visualization code written today may require significant rework in future iterations. Thus, resource allocation and time management are critical for the human effort required for development. For example, the project could be split into four loose phases that approach the resources required on the open canvas previously submitted. The four phases being data sourcing and cleaning (first phase), UI/UX design and prototyping on Figma (second phase), front-end and back-end development (third phase), and integration, testing, and user feedback (fourth phase). The thought process behind this conceptual order relates to the reconfigurability of expertise model in lecture two that acknowledges that different skills are most relevant at different points in the project lifecycle.  

The strategy behind minimizing the initial technical dept incurred was careful consideration of project needs at each stage with correlating constraints, placing an overall focus on resource allocation and time management within the development process. It is critical that initial phases of development are approached in a time-friendly matter especially as data cleaning and visualizations are heavily reliant on accuracy and reliable structures, which aims to avoid downstream consequences such as mentioned in lecture four: the skipping of proper correction, validation, and harmonization. But the data pipeline itself also represents a source of ongoing debt, as it depends on public government datasets from sources like the CPS open data portal and the Illinois Report Card that updates on irregular schedules and outside the project's control. The contributor channels for this project are primarily the CPS open data portal, the Illinois Report Card, and the ISBE (Illinois State Board of Education) database, all of which are freely available but require time investment to understand and clean. Community channels include potential outreach to Chicago public libraries, local nonprofits like ICIRR (Illinois Coalition for Immigrant and Refugee Rights), and school counselors who could serve as early adopters and feedback sources. These relationships take time to build and represent a resource cost that is easy to underestimate on a canvas but critical to the project's real-world impact. 

 

FUTURE DEVELOPMENT 

The future development of the Chicago School Exploratory Tool is oriented around expanding its reach to the populations most likely to benefit from it and local community resources who already focus on our target audience. The primary focus of future development would be among the realms of  establishing utilization workshops with local organizations and nonprofits such as the Gage Park Latinx Council and the Telpochcalli Community Education Project in Little Village, both of which serve communities with high concentrations of families navigating the CPS system without institutional support. These workshops would introduce community members to the tool in a guided, accessible setting, collect feedback directly from the target audience, and foster community trust and inquiry that empowers families to become active participants. 

Further opportunity exists to collaborate with the Chicago Public Library system, which already serves as an established resource hub for families, professionals, and community members across the city. Embedding the tool into the programs of different libraries, whether through digital literacy workshops, after-school sessions, or informational materials could significantly extend our audience. 

CONCLUSION 

This project demonstrates the importance of knowledge surrounding educational opportunities and options within the Chicago Public School System for students and families. Although the tool is not exclusive to these audiences, its use serves as a platform of accessible knowledge, unmasking the confusion and complexity of an important process. Because Chicago's cotemporary structure reflects the historical disparities and embedded in its geography, explicit policies, and educational institutions, this tool aimts to make educational information more accessible, equitable, and navigable; which is ultimately necessary is making knowledgeable decisions about a student's educational journey. The Chicago School Exploratory Tool represents an attempt to meet the needs through thoughtful design, open-source development, and a genuine commitment to the communities it aims to serve. It is the hope of this project that by lowering the informational barriers surrounding school selection and educational navigation, more students and families will be empowered to make informed decisions about their futures. 

 

Sources Cited  

Chicago Public Schools - School Progress Reports SY2425 | City of Chicago | Data Portal. (2026, May 12). https://data.cityofchicago.org/Education/Chicago-Public-Schools-School-Progress-Reports-SY2/twrw-chuq/about_data 

Chicago Public Schools and segregation A historical view of how education decisions have perpetuated segregation. (n.d.). UChicago Consortium on School Research. https://consortium.uchicago.edu/news-item/Chicago-Public-Schools-and-segregation 

Vevea, B., & Peña, M. (2023, November 9). Chicago Public Schools no longer nation’s third largest district. Chalkbeat. https://www.chalkbeat.org/chicago/2022/9/28/23377565/chicago-school-enrollment-miami-dade-third-largest/ 

 
