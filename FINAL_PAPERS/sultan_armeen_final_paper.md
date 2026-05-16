PathFinder: An Open-Source Career and Internship Development Platform
Armeen Sultan, Spring 2026

## Introduction

As a student who has gone through the internship recruiting process
firsthand, I know exactly how disorganized it can get. During my own
search, I was juggling over thirty applications spread across
spreadsheets, sticky notes, my phone\'s Notes app, and a handful of
random Google Docs that I kept meaning to consolidate but never did. At
one point, I missed a deadline for a role I genuinely wanted, not
because I was unqualified or uninterested, but simply because I lost
track of it in the chaos. That experience stuck with me, and it is what
eventually led me to this project.

The problem I experienced is not unique. Nearly every student going
through recruiting faces the same fragmented reality: no central place
to track applications, no structured resource for interview preparation,
and no visibility into data that could actually inform their job search
strategy. The tools that exist are either expensive, built for employers
rather than students, or both. There is a clear gap between what
students need and what is freely available to them.

PathFinder is my proposed solution. It is a free, open-source platform
designed to centralize the entire career development journey for
students, from the first application to the final offer. Built around
the principles of transparency, collaboration, and sustainability that
define the open-source movement, PathFinder aims to give students the
tools they need while also creating a community of contributors who can
continuously improve the platform over time.

This paper walks through the vision and goals of PathFinder, the
open-source and working open principles that shape how I would manage
it, the community and contribution model that makes it sustainable, the
role of automation in the platform, the project roadmap and lifecycle,
and the challenges and risks that any honest project plan must account
for.

## Vision Statement

PathFinder is a student-centered, open-source platform that centralizes
application tracking, interview preparation, resume feedback, recruiting
analytics, and mentor matching in one freely accessible system. The
platform is built by students, for students, and governed by the
community that uses it.

The long-term vision is for PathFinder to become the go-to career
development resource for students at any university, regardless of their
school\'s resources or their ability to pay for premium tools. The
short-term goal is more focused: build a minimum viable product that
solves the core tracking and preparation problems, put it in front of
real users, and let genuine feedback shape what it becomes.

## Project Overview

PathFinder addresses three interconnected problems that students face
during the job search process. First, there is no central system.
Students rely on a patchwork of personal tools, none of which are
designed for the scale and complexity of a full recruiting cycle.
Second, interview preparation is entirely unstructured. Students rely on
paid platforms, borrowed notes, or informal advice with no
community-driven alternative. Third, there is no data visibility.
Students make decisions about where to apply, when to apply, and how to
prioritize their time with no information about what actually works.

The platform\'s core features are designed to address each of these gaps
directly. The application tracker allows students to log job postings,
deadlines, application status, and follow-up notes in one place. The
AI-powered interview preparation tool draws on a community-built
question bank to generate practice questions tailored to specific roles
and companies. The resume feedback system combines peer review with
automated analysis. The analytics dashboard surfaces trends in hiring
timelines, response rates, and role competitiveness so students can make
more informed decisions. And the mentor matching feature connects
students with alumni and professionals in their target fields.

What ties all of these features together is the open-source model. Every
component of the platform is publicly visible, every contributor is
welcome, and nothing is ever locked behind a subscription. PathFinder is
not a product built for profit. It is infrastructure built for students.

## Why Open Source

The decision to build PathFinder as an open-source project is not
incidental. It is foundational to everything the platform is trying to
accomplish.

The first reason is transparency. Career development tools handle
sensitive information: job application history, resume content,
performance data, salary expectations. Students have every right to know
exactly how that information is stored, processed, and used. In a
closed, proprietary system, users have to take the company at its word.
In an open-source system, every line of code is publicly visible and
auditable. There is no need to trust a company\'s privacy policy when
you can read the actual implementation. For a platform handling the kind
of information PathFinder handles, this level of transparency is not
optional. It is essential.

The second reason is collaboration. A single team, no matter how
talented, will always have a narrower view of user needs than a
community of contributors with diverse backgrounds and experiences. A
student who struggled with a specific part of the recruiting process
knows something about that problem that no developer working in
isolation ever could. A career coach who reviews hundreds of resumes a
year knows what automated feedback tools miss. An alum who successfully
navigated a particular industry knows what kinds of interview questions
actually matter. Open source creates a system where all of that
knowledge can flow into the platform continuously, rather than being
filtered through the assumptions of a small product team.

The third reason is sustainability. Proprietary career tools get
acquired, pivoted, or shut down. They raise prices, restrict features,
or disappear entirely. Because PathFinder is community-owned, none of
those outcomes are possible. The platform belongs to the people who use
and contribute to it, and no company can take it away. This is what it
means to build infrastructure rather than a product.

## Open Source and Working Open Principles

### Working Open

Working open means making the process of building something as visible
as the thing being built. For PathFinder, this means every decision,
every discussion, every tradeoff is documented and accessible on GitHub.
The roadmap is public. The issue tracker is public. The pull request
history is public. Anyone who wants to understand why a feature was
built a certain way, or why a feature was not built at all, can find
that answer without asking anyone. This level of transparency is what
distinguishes a truly open project from one that is simply open-source
in name only (Cotton, 2023).

Working open also means actively inviting participation, not just
permitting it. PathFinder is designed so that students, developers,
career coaches, and researchers can all contribute in ways that match
their skills. A student who has no programming experience can still
contribute by submitting feedback, reporting issues, or adding interview
questions to the community question bank. A developer can contribute by
fixing bugs or building new features. A career coach can contribute
domain expertise. This is what makes working open genuinely different
from traditional closed development.

### Dynamic Division of Labor

One of the most powerful aspects of open-source development is what can
be described as a dynamic division of labor: contributors self-select
into the tasks that match their skills and interests, rather than being
assigned work by a manager (Alicea, 2026). This model produces better
outcomes than top-down task assignment because it harnesses genuine
motivation. A developer who chooses to work on a feature they find
interesting will outperform a developer who was told to work on it.

PathFinder is designed around this principle. The GitHub issue tracker
uses clear labels to distinguish between different types of work: bugs,
feature requests, documentation, interview question contributions, and
good first issues for new contributors. This structure allows
contributors to quickly find work that matches their skills and
availability. It also creates a natural pipeline for new contributors to
ramp up over time, starting with smaller tasks and gradually taking on
more responsibility as they become more familiar with the project.

### Technical Debt Management

Technical debt is the implied cost of choosing an easier, faster
solution now instead of a better, more robust one (Watt, 2014). Every
software project accumulates some technical debt, and PathFinder is no
exception. In the interest of shipping an MVP quickly, several
intentional technical debt decisions have been made: the availability
system will launch as a manually updated interface rather than a fully
automated real-time system, and the analytics dashboard will begin with
a limited set of pre-defined reports rather than a fully customizable
query interface.

These are deliberate tradeoffs, not oversights. The key is to make them
visible and manage them actively rather than letting them accumulate
silently. PathFinder will use a dedicated section of the GitHub project
board to track known technical debt, with clear descriptions of what
each item would require to resolve. This keeps debt visible to
contributors and ensures that it is addressed systematically over time
rather than discovered suddenly when it becomes critical (Alicea, 2026).

## Community and Contribution Model

A platform is only as good as the community that builds and maintains
it. PathFinder\'s community model is designed to be genuinely inclusive,
meaning it creates real pathways for people with different skills and
levels of experience to contribute meaningfully.

There are four primary contributor roles. Developers build and maintain
the platform\'s technical components, fix bugs, and review pull
requests. Students are both the primary users and active contributors
through feedback, issue reports, and additions to the community question
bank. Career coaches contribute domain expertise in the form of
interview preparation content and resume review guidelines. Community
leads manage onboarding, host events, moderate discussions, and help new
contributors find their footing.

The contribution workflow for code follows the standard open-source
pattern: a contributor identifies an issue or proposes a feature, forks
the repository, makes their changes, opens a pull request, goes through
code review, and merges upon approval. This process keeps quality high
while remaining accessible. Every pull request template includes a
checklist that helps new contributors understand what is expected before
their changes are reviewed.

New contributors are directed to issues labeled good first issue, which
are specifically scoped to be completable by someone unfamiliar with the
codebase. This label is not just a gesture. It represents a genuine
commitment to keeping the barrier to contribution low, which is one of
the most important factors in whether an open-source project grows or
stagnates.

Community health is maintained through a code of conduct, transparent
governance, and active recognition of contributions. Contributors whose
work is merged are acknowledged in release notes. Community leads who go
above and beyond are recognized publicly. This recognition is not just
gratitude. It is a signal to the broader community that contribution is
valued and that the project is genuinely managed by people who care
about the contributors, not just the code.

## Role of Automation

Automation plays a dual role in PathFinder: it is both a core feature of
the product and a tool for managing the development process itself.
Understanding where automation adds genuine value and where it creates
new problems is one of the more nuanced challenges in managing a project
like this (Alicea, 2026).

At the product level, automation is what makes PathFinder efficient at
scale. Automated deadline reminders ensure that students never miss an
application cutoff because they forgot to check. AI-powered resume
feedback provides instant, actionable suggestions without requiring a
human reviewer for every submission. Interview question generation draws
on job descriptions to surface relevant practice questions
automatically. The analytics dashboard aggregates data from across the
platform to surface trends without requiring manual analysis. These are
all places where automation handles repetitive, standardized tasks that
do not require human judgment.

At the project management level, automation tools like GitHub Actions
run automated tests on every pull request, catching errors before they
are merged into the main codebase. Issue labeling bots help triage
incoming bug reports and feature requests so that maintainers are not
spending time on administrative tasks. Automated release notes compile a
changelog from merged pull requests, making the release process faster
and more consistent.

However, automation also introduces real risks that need to be managed
honestly. The most serious is AI bias in the resume feedback and scoring
systems. If the underlying models are trained on data that reflects
existing inequities in hiring, they will reproduce those inequities in
their recommendations, potentially disadvantaging students from
underrepresented backgrounds without anyone realizing it. This is not a
hypothetical concern. It is a documented problem with AI hiring tools
that PathFinder must take seriously from the beginning.

Over-automation is another genuine risk. A platform that automates too
much of the feedback and mentorship process risks becoming cold and
impersonal, which would undermine the community dimension that makes
PathFinder different from a simple tracking tool. The goal is to use
automation to handle the repetitive and standardized, while preserving
human judgment for the things that actually require it: code reviews,
community disputes, mentorship, and any decision with meaningful
consequences for a specific person.

The approach PathFinder takes is what might be called a golden mean:
automate where it genuinely reduces friction and improves outcomes, but
default to human oversight for anything that requires context, nuance,
or consequential judgment (Alicea, 2026).

## Project Roadmap and Lifecycle

PathFinder\'s development is organized into five phases, each building
on the previous one and shaped by what is learned in the process.

Phase one is research and definition. This phase involves talking to
real students about their recruiting experiences, scoping the
platform\'s initial feature set, writing the community charter that
establishes governance and contribution expectations, and setting up the
foundational infrastructure: the GitHub repository, issue tracker,
documentation, and contribution guidelines.

Phase two is design and prototyping. This phase produces UI mockups,
database schema, and core architecture decisions. The goal is to make
enough decisions to begin building without over-designing a system whose
requirements are not yet fully understood.

Phase three is alpha development. This is where the core features are
built: the application tracker, the resume feedback tool, and the
community question bank. CI/CD pipelines are set up so that new
contributions can be reviewed and deployed reliably. The platform is
made available to a small group of early users for initial feedback.

Phase four is the public beta. The platform opens to a broader user base
and the contributor community begins to grow. Real user feedback shapes
the priorities for the next phase. Issues that seemed important during
design may turn out not to matter much. Issues that were not anticipated
may turn out to be critical.

Phase five is production and scale. This phase introduces the analytics
dashboard, AI-powered interview preparation, and mentor matching. It
also involves the organizational work of growing the contributor
community, establishing a sustainability funding model, and beginning to
think about what PathFinder looks like at a multi-university scale.

The iterative structure of this roadmap is intentional. As the course
has emphasized through its discussion of Agile methodology and project
lifecycle management, the most effective development processes are the
ones that embrace change rather than trying to plan around it (Alicea,
2026). Each phase of PathFinder\'s development is designed to produce
real learning that shapes the next phase, not just to execute a plan
that was finalized before any real users had seen the product.

## Sustainability and Challenges

Sustainability is where many open-source projects fail. The initial
excitement of a new project attracts early contributors, but maintaining
momentum over the long term requires deliberate, ongoing effort.
PathFinder\'s sustainability strategy addresses this at three levels:
technical, community, and financial.

At the technical level, sustainability means staying ahead of technical
debt before it accumulates to the point where the codebase becomes
difficult to maintain. Regular triage of the technical debt backlog,
consistent code review standards, and clear documentation requirements
for every contribution are the primary tools for this. Without this
discipline, even a well-built MVP can become effectively unmaintainable
within a year or two as dependencies update and original contributors
move on.

At the community level, sustainability means keeping contributors
engaged even as the initial excitement fades. Contributor burnout is the
leading cause of open-source project abandonment, and it is almost
always the result of a small number of people carrying too much of the
load (Cotton, 2023). PathFinder addresses this through rotating lead
roles, so the burden of maintenance is shared across the community
rather than concentrated in a few individuals. Clearly scoped good first
issues ensure a continuous pipeline of new contributors. A public
recognition system acknowledges contributions in release notes and
community announcements, making it clear that showing up matters.

At the financial level, early-stage funding will come from grants such
as the Mozilla Open Source Support program and GitHub Sponsors, combined
with university partnerships that provide infrastructure support in
exchange for access to the platform\'s anonymized recruiting analytics.
As the platform scales, an optional premium tier for university career
centers can provide a sustainable revenue stream without compromising
the free core that students use.

The risks to PathFinder\'s long-term success are real and worth naming
honestly. The most significant is adoption. A platform that tracks
applications is only useful if students actually use it consistently,
and a platform that offers community-contributed interview resources is
only valuable if those contributions are high quality. Achieving both
requires building genuine trust with the user base from the beginning,
which means being transparent about decisions, responsive to feedback,
and honest about limitations.

Scope creep is another significant risk. Career development is a broad
domain, and there will always be pressure to add features that seem
useful but dilute the platform\'s focus. The discipline of maintaining a
clear MoSCoW prioritization framework, where every proposed feature is
explicitly categorized as must-have, should-have, could-have, or
will-not-have for the current phase, is the primary defense against
this. It keeps the team focused on delivering real value to real users
rather than building an impressive feature list that nobody actually
uses.

## Conclusion

PathFinder is not a solution I invented for a class assignment. It is a
response to a problem I lived through and that I know many other
students are living through right now. The recruiting process is harder
than it needs to be, and the tools that could make it easier are either
locked behind paywalls or simply do not exist yet.

Building PathFinder as an open-source project is what makes it genuinely
different from the alternatives. Transparency means students can trust
it with sensitive information. Collaboration means it gets better
through the contributions of the community that uses it. Sustainability
means it cannot be taken away or monetized at students\' expense. These
are not just values. They are design decisions that shape every aspect
of how the platform is built and managed.

The principles covered in this course, working open, dynamic division of
labor, technical debt management, project lifecycle thinking, and the
honest assessment of automation\'s tradeoffs, are all directly reflected
in how PathFinder is structured. This paper has been an exercise in
applying those principles to something real, and the result is a project
plan that I am genuinely excited to continue developing beyond the end
of the semester.

PathFinder is designed to grow with its community, not despite it. That
is what makes it worth building.

## References

Alicea, B. (2026). Open Source Project Management \[Course Lecture
Notes\]. University of Illinois Urbana-Champaign.

Cotton, B. (2023). Program management for open source projects. The
Pragmatic Bookshelf.

Project Management Institute. (2021). A guide to the project management
body of knowledge (PMBOK guide) (7th ed.). Project Management Institute.

Watt, A. (2014). Project management. BCcampus Open Education.
https://opentextbc.ca/projectmanagement/
