## OpenTelemetry Racing: An Open-Source Analytics Platform for Open-Wheel Motorsport 
Daniel Lindarev, Spring 2026

#### Abstract 

This article introduces OpenTelemetry Racing, an imaginative collaborative analytics system for open-wheel motorsport, utilizing an open-source framework. The various types of open-wheel racing include Formula 1, IndyCar, Formula 2, Formula 3, Formula E, and different levels of grassroots formula divisions. All types of open-wheel racing produce vast volumes of performance data; however, most of this data is trapped within proprietary team electronic systems (e.g., the race car), expensive software (e.g., GPS systems), or between various incompatible formats (e.g., file types). The intention of this open-source project is to create an open-source collaborative platform where members of the community—teams, engineers, developers, drivers, students, simulation racers, and fans—can share, process, analyze, and visualize racing telemetry data in a transparent manner. This paper will describe the project’s goals, who will use it, what features will be available in the platform, what development strategies and technologies will be utilized to bring the platform live, and how open-source principles will be used to facilitate long-term stewardship of the project. 

The principles of transparency, cooperation, contributions by merit, continuous improvement, and accessibility will be central to the OpenTelemetry Racing project. Building a cooperative community to create tools to assist drivers and teams to analyze every possible facet of open-wheel racing (i.e., lap analysis, tire strategy, weather patterns, vehicle optimizations, and racing predictions) by leveraging their passion for motor racing and modern analytics would reduce the barriers to entry for participants and provide a wealth of knowledge and resources available to worldwide racers. 

 

#### Introduction 

Automobile racing is the most advanced form of motorsport from a technology standpoint; every session on the racetrack generates thousands of data points (speed, braking pressure, throttle input, steering angle, tread wear, fuel load, suspension movement, sector times, and weather conditions). Professional teams use this data to improve their lap times, race pace, and strategic decisions. Unfortunately, most advanced analytical tools cost too much money and are very private; for instance, Formula 1 teams use proprietary analytical systems that are very costly, IndyCar teams utilize engineering tools that are only for internal use, and lower-tier teams usually cannot afford to pay for such tools. As a result, fans will rarely be able to obtain detailed information; amateur racers and karting drivers also have difficulties finding affordable methods to analyze their performance. There is a substantial gap within motorsport since there is so much data produced every minute of every day, but there are very few ways to have access to it in terms of usefulness. 

I am proposing an open-source platform called OpenTelemetry Racing to solve this problem. The platform is trying to democratize racing analytics with free, community-built tools for open-wheel motorsport. Users could upload telemetry logs, compare laps, simulate race strategy, study tyre wear and collaborate on performance enhancements. Contributors would keep on adding to the system with their coding, documentation, design and motorsport expertise. This project is a blend of two personal interests of mine, open wheel racing and data analytics. It would allow technical communities and racing communities to collaborate in the spirit of open-source values. 

 

#### Purpose 

OpenTelemetry Racing's goal is to provide access to racing analytics to everyone instead of just being available only to elite racing teams and large spending organizations. Data has become more and more commonplace in motor sports; now, in most cases, data is used as a part of the race strategy to determine where someone may finish as opposed to just relying on the skill of the driver. Analytics play an important role in how to effectively manage tire wear, when to pit, how to implement the undercut strategy, when to save fuel, and how to plan for changing weather conditions. If only the higher-budgeted teams can access the advanced technology needed to compete in today's racing world, then it can diminish the competitive quality of the racing. 

The introduction of OpenTelemetry Racing will provide financial relief to small racing teams, junior formulas, karting teams, and amateur racers who cannot afford expensive engineering software. This platform will give them free alternatives that will provide valuable insight into their racing performance. The platform will also provide educational benefits; students wanting to become motorsport engineers require real-world tools in order to learn how to perform a telemetry analysis. Universities and independent learners would utilize the software to learn how racing data is generated from real-world conditions. Fans would derive benefits from the platform as many race spectators are interested in the technical aspects of a race and enjoy watching technical reviews of tire strategy, race pace, and qualifying data for a race. Therefore, this platform would allow fans to develop a greater understanding of what is happening with the race. Another major reason for the creation of OpenTelemetry Racing is the opportunity for innovation through collaboration with others. Software developed by open-source communities typically experiences more rapid improvements than that developed in closed environments because there are many contributors throughout the world who collaborate on solving problems. Finally, many sim racers would benefit from this resource as iRacing, rFactor 2, Assetto Corsa, and Formula 1 gaming generate telemetry file formats which could be imported into this platform for further analysis by sim racers. 

 

#### Target Audience 

There are multiple key audiences this project will serve. Racing teams (grassroots formulas, karting, Formula SAE, and semi-professional circuit racing) could leverage this platform to improve performance of their vehicles and develop effective race strategies; drivers can analyze their laps, their braking zones, throttle traces, consistency and trends with respect to pace throughout the race; mechanical engineering, computing and data science students interested in motorsport can learn with real-world datasets and realistic tools; fans and content creators may analyze race, visualize strategy battles and provide educational materials for community; and sim racers will benefit from using the platform since competitive sim racers use telemetry data to improve lap times and setup their vehicles for competition. Developers interested in sports analytics or motorsport technology can also contribute code, visualizations, and innovative features to the project. 

 

#### Features 

OpenTelemetry Racing's initial version will be centered around real value-adds and functionality within automotive racing such as a telemetry upload dashboard (users can upload telemetry files from supported racing applications or popular spreadsheets) that can then be converted into a standard format for analysis. A second key element of our product offering is the ability to compare laps with real time data showing speed, brake pressure, throttle input, steering angle and gear selection during the lap and determine how much time the driver gains/loses throughout the lap. This is crucial in motorsports as these comparisons will directly indicate where improvement can occur for the driver. 

Another feature will be an automatic timing app that will allow users to track their session times with the click of a button while they are in the simulator. The app will enable them to determine how their setup is progressing against other drivers. Users can also request feedback from other users on their setups through the app. The driver will have the option of creating an event for all racers to participate in, such as a track day, and any driver can register for that event. The driver will also be able to provide feedback to drivers who are participating in that event by leaving comments for the other drivers. Additionally, there will be an event calendar that will allow drivers to set up events with the click of a button. Each driver will receive notifications based on their set dates and will be permitted to invite other drivers to participate in those events. One of the new features in this app will be that the timing app will be used to calculate lap times based on laps completed in the simulator and compare them with the actual laps completed on the racetrack. Thus, the application will be able to provide a driver with an accurate representation of how well they're doing against the competition. 

 

#### Development Strategy 

The project will be executed in a series of stages. First is establishing the minimum Implementable Product consisting primarily of creating user accounts and a way of uploading input into the system, creating a place to see lap comparison results, interactive charts, providing open API documentation and creating a public GitHub repository. In phase 1, the goal is to establish proof of value for this platform and to generate interest within the early contributor community. Second will be expanding the user base and building the contributor community through implementation of tire wear models, strategy simulator functionality, collaborative working spaces for teams, mobile compatibility, generating a Discord support server, and creating onboarding guides for contributors. As this stage progresses, user input will play a critical role in determining the direction of future developments. Phase 3 will include the addition of advanced analysis capabilities. Future updates of the platform could contain tools for artificial intelligence lap coaching, predictive pace models using machine learning, automated anomaly detection, setup recommendations, integration of live timing data and public access to a motorsport data repository. Such advancements would increase the overall value of this platform for competitive end users. 

 

#### Technology Stack 

As this is a new modern platform for the analysis of data, the front-end of the platform will be developed utilizing React.js in combination with TypeScript and Tailwind CSS to create a fast and responsive front-end experience for users through its user interface design (UI). Data displayed can be graphically represented using data visualization libraries such as D3.js and/or Plotly. The back-end will be built utilizing Node.js to provide user and core service management capabilities but will use Python along with FastAPI for data analytics functions. The functionality that Python provides within the data science community is one of the reasons it's widely used for this type of development. 

The project will utilize the data science libraries of Pandas, NumPy, Scikit-learn, and TensorFlow for building models and performing machine learning. PostgreSQL will be used for managing structured user and platform data, whereas TimescaleDB would be the preferred data management solution for time-based telemetry data. The hosting platform that will be utilized will be either AWS or Google Cloud and will be implemented utilizing Docker Containers and Kubernetes for scalable hosting capabilities. Version control will use Git and GitHub for sharing and maintaining code, whereas GitHub Actions will be required for automating the common practices of Testing & Deployment. All collaborative efforts will use Discord & Slack for operational teamwork. 

 

#### Open Source Management Principles 

In order to run the project successfully, we needed more than just good code (writing). We need leadership and healthy community systems to support the project. Transparency would be one of the most important principles. Every development discussion, bug, feature request, and future road map will be in public view. To have contributors earn each other's trust through their quality of work (meritocracy), rather than their job title or rank. By far, documentation will be at the forefront of everything that we do because many open-source projects fail due to a poorly defined onboarding process. We would maintain setup guides, API documentation, beginner issues, and architecture diagrams so that new contributors would be able to come up to speed quickly. There will be a continual improvement process through regular milestone releases and roadmap reviews. Our community will be inclusive and open to everyone, regardless of a contributor's background in coding, racing, engineering, design, or analytics. A core governance-maintainer group will be responsible for reviewing pull requests and crating the long-term direction for this project with contributions and feedback from our community will be included in any major decisions. 

 

#### Sustainability and Funding 

To sustain viability over time, the long-term project requires continual funding sources. Potential funding sources may include GitHub Sponsors, and/or donations using Patreon to fund hosting and infrastructure costs. In addition, there is an opportunity to build a series of premium tools for users while keeping the original basic tool (system) free. Premium tools could include private workspace for teams; enterprise hosting; AI reporting; and customized dashboards. Partnerships with sim racing leagues, universities, racing schools, karting organizations, motorsport media, etc. may be able to generate additional funding and publicity. The community can support the project by purchasing merchandise (i.e., t-shirts, hats, stickers) that builds the project's identity.  

As the project evolves, grant funding becomes a viable means of funding. The project's combination of an element of education, technology, and accessibility may fall under potential grant categories, such as STEM education; open-source innovation; or technology research related to sports, and typically universities and not-for-profit organizations will fund projects that create a public opportunity for education. The project must demonstrate to the community transparency concerning any funds received. This would provide access to the community to records reflecting how funds have been expended (hosting, developer stipend, infrastructure improvements, community events, etc.). The project can present annual budgets and reports to the community to demonstrate transparency in accordance with the open-source principle of transparency. Overall, the combination of donor funding; revenues from subscriptions; partnership funding; and revenues from merchandise sales; and grant funding; should provide an adequate financial basis for continued growth and support of the project's commitment to openness. 

 

#### Security and Privacy 

Since telemetry data tends to be sensitive and competitive, privacy controls would be critical as users should be able to choose whether or not their sessions are public, private, or anonymous. This new system would include role-based permissions, encrypted storage, audit logs, with the option for two-factor authentication. These protections would build trust among serious racers and teams with OpenTelemetry Racing. 

 

#### License Choice 

For this project, I would prefer to use the Apache 2.0 License due to its permissiveness for commercial use and strong legal protections that can be provided to the contributors. It also includes patent statutes, which are often viewed favorably by established software communities. The Apache 2.0 License would provide an equal balance between being an open and professional platform and would be an appropriate license for a technical platform such as OpenTelemetry Racing. 

 

#### Challenges 

All projects suffer difficulties that OpenTelemetry Racing is no exception to. Data standardization will be problematic due to racing games, simulators, and telemetry systems all carrying multiple data formats resulting in no standardization whatsoever. Retaining contributors is also likely to be a challenge for the project since contributors of open source projects typically go through cycles of participating in project after project and may eventually tire of it. Having analytical tools that are reliable is essential because if this is not the case, users will begin to shun the analytical tools. Finally, the project will also be faced with the challenge of competition from existing paid telemetry products. All these issues require a leadership style that will support active management of the program, a high level of quality control within the program; as well as providing continuous interaction between the users involved in the project. 

 

#### Conclusion 

OpenTelemetry Racing is an emerging intersection between two professions: motorsports (a growing industry) and analytical data analysis. Telemetry is critical in open-wheel motorsports but is currently a barrier because advanced telemetry instrumentation is both expensive and inaccessible to many of its potential users. This project will help bridge the gap between these two areas by developing an open-source, free, community-driven, and open-platform analytical tool for drivers, teams, students, and fans. The platform will enable users to upload their own telemetry data, compare lap times with one another, create tire strategy models, perform predictive analyses on simulated results, as well as develop community-developed tools for other users. Based on open-source principles of transparency, meritocracy, continuous improvement, and inclusive collaboration, OpenTelemetry Racing can benefit from the contributions of people from around the world. When properly established with appropriate leadership, technology, and sustainability, OpenTelemetry Racing may become one of the most valuable open-source projects in the motorsport industry. Most importantly, it will demonstrate that innovative approaches to motorsport can occur without the constraint of having to spend large amounts of money on these approaches or products; rather, through collaboration and sharing knowledge, the advanced tools required for optimum performance will be available to all users. 



#### References 

Apache Software Foundation. “Apache License 2.0.” https://www.apache.org/licenses/LICENSE-2.0/ 

AWS Documentation. “Cloud Infrastructure Services.” https://aws.amazon.com/ 

Formula1.com Technology Analysis Articles. 

GitHub Docs. “About Pull Requests.” https://docs.github.com/ 

Open Source Initiative. “Open Source Licenses.” https://opensource.org/ 

Pandas Documentation. https://pandas.pydata.org/ 

Scikit-learn Documentation. https://scikit-learn.org/ 
