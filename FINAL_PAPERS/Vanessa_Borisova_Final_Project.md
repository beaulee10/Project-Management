## Closet-Sustainability Tracker App
Vanessa Borisova, SP'26, IS 340


### Introduction   

The fashion industry is one of the largest contributors to environmental waste and overconsumption, and college students are a major part of the consumer group driving fast fashion trends. Because students are heavily influenced by social media, online shopping, seasonal trends, and low-cost clothing brands, many purchase large amounts of inexpensive clothing that may only be worn a few times before being replaced. Limited budgets and rapidly changing fashion trends often encourage students to prioritize affordability and convenience over sustainability.

According to the “2015 documentary The True Cost, the world consumes around 80 billion new pieces of clothing every year – 400% more than the consumption twenty years ago,” while “the average American now generates 82 pounds of textile waste each year” (Maiti, 2026).

As a result, many students accumulate overcrowded wardrobes, contribute to textile waste, and unknowingly participate in unsustainable consumption habits. Technology can help address this issue by encouraging students to become more aware of their clothing usage and purchasing behaviors.

This sustainability-focused project primarily focuses into developing an open-source sustainability closet application designed for students to digitally organize their wardrobes while promoting sustainable fashion habits. The application allows users to upload clothing items into a virtual closet, organize outfits, track clothing usage, and receive sustainability-related insights. The goal of the project is to help students make the most of the clothing they already own while reducing unnecessary purchases and clothing waste.

The project is designed as an open-source application, meaning that contributors such as developers, designers, and testers can collaborate publicly throughout the development process. Open-source development encourages transparency, community feedback, and continuous improvement. Because the application involves multiple contributors and development stages, effective project management is necessary to coordinate tasks, manage timelines, reduce risks, and ensure the successful completion of the project.

This paper will go through the different stages involved in implementing and managing the sustainability closet application, including planning, development, testing, deployment, and maintenance. It will also examine the project management methods, design decisions, and HCI concepts used throughout the development process to explain how the application would be successfully managed as an open-source project. 

### Project Overview

The sustainability closet application is a mobile and web-based platform created specifically for college students to manage their wardrobes digitally while learning more sustainable clothing habits. The main objective of the application is to reduce unnecessary clothing purchases and help students make the most of the clothing they already own. Since many students purchase fast fashion items because of affordability, convenience, and trend culture, the application is designed to encourage more intentional wardrobe management and purchasing decisions.	

The application includes several core features that support both organization and sustainability. Users can upload photos of clothing items into a digital closet and categorize them by type, season, color, or frequency of use. Students can create outfit combinations using existing wardrobe items and save outfits for classes, events, or daily activities. The application also tracks how often clothing items are worn, helping users identify which items are overused, underused, or forgotten.

Another major feature of the application is the sustainability dashboard. This section provides users with visual statistics about their clothing habits, such as most-worn items, least-worn items, estimated money saved through outfit reuse, and clothing usage trends over time. By making this information visible, the application encourages students to think more critically about consumption habits and clothing waste.

Additional sustainability-focused features may include resale recommendations, donation reminders, and alerts for clothing items that have not been worn for long periods of time. These features aim to reduce unnecessary purchases and promote reuse instead of disposal.

Because the project is open-source, contributors from different backgrounds can participate in improving the application. Developers may add features or optimize performance, while designers may improve interface usability and accessibility. Community-driven development allows the application to continuously evolve while benefiting from collaboration and feedback.


#### Target Users and Stakeholder
The primary target users for the sustainability closet application are college students and young adults who regularly engage with fast fashion trends and online clothing shopping. Many students purchase clothing frequently due to social pressure, changing trends, and the influence of social media platforms. However, students often have limited budgets and may not fully realize the environmental impact of excessive clothing consumption.

The application is designed to help students become more organized while promoting sustainable decision-making. Users who struggle with overcrowded closets, forgotten clothing items, or repetitive purchases would benefit from the application’s wardrobe management features. The application also appeals to students interested in sustainability, minimalism, budgeting, or personal organization.

Several stakeholders are involved in the success of the project. Users are the primary stakeholders because the application is designed around their needs, behaviors, and feedback. User satisfaction and engagement are critical factors that determine whether the project succeeds.

The project manager plays an important role in organizing contributors, assigning tasks, monitoring progress, and ensuring deadlines are met. Because the project is open-source, the project manager must also coordinate communication between contributors and maintain workflow organization.

Developers are responsible for building the technical functionality of the application, including frontend systems, backend servers, databases, and authentication features. UI/UX designers focus on creating an interface that is intuitive, visually organized, and accessible for students. 

In addition to this, designers also conduct usability testing to identify navigation problems and improve the overall user experience. Other stakeholders may include testers, sustainability researchers, marketing contributors, and open-source community members who help improve the application throughout development. Since the project relies heavily on collaboration between multiple contributors, effective communication between stakeholders is essential for maintaining organization, managing tasks efficiently, and ensuring the project continues progressing successfully. 

### Project Planning and Task Breakdown
Developing the sustainability closet application requires careful planning and organization across multiple project phases. Breaking the project into smaller stages allows contributors to focus on manageable tasks while helping the project manager monitor overall progress.

### Phase 1: Research and Requirement Gathering
The first phase focuses on identifying user needs and defining project requirements. During this stage, contributors would research fast fashion consumption among students and gather information about wardrobe management challenges. User surveys and interviews would help identify common problems students experience when organizing clothing or managing purchasing habits.

During this phase, the project team would focus on conducting student surveys, researching sustainability trends, analyzing competing closet applications, identifying user pain points, creating requirement documents, and defining project goals and deliverables. Conducting student surveys would help the team better understand shopping habits, fast fashion usage, and wardrobe organization challenges among college students. Researching sustainability trends would allow contributors to learn more about clothing waste, overconsumption, and environmentally responsible fashion behaviors. Analyzing competing closet applications would help identify useful features, weaknesses, and opportunities to improve the user experience of the sustainability closet app. Identifying user pain points would help the team understand common frustrations students face, such as overcrowded closets, forgotten clothing items, and unnecessary purchases. Creating requirement documents would establish clear expectations and organize the features that need to be developed throughout the project. Finally, defining project goals and deliverables would help ensure the project remains focused, organized, and aligned with its sustainability objectives during future development phases.

This phase is important because it establishes the foundation for the entire project. Without proper research and planning, developers may create unnecessary features or fail to address important user problems.

### Phase 2: Design and Prototyping
The second phase focuses on designing the user interface and planning user interactions. UI/UX designers would create wireframes and prototypes to visualize the application before development begins.

Tasks during this phase include designing wireframes, creating user flows, building interface prototypes, selecting color palettes and layouts, conducting usability testing, and revising designs based on feedback.

Usability testing is especially important because students expect applications to be simple, fast, and visually organized. Testing helps identify confusing navigation structures or unnecessary complexity before development begins.

The design phase also includes accessibility considerations such as readable typography, responsive layouts, and consistent navigation patterns.

Early sketches and wireframes were created during the design phase to help visualize the layout, navigation structure, and functionality of the sustainability closet application before development began. These sketches helped contributors organize interface elements and identify usability improvements early in the project lifecycle. 

| ![](https://raw.githubusercontent.com/OREL-group/Project-Management/f19ed5e6cea80e98835cc57e0595d54d6b44ebde/FINAL_PAPERS/Screenshot%202026-05-11%20132045.png) |
| :--: |

### Phase 3: Development

The development phase involves building the actual application features and systems. Since the project is open-source, contributors may work on different components simultaneously using collaborative development tools.

Development tasks during this phase would include frontend interface development, backend server setup, database integration, user authentication systems, closet item management functionality, outfit planning systems, sustainability dashboard implementation, and notification systems. Frontend development would focus on creating the visual interface users interact with, while backend development would support data storage and application functionality. Database integration and authentication systems would allow users to securely store wardrobe information and manage accounts. Closet item management and outfit planning features would help students organize clothing and reuse outfits more efficiently. Sustainability dashboards and notification systems would provide users with statistics, reminders, and feedback related to their clothing habits and sustainability goals.

Another feature of the application would include an interactive sustainability map that helps students locate nearby thrift stores, donation centers, clothing recycling locations, and sustainable fashion businesses. This feature would encourage students to participate in more environmentally responsible clothing practices by making sustainable options easier to find and more accessible.

“A lot of environmentally friendly stuff tends to be more expensive. Unfortunately, not every person can afford those items … they’re just trying to get clothes to wear on their back” stated by Tierna Mahoney, Broad Bin Vintage Customer (Acosta, 2024).

Developers would use version control systems such as GitHub to manage code changes and contributor collaboration. This is because pull requests and code reviews to maintain code quality while reducing development conflicts.

Agile sprint planning would help organize development priorities and track task completion efficiently.

### Phase 4: Testing
Testing ensures the application functions correctly and provides a positive user experience before launch. Multiple forms of testing are necessary to identify technical issues and usability problems.

Testing tasks during this phase would include functional testing, bug fixing, accessibility testing, user acceptance testing, performance testing, and mobile responsiveness testing. These tasks would help ensure the application functions correctly, remains accessible to users, performs efficiently, and operates properly across different devices and screen sizes. 

Students participating in testing sessions would provide feedback regarding navigation, usability, and feature usefulness. This feedback helps contributors prioritize improvements before deployment.

### Phase 5: Deployment

Deployment tasks during this phase would include server configuration, security verification, application publishing, contributor documentation, community onboarding, and launch preparation. These tasks would help ensure the application is secure, accessible to users, and properly organized for both public release and future open-source contributors.

Because the project is open-source, documentation is extremely important. Contributors need clear installation instructions, coding guidelines, and contribution processes to participate effectively.

### Phase 6: Maintenance and Continuous Improvement

After launch, the project enters the maintenance phase. Open-source projects continue evolving through contributor collaboration and user feedback.
Maintenance tasks during this phase would include fixing bugs, monitoring application performance, adding new features, updating security systems, reviewing contributor submissions, and improving documentation. These tasks would help keep the application functional, secure, organized, and continuously improving after launch.

Continuous improvement helps the application remain relevant while adapting to changing user needs and sustainability trends.


### References     

Acosta, A. (2024, December 4). College students and the effects of fast fashion. The Daily Campus. https://dailycampus.com/2024/12/04/college-students-and-the-effects-of-fast-fashion/

Maiti, R. (2026, February 3). Fast fashion and its environmental impact in 2026. Earth.Org. https://earth.org/fast-fashions-detrimental-effect-on-the-environment/
