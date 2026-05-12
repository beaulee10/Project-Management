IlliniCare: A Centralized Wellness Hub for Academic Success
Beau Lee, Spring 2026
Abstract
In the modern realm of higher education, student burnout continues to be an increasingly complex "wicked problem." An example of such an institution that is known for being a difficult environment is the University of Illinois at Urbana-Champaign (UIUC). IlliniCare is an innovative centralized wellness hub that aims to address one area of the student burnout issue called the "Forsaken Factor," which describes the intersection of bureaucratic "red tape," multiple resources being fragmented across campus, and the large cognitive load on a student during difficult times in their life, when he/she/they will often reach their breaking point with poor mental health and existence.  By taking advantage of artificial intelligence-based support in combination with habit loop-driven design, IlliniCare provides conversational triage 24 hours per day, seven days per week and allows students to have access to campus services such as the Counseling Center and McKinley Health Center through a streamlined process.
In order to build IlliniCare such that it has the greatest functional benefit while using an Integrative Project Management view, it was developed using an Agile Sprints process and a Minimum Viable Community (MVC) approach. This report provides analysis of 2500 words that includes details that are related to the functional utility of IlliniCare as measured by the current Simplicity Cycle, methods used to address the "Policy Knot" associated with the university's regulations, and proposed methods to implement a long-term sustainable stewardship model. Additionally, information obtained from the IS-340 curriculum and associated theoretical frameworks will support the development of IlliniCare through each stage of its lifecycle and also will lead toward a roadmap for its long-term sustainability.
1. Project Motivation: Addressing the "Forsaken Factor"
IlliniCare is the result of the insight that many students at UIUC will struggle to access available mental health resources because they are presented with many different ways to find help - through websites, phone numbers, and referral systems - which is non-linear, fragmented, and overwhelming. In addition to academic and social pressures, this situation allows for the marking of a "Forsaken Factor", or a state whereby the administrative barrier prevents students from seeking help.
Once a student has navigated through the many different ways to find help, that student will most likely be in crisis - meaning their academic and personal lives are compromised.

IlliniCare seeks to change this by creating a stigma- and friction-free way of promoting balanced living and a shift from a reactive, crisis response style of mental wellness to proactive, manageable daily practices. By consolidating the many different mental health services available through one centralized internet interface, the project will eliminate the feeling of a student as being "forsaken" by the system designed to support them.
1.1 The Problem of Burnout as a "Wicked Problem"
Wicked problems have no definitive solutions, are complex and involve different stakeholders with different opinions (Rittle and Webber 1973). Student Burnout is a prime example of a wicked problem for multiple reasons:
No Stopping Rule. Burnout is not looked at as something you can can be 'solved'; it is a multi-year process that requires continuous management.
Unique Circumstances. Each student has a unique experience with stress with different influences (major, financial stability, social support).  
Higher Order Consequences. Resolving one facet of burnout might create other facets (i.e. adding more academic advisers might create longer wait times or resultant budget cutbacks).
IlliniCare cannot resolve Burnout alone; it is part of a larger network of resources that are meant to provide support to students. IlliniCare’s frame of reference for the Burnout wicked problem allowed us to move beyond a search for a “perfect” solution and to focus on an “awkward” approach for providing immediate, tangible value.  
Reference Link: Rittel and Webber's Wicked Problems
2. The Community and Stakeholder Landscape
The success of any project relies on the community associated with it. IlliniCare defines its primary community to be UIUC students balancing their education, employment and socialization. Through IS-340, I learned that projects without an identified community do not have an associated purpose.
2.1 Minimum Viable Community (MVC)
As outlined in the concepts explored in Lecture 11, we do not plan for our project to serve the entire University population on Day 1, but rather create a “Minimum Viable Community” (MVC), meaning the smallest (but not simply bare bones) group of individuals (actual real-life people) that support the programs (or activities) such that they receive value from being a part of those programs (or activities).
In IlliniCare, the MVC includes:
Pilot Group: 50+ students from a variety of areas (Informatics, Engineering, Liberal Arts) that will be “lead users” of the program(s).
Contributors (Makers): Students and Faculty (and/or Teachers) interested in wellness technology that maintain the resource database of tools provided to students as a result of this project.
Stakeholders: Staff from Counseling Services and McKinley who will provide the “back end” for referrals via the app.
By having a very limited number of users, we will minimize the risk of “stretching resources too thin.” This helps to provide valuable insights into what students truly have a need for; rather than what we “think” they require before we expand to the larger campus community and other Big Ten institutions.
Reference Link: Defining a Minimum Viable Community
3. Project Concept and Workflow
Three main pillars of functionality are at the heart of IlliniCare, combining to benefit the student lifecycle:
Centralized Hub: A single point of entry for the Counseling Center, McKinley, and peer support reduces the effort it requires for students to connect with help.
AI Support: 24/7 conversational interface that enables students to connect with pre-arranged resources by providing support for triage and providing habit-tracking; fills in the 24/7 gaps created by the lack of student resources after hours.
Wellness Dashboard: A project-management interface that considers wellness to be an integral aspect of academic performance through "Habit Loop" psychology.
3.1 The Habit Loop Design
Each application utilizes a three-stage process to promote student resilience:
Daily check-in: a quick and simple way for students to track their daily levels of mood, energy, and stress.
AI Triage: a virtual assistant that utilizes the principles identified in Lecture 22 about AI to provide support through logging and enabling students to access immediate support through the use of AI triaging.
Action Step: An option that will link the user to 1-click consultations and/or campus resources, thereby moving the user from "I feel..." to "I'm going to do..." with no bureaucracy between them.
4. Methodology: Agile, Sprints, and MVP
The IlliniCare platform was created using an Agile Methodology. As reported in Lecture 12, an Agile approach is a direct contrast to the rigid/codified Waterfall methodology. Specifically, in mental health situations where there is a constantly changing need and sentiment from student populations, using a Waterfall methodology that spends months creating paperwork and documentation before beginning to build would yield an obsolete product by the time it launched.
4.1 Sprint Cycles and "Demo or Die"
We implemented Agile methodology by managing the IlliniCare project through weekly Agile Sprints following the structure presented in Lecture 13 and Lecture 14. Each week contained:
Sprint Planning: Defining why the sprint was of value (i.e., "designing the logic for the AI triage");
Implementation: Creating rapid prototyping using No Code tools such as Glide or Betty Blocks;
Sprint Review: A "Demo or Die" meeting for peers to view working prototypes and provide feedback
Sprint Retrospective: Documenting what did not work well (e.g., "the response provided by AI was too clinical") and what should be changed for the next cycle.
4.2 Failure Modes of the Sprint Model
As indicated in Lecture 13, the Sprint model presents risks that must be accounted for. We determined and created measures to counteract two high-impact failure modes:
Single Point of Failure - When a backlog owner is absent, no further progress can be made on a sprint. To reduce the risk of this occurring, we utilize a shared GitHub Discussion board for tracking issues.
Vision Vagueness - When project vision (the "why") is unclear, teams will create components based on one-off needs (or just-in-time) and that results in lack of alignment on direction. We avoided a vagueness issue by using a strict MVP lens to evaluate feature creation: Will the feature reduce student friction? If it won't help reduce student friction, we moved it into the Icebox.
Reference Link: The Agile Manifesto
4.3 Managing the Maker-Taker Problem
One of the biggest challenges we had to address related to project management was the Maker-Taker Problem (Lecture 19). In the context of IlliniCare, the "makers" are developers and healthcare professionals and the "takers" are students. If maker's burden (e.g., updating counseling hours manually) is too high, there is significant "churn" to the project, and it will fail. To mitigate risk to the sustainability of the project, we focused on reducing maker's burden through automated processes such as web scraping to maintain real-time updated resource hour availability without any human interaction.
5. Theoretical Frameworks and Course Application
5.1 The Simplicity Cycle (Ward, 2005)
The Simplicity Cycle, introduced in Lecture 20, is a major theme of IS-340. The Simplicity Cycle states that as the idea evolves, more detail is created; this is a positive, increasing utility. Eventually the number of details may cause the utility to cease to increase; this will happen when there is too much detail and it becomes complex and stops providing utility.
The Simplicity Cycle will guide our innovation in developing the IlliniCare application:
1. The first phase of this innovation was to create a complete medical record system, the second phase was to design a "Wellness Hub" application that provides more functionality for consumers than our first idea.
2. In the third phase of our innovation, we need to be very careful to not add complexity with features such as social media integration, gaming, and/or complex scheduling. Our aim is to maintain a clean, user-friendly interface and produce succinct responses to users based upon the AI application output (stay within the Utility Zone).
Reference Link: The Simplicity Cycle Whitepaper
5.2 The Policy Knot and Risk Management
Developing a mental health application at a public university requires navigating a complicated Policy Knot (Lecture 21). The Policy Knot illustrates the relationship among government policies (such as HIPAA), regulations imposed by the university, and how the technology will function.
Regulatory/Innovative Connection: Exploratory (AI triage) and regulatory (Privacy) processes can often conflict. IlliniCare's solution is to classify all of its wellness logs as Extremely Sensitive Information, and to apply end-to-end encryption to all information from the start of the process.
Designing Proactively: Rather than waiting for a "failure point" in the association of law and design, we designed with the regulations in mind. We consulted with campus health representatives early on to ensure that we would not cross over into "unlicensed medical advice" in our "conversational triage" interface.
Reference Link: The Policy Knot: Re-Integrating Policy and Design
5.3 Ironies of Automation
"You cannot automate a process that is broken." This principle—discussed in Lecture 22 by Lisanne Bainbridge, "The Ironies of Automation"—implies that the more efficient an automated process, the more dependent it is on human beings. It follows that if our AI triage is optimised to save "human work" (a goal of our design), it will not be able to replace human counselling and will not be able to function properly. The irony would be if students who use the AI (which is expected to be superior) ceased to seek out professional, human-based assistance. Our strategies for mitigating this effect are:
Lesser Awareness Mitigation Strategy: Students need to be aware they are engaged with an AI in order to keep them "connected" to their own mental health status.
Hand-off Protocols:  When students' stress levels reach a certain point, the AI explicitly exits the system and connects them to a human-to-human resource.
Reference Link: Lisanne Bainbridge: Ironies of Automation
6. Technical Implementation: No-Code and AI Transformation
From reference 12, the stewardship model emphasizes the ongoing care of projects by individuals who continue to be active members of the community after graduation, increasing the likelihood that these projects will continue beyond the original founders' involvement.
6.1 Why No-Code?
The success of projects similar to IlliniCare depends on increased speed. The use of no-code tools, such as Glide or Betty Blocks, allowed us to:
Bridge communication gaps by displaying a working prototype within days, instead of months, to the Counseling Center.
Break down structural barriers by enabling an individual, regardless of their education level, to contribute towards the development of the wellness hub, thus creating a more diverse “maker” pool.
Reduce classic maintenance by using existing software platforms, eliminating the "technical debt" associated with maintaining proprietary server-based software.
6.2 AI Transformation in PM
Based on the insights gained in Lecture 22, by 2030, the nature of project management will shift from administration and control of stakeholders, to providing guidance to stakeholders on how best to achieve project objectives. IlliniCare has exemplified this shift. In traditional models, the student who utilizes the resources of the Wellness Center has no direct responsibility for the success of his or her project. In this model, IlliniCare provides students who are utilizing the Wellness Center with a virtual assistant who will provide them with the needed assistance and support to complete their projects successfully.
Reference Link: How AI Will Transform Project Management (HBR)
7. Sustainability and Future Work
7.1 Stewardship vs. Ownership
We are currently collecting and preparing "wellness data," which will enable future versions of AI-based systems to help predict student burnout earlier in the semester. These AI systems will enable student-led wellness projects to continue beyond the initial student-led phase and will not depend on the founders' involvement.
There is a process for including new features into the IlliniCare project where students can help shape this app in the community comment period.
To avoid IlliniCare becoming bloated as an app, we have established EOL strategies for obsolete features.
Reference Link: Red Hat: Open Source Software Life Cycle
7.2 Open-Source Maturity
We will use Product Integration (PI) to transition IlliniCare from being a standalone application to being part of the Illinois App throughout all levels of maturity (Basic, Advanced, etc.) for continued support there.
8. Conclusion
IlliniCare is a project management intervention to address the dementia that university students are experiencing. Using the Simplicity Cycle and Agile Development, we have defined a workable product that integrates with other applications (not just IlliniCare) through electronic data exchange.
The failure to integrate all systems and have enough resources contributed to the "Forsaken Factor." IlliniCare resolves this issue by making the student the focal point of their design and creating a process whereby wellness becomes an inherent practice rather than an obligation through the use of smart and readily accessed automated solutions. By means of a long-term commitment to being good stewards and continuing improvement, IlliniCare will change the way that students experience mental health services at the University of Illinois and create a model for how all students are successful within the Big 10 Conference and elsewhere.
9. References
Alicea, B. (2024). IS-340: Integrative Project Management Lectures 11-22. University of Illinois at Urbana-Champaign.
Ambler, S. (2022). Lean Documentation. Agile Modeling. http://agilemodeling.com/essays/agileDocumentation.htm
Bainbridge, L. (1983). Ironies of Automation. Automatica, 19(6), 775-779. https://www.sciencedirect.com/science/article/abs/pii/0005109883900468
Beck, K., et al. (2001). Manifesto for Agile Software Development. https://agilemanifesto.org/
Harvard Business Review. (2023). How AI Will Transform Project Management. https://hbr.org/2023/02/how-ai-will-transform-project-management
Jackson, S. J., Gillespie, T., & Payette, S. (2014). The Policy Knot: Re-Integrating Policy, Practice and Design. ACM CSCW. https://dl.acm.org/doi/10.1145/2531602.2531721
Magwaza, P. (2022). What is a Minimum Viable Community? Commsor. https://www.commsor.com/post/minimum-viable-community
Red Hat. (2021). Understanding the Open Source Software Life Cycle. https://www.redhat.com/en/resources/open-source-software-life-cycle-brief
Ward, D. (2014). The Simplicity Cycle: A Field Guide to Making Things Better Without Making Them Worse. HarperBusiness. https://www.danward.net/simplicity-cycle
