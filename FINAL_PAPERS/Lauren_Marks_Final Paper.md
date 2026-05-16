# A Trauma-Informed, Open-Source Pamphlet for Community-Level Domestic Violence Advocacy

**Lauren Marks**  
IS 340 — Final Project  
University of Illinois Urbana-Champaign  

---

## Abstract

Domestic violence remains a pervasive public health crisis in the United States, yet most community-level resources target survivors or trained professionals rather than everyday bystanders. Friends, family members, neighbors, and coworkers are often the first point of contact for those experiencing intimate partner violence. This paper introduces a community-centered open-source project designed to address that gap: a trauma-informed, openly licensed pamphlet equipping non-professional community members with the language and practical guidance needed to support survivors effectively.

The proposed solution applies foundational open-source principles—including transparency, participatory governance, contribution workflows, and version control—to the production of a public health communication artifact. Key course concepts applied include working open, open-source governance, technical debt management, and accessible design. The anticipated impact is a scalable, freely redistributable resource that reduces barriers to informal advocacy and strengthens community-level support networks for survivors.

---

## 1. Introduction

Intimate partner violence (IPV) constitutes one of the most consequential and systematically underaddressed public health challenges in the United States. According to the Centers for Disease Control and Prevention's National Intimate Partner and Sexual Violence Survey (NISVS), more than one in three women have experienced contact sexual violence, physical violence, or stalking by an intimate partner during their lifetime, while more than one in six men—approximately 20.7 million individuals—have experienced the same (Zhang Kudon et al., 2026).

Underreporting remains pervasive, driven by fear of retaliation, economic dependence, social stigma, and the absence of culturally responsive resources (Davies et al., 2025).

Domestic violence response has historically concentrated at two poles: formal institutional systems such as law enforcement, healthcare, and legal advocacy, and direct-service organizations for survivors who have already sought help. Critically underdeveloped is a resource layer for informal community members who occupy the relational space between these systems. Friends, family members, coworkers, neighbors, and faith community members are often the first people a survivor discloses to, yet they frequently lack the knowledge or frameworks to respond effectively and without causing harm.

This paper presents a community-centered open-source project designed to fill that gap. The paper articulates the project vision, defines the target community, states concrete goals, describes the proposed solution and implementation strategy, and examines governance, sustainability, and future pathways.

---

## 2. Project Vision

The overarching vision of this project is a free, openly licensed, trauma-informed pamphlet that any community member, regardless of professional background, can access and use. The pamphlet is not a clinical tool or substitute for professional services; it is a bridge resource: a practical, readable guide that helps everyday people respond with care and connect survivors to further support when appropriate.

Central to this vision is accessible design. The pamphlet will be written in plain language at or below an eighth-grade reading level, formatted for both print and digital use, and designed with high visual contrast and readable typography. Cultural sensitivity is equally foundational. Content will avoid assumptions about family structures, economic status, immigration status, or relationship configurations, recognizing that IPV affects individuals across all demographic groups.

This vision is inseparable from the principles of working openly articulated by the Mozilla Foundation. Working open means that design decisions, editorial choices, governance structures, and content revisions are visible and accessible to all participants (Mozilla Foundation, 2016). Participation is not merely permitted but actively solicited, and ownership is shared. The pamphlet thus becomes a model of the collaborative, community-accountable values it seeks to promote.

---

## 3. Community and Target Audience
The primary audience is deliberately defined as non-professional community members: individuals within survivors' social networks who have received no formal training in domestic violence response, trauma-informed care, or social work practice. This includes friends, family members, neighbors, coworkers, faith community members, and community volunteers. This audience is profoundly underserved. Existing domestic violence materials are directed either at trained service providers or at survivors themselves, leaving community members who wish to help to navigate an overwhelming landscape of content written at a professional reading level or anchored in clinical rather than relational frameworks.
The secondary audience includes domestic violence organizations, public health departments, educators, and community health workers who may distribute or adapt the pamphlet for their constituent populations. Partnering with agencies already embedded in communities most affected by IPV enables the project to reach individuals who would not independently seek out such a resource.
For both audiences, trauma-informed care principles are essential. As Ross et al. (2026) establish, the six foundational principles—safety, trustworthiness and transparency, peer support, collaboration and mutuality, empowerment and voice, and attention to cultural and historical context—produce measurable improvements in engagement and recovery outcomes.

---

## 4. Purpose and Goals
The project is organized around five concrete, interrelated goals. First, the project will produce a freely available pamphlet distributed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license, which permits any individual or organization to reproduce, adapt, and redistribute the resource provided attribution is maintained, a direct instantiation of open-source licensing principles (Creative Commons, 2013).
Second, the project will ensure comprehensive accessibility: plain language at or below an eighth-grade reading level, multilingual availability in priority languages, compliance with Web Content Accessibility Guidelines (WCAG) for the digital version, and a print-optimized format that functions without color coding. Accessibility is treated as a design prerequisite, consistent with the Universal Design for Learning framework developed by CAST (2024).
Third, all content will be grounded in evidence-based, trauma-informed principles. Every editorial choice will be evaluated against the eight-theme framework for trauma-and-violence-informed care identified by Davies et al. (2025), including survivor-centered care, cultural safety, and non-judgmental relational support.
Fourth, the project will establish a transparent, community-governed GitHub repository complete with a project charter, a CONTRIBUTING.md, a CODE_OF_CONDUCT.md, and a public roadmap, ensuring that governance is legible, participation is structured, and accountability is maintained across all contributors.
Fifth, the project will build a sustainable contribution model that proactively manages technical debt through automated accessibility checks, a biannual content review cycle, and a living debt register so that the resource does not decay into inaccuracy over time.

---

## 5. Proposed Solution
The proposed solution is a single-fold or tri-fold pamphlet available in two primary formats: a professionally typeset print-ready PDF and an accessible digital PDF optimized for screen readers. The print format is reproducible on standard 8.5-by-11-inch paper using any consumer-grade printer, ensuring cost-free distribution. The digital version will conform to PDF/UA standards, including tagged document structure, alternative text for all visual elements, and logical reading order.
Content will be written in plain language, organized around four practical questions community members are most likely to ask: How do I recognize signs of domestic violence? What should I say, and what should I avoid? How do I support someone not yet ready to leave? Where can I find immediate resources? 
All language will be reviewed for victim-blaming framing and replaced with survivor-centered, agency-affirming alternatives. Phrases that imply fault, minimize the complexity of leaving, or prioritize the advocate's comfort over the survivor's safety will be systematically removed, consistent with the survivor-centered care principle identified as foundational by both Davies et al. (2025) and Ross et al. (2026).
The project will be hosted as an open-source repository on GitHub and released under a Creative Commons CC BY 4.0 license, enabling any individual, organization, or government agency to reproduce and adapt the pamphlet without seeking permission, provided they attribute the source and release derivatives under compatible terms.

---

## 6. Implementation Strategy

### 6.1 Define

The definition phase formally establishes the project's scope, goals, and governance structures through a structured needs assessment drawing on two parallel streams: a systematic review of domestic violence advocacy literature and a stakeholder consultation process engaging IPV survivors, community health workers, faith leaders, and DV organization staff. This dual approach grounds the project in both empirical evidence and lived experience.

The project team will then draft and publish core governance documents: a project charter articulating mission, scope, and success metrics; a `CONTRIBUTING.md` specifying how community members may submit issues and propose content changes; and a `CODE_OF_CONDUCT.md` adapted from the Contributor Covenant standard. These documents constitute the project's participatory framework and map directly to the open-source initiation lifecycle.

### 6.2 Design

The design phase translates project goals into concrete content and visual architecture. Designers develop wireframes for each pamphlet panel, mapping the information architecture against the four primary user questions identified during definition. Decisions about visual hierarchy, white space, font size, and contrast ratios reference Universal Design for Learning principles, particularly the perception and language clarity guidelines in CAST's UDL Guidelines version 3.0 (CAST, 2024).

Community feedback is incorporated through a structured public comment period: wireframes and content outlines are posted as GitHub issues with an explicit invitation for review, and a minimum two-week comment period is observed before any design decision is finalized. This operationalizes the working open principle of participatory design. All feedback is documented in the repository's issue tracker, creating a transparent record of how community input shaped the final design.

### 6.3 Development

The development phase is conducted entirely through GitHub's version control infrastructure. Contributors submit content via pull requests against the repository's development branch. Each pull request is reviewed by at least two maintainers before merging, and no content may be promoted to the stable main branch without completing a full review cycle.

This branching workflow is a standard open-source practice that translates effectively to content production. It ensures the publicly available pamphlet always reflects reviewed content while allowing revision without disrupting distribution. Every change is logged in Git's commit history and is permanently attributable and reversible.

The workflow is intentionally designed to welcome a diverse contributor base. Individuals without coding experience contribute through GitHub's issue tracker and in-browser editing interface. Writers, designers, translators, and accessibility reviewers are each recognized as valued contributors, with governance documentation specifying accessible pathways for each participation type.

### 6.4 Production

The production phase finalizes the pamphlet in all distribution-ready formats: a print-optimized PDF, a screen-reader-accessible PDF conforming to PDF/UA standards, a responsive HTML web version hosted on GitHub Pages, and a plain-text version for low-bandwidth environments.

The project team tags a versioned release using semantic versioning: version `1.0.0` represents the first stable public release, with subsequent translations and content updates tagged as minor or patch releases. The full production workflow—file naming conventions, format generation scripts, and release procedures—is documented in the repository's wiki so that future maintainers can execute the process without relying on institutional memory from original contributors.

---

## 7. Technical Stack

The technical infrastructure has been selected according to three criteria: accessibility, cost, and long-term sustainability. Every tool in the stack is either free and open-source or available at no cost to nonprofit and academic users, minimizing barriers to participation and preventing financial dependency on proprietary software.

GitHub serves as the central platform for version control, issue tracking, and community governance, providing the pull request workflow, branching model, and issue tracker that underpin the contribution model. GitHub Pages provides free hosting for the HTML web version (GitHub, 2023).

Markdown is the primary content authoring format because it is human-readable in raw form, renders cleanly as HTML, and requires no specialized software, enabling contributors without design experience to author and review content using any text editor.

GitHub Actions provides continuous integration and deployment (CI/CD) infrastructure. Automated workflows run on every pull request to perform reading-level analysis using the Flesch-Kincaid algorithm, link validation, and contrast ratio verification before human review begins, ensuring accessibility standards are enforced consistently.

The Creative Commons CC BY 4.0 license governs all distribution and adaptation, chosen because it maximizes reach: any organization, regardless of size, jurisdiction, or commercial status, may reproduce and adapt the pamphlet without seeking permission or paying fees (Creative Commons, 2013).

---

## 8. Governance and Community Model

The project adopts a BDFL-lite governance model: the project founder retains final editorial authority over content deemed inconsistent with trauma-informed principles or posing a risk of harm to survivors, but exercises this authority within a transparent framework of community deliberation. A small steering committee provides collective oversight of major directional decisions, including changes to scope, licensing, or governance structure.

Contribution pathways are structured in three tiers. Any member of the public may submit issues or propose changes via pull requests without prior approval. Contributors who demonstrate consistent quality, adherence to the code of conduct, and alignment with project values are invited to become trusted maintainers, with authority to review and merge others' pull requests. Maintainers who demonstrate sustained expertise may join the steering committee. This meritocratic escalation model is directly informed by Mozilla's Working Open principles, which hold that authority should be distributed through contribution rather than appointment (Mozilla Foundation, 2016).

The `CODE_OF_CONDUCT.md`, adapted from the Contributor Covenant (version 2.1), establishes behavioral expectations including respectful communication, confidentiality of sensitive disclosures, and a clear enforcement process for violations. The `CONTRIBUTING.md` specifies how to submit issues, write effective pull requests, participate in design review periods, and propose translations. Together, these documents constitute the project's social contract.

---

## 9. Technical Debt and Sustainability

In this project's context, technical debt refers broadly to any deferred obligation that, left unaddressed, degrades the quality, accuracy, or accessibility of the resource. Specific forms include outdated citations and statistics, language that conflicts with evolving trauma-informed best practices, accessibility features omitted in early versions that are costly to retrofit, and documentation gaps that prevent new contributors from understanding the project's history and conventions.

The project manages debt through proactive and reactive strategies. Proactively, contributors are required to include inline documentation, including brief source file comments noting the source, date, and rationale for editorial decisions. A biannual review cycle, scheduled each January and July, tasks the steering committee with auditing citations for currency, language for alignment with best practices, and accessibility features for WCAG compliance.

Reactively, a debt register implemented as a GitHub project board publicly logs, prioritizes, and assigns known content gaps, outdated references, and unresolved accessibility issues. This visibility ensures technical debt is treated as a managed backlog rather than an ignored liability.

---

## 10. Future Pathways

The open governance model enables community-driven expansion without depending on the original project founder. Multilingual translation is the most immediate priority: Spanish, Mandarin, Somali, and Arabic have been identified as the first four target languages, based on populations most affected by IPV who face significant barriers to English-language resource access.

An interactive web version incorporating embedded hotlines, resource locators, and guided decision trees has been scoped as a longer-term goal. The open repository structure allows any contributor with relevant skills to begin work on these extensions at any point, provided the contribution aligns with the project charter and `CODE_OF_CONDUCT.md`.

---

## 11. Conclusion

This paper has presented the design, rationale, and implementation strategy for an open-source, trauma-informed pamphlet project aimed at empowering everyday community members to support survivors of domestic violence. Grounded in rigorous open-source governance, proactive technical debt management, accessible design, and community-centered contribution workflows, the project is structured not only to be launched but to be sustained and extended by the communities it serves.

The scale of intimate partner violence demands a response operating at every level of the social ecosystem, including the informal relational networks survivors inhabit long before they access formal services. This project contributes to that layered response: a freely available, community-built, survivor-centered resource designed to make advocacy accessible to all.

---

## 12. References

- CAST. (2024). *Universal Design for Learning guidelines version 3.0* [Graphic organizer]. CAST. https://udlguidelines.cast.org

- Creative Commons. (2013). *Attribution 4.0 International (CC BY 4.0).* Creative Commons. https://creativecommons.org/licenses/by/4.0/

- Contributor Covenant. (2020). *A code of conduct for open source communities, version 2.1.* Contributor Covenant. https://www.contributor-covenant.org/version/2/1/code_of_conduct/

- Davies, M., Satyen, L., & Toumbourou, J. W. (2025). *Trauma-and-violence-informed care for victim-survivors of domestic, family and sexual violence: A qualitative meta-synthesis of service providers' perspectives.* Trauma, Violence, & Abuse. https://doi.org/10.1177/15248380251383933

- GitHub. (2023). *GitHub Pages documentation.* GitHub Docs. https://docs.github.com/en/pages

- Mozilla Foundation. (2016). *Working open: A guide to working open at Mozilla.* Mozilla Foundation. https://mozilla.github.io/open-leadership-training-series/

- Open Source Initiative. (2007). *The open source definition (annotated), version 1.9.* Open Source Initiative. https://opensource.org/osd

- Ross, N., Doria, N., McNaughton, C., & Bagg, L. (2026). *How survivors of intimate partner violence experience trauma-informed care: A scoping review.* PLOS ONE, 21(4), e0334623. https://doi.org/10.1371/journal.pone.0334623

- Wathen, C. N., Schmitt, B., & MacGregor, J. C. D. (2022). *Measuring trauma- (and violence-) informed care: A scoping review.* Trauma, Violence, & Abuse, 24(1), 261–277. https://doi.org/10.1177/15248380211029399

- Zhang Kudon, H., Zhu, S., Chen, B., Breiding, M. J., Leemis, R. W., Zhang, X., Schwank, A., & Basile, K. C. (2026). *The National Intimate Partner and Sexual Violence Survey (NISVS): 2023/2024 intimate partner violence data brief.* National Center for Injury Prevention and Control, Centers for Disease Control and Prevention. https://www.cdc.gov/nisvs
