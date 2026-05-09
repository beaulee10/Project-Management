### Mobile App to see Dining Hall Rush
Eman Siddiqi, Spring 2026

### Introduction
Rush Radar is an application idea that will assist students in knowing the extent of activity at the campus dining halls to make informed decisions on which place to dine. In a large university setting, students are known to have very little time between class activities, meetings, work, studying, and other activities. Although dining halls may vary in menus and timings, there remains an issue in knowing the extent of rush and convenience at these places at any particular point in time.

Students at the University of Illinois Urbana-Champaign have various options of dining halls around the campus, ranging from all-you-can-eat dining halls to retail dining. University Housing has been providing students with menus, opening times, nutritional value, allergen information, and meal plans for the dining halls using the Illinois app. Rush Radar specifically addresses the current rush at the dining halls.

### Motivation
The motivation behind Rush Radar comes from the everyday student experience, especially for freshman. Dining decisions are often made quickly, and students usually want to know more than just what food is being served. A dining hall may have good food that day, but if the line is extremely long or there are no seats available, it may not be the best option. Students may also waste time walking across campus only to discover that a dining hall is too crowded.

Rush Radar addresses this issue by helping students make faster, more informed decisions. The app would reduce uncertainty by showing real-time or near-real-time information about dining hall traffic. Instead of guessing based on time of day or word of mouth, students could open the app and immediately compare dining halls based on crowd level, wait time, seating, and convenience.
### Project Statement
The goal of Rush Radar is to design and develop a mobile application that allows students to view dining hall rush levels in a simple and accessible way. The app will provide an easy-to-read dashboard showing which dining halls are busy, moderately busy, or relatively open. It will also include features such as estimated wait times, seat availability, peak-hour predictions, and possibly social or user-submitted updates.

The project is not simply about displaying dining hall information. It is about improving the student decision-making process. Rush Radar will be designed around speed, clarity, and usability so that students can get the information they need in just a few seconds.

### Target Audience
The main target audience for the application "Rush Radar" are college students that eat at university cafeterias. These can include, but are not limited to: dormitory residents, meal plan holders, students attending many classes, and those moving around campus a lot.
In addition, those students with particular requirements or preferences regarding dining can also find the app useful. Those that enjoy quiet dining locations, or dislike standing in line, have less time between classes, or wish to dine with other students may find useful information prior to coming to the cafeteria.
### Primary users
The primary users of Rush Radar are undergraduate students who regularly eat at campus dining halls. First-year students may especially benefit from the app because they are still learning campus routines and may not know which dining halls are crowded at certain times. Students with packed schedules would also be strong users because they need to make quick decisions and avoid wasting time.
A secondary user group could include dining staff or campus dining administrators. If the app collects useful data over time, it could help dining services understand peak traffic patterns, identify overcrowded locations, and improve the overall dining experience.
### Benefits
Rush Radar would provide several benefits to students and the campus community. First, it would save students time by helping them avoid long lines and crowded dining halls. Second, it would reduce stress by making dining decisions easier and more predictable. Third, it could improve the distribution of students across dining locations by encouraging students to visit less crowded options.
The app could also improve accessibility and comfort. Some students may feel overwhelmed in crowded spaces, while others may need a quieter or more open environment. By showing crowd levels and seating availability, Rush Radar would allow students to choose the dining hall environment that best fits their needs.
Another benefit is that the app supports better planning. Students could check the app before leaving class, before heading back to their dorm, or before meeting friends. Instead of relying on guessing, they could make decisions based on actual information.

### Development Methodology
The development of Rush Radar would use a combination of open source development and agile development. This approach would allow the project to remain flexible, collaborative, and responsive to student feedback. 
Open Source Development
Rush Radar could be developed as an open source project so that students, developers, designers, and campus community members can contribute to its improvement. Open source development would make the project more transparent and collaborative. It would also allow other students to learn from the codebase, suggest features, report bugs, or help improve the design.
A strong open source project also needs a welcoming community. Open Source Guides emphasizes that making contributors feel welcome and giving them a positive first experience can help a project grow and sustain participation over time. For Rush Radar, this would mean having clear documentation, beginner-friendly issues, contribution guidelines, and a respectful project culture.

### Agile Development
Rush Radar would also follow an agile development process. Agile software development values working software, collaboration, flexibility, and the ability to respond to change rather than strictly following a fixed plan. This fits Rush Radar because the project would likely change as students test the app and give feedback.
The project could be organized into short development cycles or sprints. Each sprint would focus on a small set of features, such as creating the home screen, building dining hall cards, adding wait-time estimates, or improving the search/filter function. After each sprint, the team could test the app with users and make adjustments based on what students actually need.


### Workflow Mapping
The basic user workflow for Rush Radar would be simple:
A student opens the Rush Radar app.
The home screen displays nearby dining halls.
Each dining hall card shows crowd level, wait time, seating availability, and distance.
The student can filter by “least crowded,” “closest,” “shortest wait,” or “best overall option.”
The student selects a dining hall and views more details, such as menu highlights, hours, and recent user updates.
The student decides where to eat based on the information shown.

The main design priority is reducing the number of steps between opening the app and making a decision. Since students may be walking, rushing between classes, or quickly checking their phones, the interface should be simple and fast. This connects to usability principles such as visibility of system status, recognition rather than recall, consistency, and minimalist design. Nielsen Norman Group’s usability heuristics emphasize that users should be able to understand system information clearly and recover easily from errors.

### Technology
Technology that will be used
Rush Radar would likely be built as a mobile-first application. A possible technology stack could include:

Frontend: React Native or Flutter could be used to build a mobile app that works across iOS and Android. The interface would focus on dining hall cards, map views, filters, and quick status indicators.

Backend: Node.js with Express, Firebase, or Supabase could be used to manage user-submitted updates, dining hall data, and app logic.

Database: Firebase Firestore, PostgreSQL, or Supabase could store dining hall names, locations, crowd reports, timestamps, and historical traffic trends.

APIs/Data Sources: The app could use available dining hall menu and hours information, and future versions could connect with campus data sources if available. Since UIUC already provides menu, nutrition, allergen, hours, and meal plan information through the Illinois app, Rush Radar would build on the idea of centralized dining information while focusing more specifically on crowd and wait-time visibility.

User Input: Students could submit quick crowd updates, such as “not busy,” “moderate,” or “very busy.” To prevent inaccurate data, the app could weigh more recent reports more heavily and show when the last update was submitted.

Design Tools: Figma could be used for wireframing, prototyping, and usability testing before full development.

### Managing Technical Debt
Technical debt is the accumulation of issues resulting from hasty decisions made during development processes. Rush Radar would deal with technical debt through consistent structuring of the program throughout its development stages. Consistent structuring includes maintaining a good naming convention, creating reusable elements in the code, documenting critical decision-making and performing frequent code reviews.
The second aspect of managing technical debt will be to develop the application slowly while ensuring all necessary functionalities have been built. The first phase of development should focus on solving the core issue which involves enabling students to view rush levels at dining halls. Additional functionalities such as comment sections, personalized recommendations or more complex prediction models can be implemented in other iterations of the software.
Testing would also be essential since the application must solve its primary problem of presenting rush levels to the users accurately. Common test scenarios would include slow application speed, out-of-date crowd data, labeling mistakes, and application crashes among others. The information presented by the application is expected to be reliable and comprehensible to students.

### Community Building & Ecosystem Strategy
Rush Radar would be most successful if it became part of the student dining ecosystem rather than just a standalone app. Community building would involve encouraging students to use the app, submit updates, and give feedback. The app could be promoted through residence halls, student organizations, campus social media, and dining-related channels.
To build trust, the app should be transparent about where its information comes from. For example, it should clearly show whether crowd data is based on user reports, historical predictions, or official data. This would help users understand how reliable the information is.
The app could also include feedback features, such as “Was this crowd estimate accurate?” or “Report current wait time.” Over time, this would help improve the quality of the data. A strong community strategy would make students feel like they are not just using the app, but helping improve the dining experience for everyone.

### Sustainability
For Rush Radar to remain useful long term, it would need both technical sustainability and community sustainability. Technically, the app should be built with reusable components, clear documentation, and a manageable feature set. The project should avoid adding too many features too quickly, because that could make the app harder to maintain.
Community sustainability would depend on student participation. Since crowd information may rely on users submitting updates, the app would need to encourage students to contribute without making the process annoying. A simple one-tap update system could make participation easier. The app could also remind users that their updates help other students make better dining decisions.
Rush Radar could also be promoted through residence halls, student organizations, campus social media, and dining-related announcements. If enough students use the app regularly, it could become part of the normal campus dining routine.

### Conclusion
Rush Radar is a mobile app concept designed to solve a real problem in student life: uncertainty around dining hall crowds, wait times, and seating availability. While existing campus tools may provide menus, hours, and meal plan information, Rush Radar focuses on the live dining experience and helps students quickly decide where to eat.
By using open source and agile development methods, the project can remain flexible, collaborative, and responsive to student needs. The app’s success would depend on clear design, reliable data, strong usability, and active student participation. Ultimately, Rush Radar has the potential to make campus dining more efficient, less stressful, and better suited to the daily routines of students.

### Reference

University Housing, University of Illinois Urbana-Champaign. “Dining Locations.”

University Housing, University of Illinois Urbana-Champaign. “Dining Menus.”

Nielsen Norman Group. “10 Usability Heuristics for User Interface Design.”

Nielsen Norman Group. “How to Conduct a Heuristic Evaluation.”

Agile Manifesto. “Manifesto for Agile Software Development.” 

Open Source Guides. “Building Welcoming Communities.”
