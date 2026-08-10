<div align="center" style="text-align: center">
<img src="images/ossu-logo.png" alt="Open Source Society University Logo"/>
<h3>Open Source Society University</h3>
<p>
  Path to a free self-taught education in Computer Science!
</p>
<p>
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Shield: Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"
  ></a>
  <a href="https://github.com/ossu/computer-science">
    <img alt="Shield: OSSU - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg"
  ></a>
</p>
</div>

# Contents

- [Summary](#summary)
- [Community](#community)
- [CS-Curriculum](#cs-curriculum)
- [Code of Conduct](#code-of-conduct)
- [Team](#team)

# Summary

The OSSU curriculum is a **complete education in computer science** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all computing disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.

It is designed according to the degree requirements of undergraduate computer science majors, minus general education (non-CS) requirements,
as it is assumed most of the people following this curriculum are already educated outside the field of CS.
The courses themselves are among the very best in the world, often coming from Harvard, Princeton, MIT, etc.,
but specifically chosen to meet the following criteria.

**Courses must**:
- Be open for enrollment
- Run regularly (ideally in self-paced format, otherwise running multiple times per year)
- Be of generally high quality in teaching materials and pedagogical principles
- Match the curricular standards of the [CS 2013](CURRICULAR_GUIDELINES.md): Curriculum Guidelines for Undergraduate Degree Programs in Computer Science

When no course meets the above criteria, the coursework is supplemented with a book.
When there are courses or books that don't fit into the curriculum but are otherwise of high quality, they belong in [extras/courses](extras/courses.md) or [extras/readings](extras/readings.md).

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide

**Duration**. It is possible to finish within about 2 years if you plan carefully and devote roughly 20 hours per week to your studies. Learners can use [this spreadsheet](https://docs.google.com/spreadsheets/d/1y2kMsIg9VaHMVmw35x_aH1hpty3V-ZMuV2jA13P_Cgo/copy) to estimate their end date. Make a copy and input your start date and expected hours per week in the `Timeline` sheet. As you work through courses you can enter your actual course completion dates in the `Curriculum Data` sheet and get updated completion estimates.
  
> **Warning:** While the spreadsheet is a useful tool to estimate the time you need to complete this curriculum, it may not always be up-to-date with the curriculum. Use the [OSSU CS website](https://cs.ossu.dev) or [the GitHub Repo](https://github.com/ossu/computer-science) to see what courses to do.

**Cost**. All or nearly all course material is available for free. However, some courses may charge money for assignments / tests / projects to be graded.
Note that both [edX](https://courses.edx.org/financial-assistance/) and [Coursera](https://www.coursera.support/s/article/209819033-Apply-for-Financial-Aid-or-a-Scholarship?language=en_US) offer financial aid.

Decide how much or how little to spend based on your own time and budget;
just remember that you can't purchase success!

**Process**. Students can work through the curriculum alone or in groups, in order or out of order.
- We recommend doing all courses in Core CS, only skipping a course when you are certain that you've already learned the material previously.
- For simplicity, we recommend working through courses (especially Core CS) in order from top to bottom. Some students choose to study multiple courses at a time in order to vary the material they are working on in a day or week. A popular option is to take the math courses in parallel with the introductory courses. Course prerequisites are listed to help you determine if you are prepared for a given course.
- Courses in Advanced CS are electives. Choose one subject (e.g. Advanced programming) you want to become an expert in and take all the courses under that heading. You can also create your own custom subject; the Discord community may provide feedback on your planned subject.

**Content policy**. If you plan on showing off some of your coursework publicly, you must share only files that you are allowed to.
*Respect the code of conduct* that you signed in the beginning of each course!

**[How to contribute](CONTRIBUTING.md)**

**[Getting some help](HELP.md)** (Details about our FAQ and Chatroom)

# Community

- We have a Discord server! This should be your first stop to talk with other OSSU students. Why don't you introduce yourself right now? [Join the OSSU Discord](https://discord.gg/wuytwK5s9h)
- You can also interact through GitHub issues. If there is a problem with a course, or a change needs to be made to the curriculum, this is the place to start the conversation. Read more [here](CONTRIBUTING.md).
- Add **Open Source Society University** to your [Linkedin](https://www.linkedin.com/school/11272443/) profile!

> **Warning:** There are a few third-party/deprecated/outdated material that you might find when searching for OSSU. We recommend you to ignore them, and only use the [OSSU CS website](https://cs.ossu.dev) or [OSSU CS GitHub Repo](https://github.com/ossu/computer-science). Some known outdated materials are:
>  - An unmaintained and deprecated firebase app. Read more in the [FAQ](./FAQ.md#why-is-the-firebase-ossu-app-different-or-broken).
>  - An unmaintained and deprecated trello board
>  - Third-party notion templates

# CS-Curriculum

- [Prerequisites](#prerequisites)
- [Intro CS](#intro-cs)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [Core math](#core-math)
  - [CS Tools](#cs-tools)
  - [Core systems](#core-systems)
  - [Core theory](#core-theory)
  - [Core security](#core-security)
  - [Core applications](#core-applications)
  - [Core ethics](#core-ethics)
- [Advanced CS](#advanced-cs)
  - [Advanced programming](#advanced-programming)
  - [Advanced systems](#advanced-systems)
  - [Advanced theory](#advanced-theory)
  - [Advanced information security](#advanced-information-security)
  - [Advanced math](#advanced-math)
- [Final project](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://ossu.dev/precollege-math) or pre-college math courses, including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken basic physics courses, e.g. physics in high school or pre-college physics courses, etc.

## Intro CS

This course will introduce you to the world of computer science and programming. This course gives you a flavor of the material to come. If you finish the course wanting more, Computer Science is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--: 
[Introduction to Computer Science and Programming using Python](coursepages/intro-cs/README.md) | 14 weeks | 6-10 hours/week | [High School Math](https://ossu.dev/precollege-math) | ✅ | [Computer Science for Python Programming](https://www.edx.org/certificates/professional-certificate/harvardx-computer-science-for-python-programming) | [Own Certificate](https://credentials.edx.org/credentials/e6e3fd24f97e42e082a9e5bfd93e0846/)

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof 
:--: | :--: | :--: | :--: | :--: | :--: | :--: 
[Systematic Program Design](coursepages/spd/README.md) | 13 weeks | 8-10 hours/week | - | ✅ | [CS50's Introduction to Computer Science](https://cs50.harvard.edu/x/) | [Own Certificate](https://certificates.cs50.io/9904bc2c-2067-4045-a299-5861696c1d50.pdf?size=A4) 
[Class-Based Program Design](coursepages/class-based/README.md) | 13 weeks | 5-10 hours/week | [Systematic Program Design](coursepages/spd/README.md), [High School Math](https://ossu.dev/precollege-math) | ✅ | [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) | [Own Certificate](https://certificates.cs50.io/0c356023-eb6f-4ee5-8721-e10b14ba3d92.pdf?size=A4) 
[Programming Languages](https://courses.cs.washington.edu/courses/cse341/19sp/#lectures) | 11 weeks | 4-8 hours/week | [Systematic Program Design](coursepages/spd/README.md) | ✅ | [Introduction to Programming](https://programming-24.mooc.fi/) and [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) | [Own Certificate](https://certificates.mooc.fi/validate/mrmzq0gp63) and [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment) 
[Object-Oriented Design](https://course.ccs.neu.edu/cs3500f19/) | 13 weeks | 5-10 hours/week | [Class-Based Program Design](coursepages/class-based/README.md) | ✅ | [Advanced Programming](https://programming-24.mooc.fi/) and [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) | [Own Certificate](https://certificates.mooc.fi/validate/jn6kits13rs) and [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment) 
[Software Architecture](https://www.coursera.org/learn/software-architecture) | 4 weeks | 2-5 hours/week | [Object-Oriented Design](https://course.ccs.neu.edu/cs3500f19/) | ✅ | [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) and [Per Own Project](https://github.com/Cranjah/Challenge-Green-Trip) | [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment) and [Per Own Project](https://github.com/Cranjah/Challenge-Green-Trip) 

### Core math
Discrete math (Math for CS) is a prerequisite and closely related to the study of algorithms and data structures. Calculus both prepares students for discrete math and helps students develop mathematical maturity.

**Topics covered**:
`discrete mathematics`
`mathematical proofs`
`basic statistics`
`O-notation`
`discrete probability`
`and more`

Courses | Duration | Effort | Notes | Prerequisites | Passed | Taken | Proof 
:--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: 
[Calculus 1A: Differentiation](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.1x+2T2019/about) ([alternative](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/index.htm)) | 13 weeks | 6-10 hours/week | The [alternative](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/index.htm) covers this and the following two courses | [High School Math](https://ossu.dev/precollege-math) | - | - | - 
[Calculus 1B: Integration](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.2x+3T2019/about) | 13 weeks | 5-10 hours/week | - | [Calculus 1A](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.1x+2T2019/about) | - | - | - 
[Calculus 1C: Coordinate Systems & Infinite Series](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.3x+1T2020/about) | 6 weeks | 5-10 hours/week | - | [Calculus 1B](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.2x+3T2019/about) | - | - | - 
[Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) ([alternative](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/)) | 13 weeks | 5 hours/week | - | [Calculus 1C](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.3x+1T2020/about) | 🚧 | [Per eBook Reading](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf) | [Per eBook Reading](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf) 

### CS Tools
Understanding theory is important, but you will also be expected to create programs. There are a number of tools that are widely used to make that process easier. Learn them now to ease your future work writing programs.

**Topics covered**:
`terminals and shell scripting`
`vim`
`command line environments`
`version control`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof 
:--: | :--: | :--: | :--: | :--: | :--: | :--: 
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week | - | ✅ | [Introduction to Linux](https://www.edx.org/learn/linux/the-linux-foundation-introduction-to-linux) and [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) | [Own Certificate](https://verify.edx.org/cert/006d9c67cffe43bc98bc4304a3a9b7f0) and [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment) 

### Core systems

**Topics covered**:
`procedural programming`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Additional Text / Assignments | Prerequisites | Passed | Taken | Proof 
:--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: 
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alternative](https://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | - | C-Like Programming Language | 🚧 | [Per eBook Reading](https://www.nand2tetris.org/) | [Per eBook Reading](https://www.nand2tetris.org/)
[Build a Modern Computer from First Principles: Nand to Tetris Part II](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | [One of these Programming Languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), [From Nand to Tetris Part I](https://www.coursera.org/learn/build-a-computer) | 🚧 | [Per eBook Reading](https://www.nand2tetris.org/) | [Per eBook Reading](https://www.nand2tetris.org/)
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | [Nand to Tetris Part II](https://www.coursera.org/learn/nand2tetris2) | - | - | -
[Computer Networking: a Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](https://gaia.cs.umass.edu/kurose_ross/wireshark.php) | Algebra, Probability, Basic CS | - | - | -

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Algorithms: Design and Analysis, Part 1](https://www.edx.org/learn/algorithms/stanford-university-algorithms-design-and-analysis-part-1) ([alternative](https://www.algorithmsilluminated.org/)) | 8 weeks | 4-8 hours/week | Any Programming Language, [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) | 🚧 | [Algorithms, Part 1 in Progress](https://www.coursera.org/learn/algorithms-part1) and [Per Own Project](https://github.com/Cranjah/Casual-TSP-Iterations) | [Per Own Project](https://github.com/Cranjah/Casual-TSP-Iterations)
[Algorithms: Design and Analysis, Part 2](https://www.edx.org/learn/algorithms/stanford-university-algorithms-design-and-analysis-part-2) | 8 weeks | 4-8 hours/week | [Algorithms Part 1](https://www.edx.org/learn/algorithms/stanford-university-algorithms-design-and-analysis-part-1) | 🚧 | [Algorithms, Part 2 in Progress](https://www.coursera.org/learn/algorithms-part2) and [Per Own Project](https://github.com/Cranjah/Casual-TSP-Iterations) | [Per Own Project](https://github.com/Cranjah/Casual-TSP-Iterations)

### Core security
**Topics covered**
`Confidentiality, Integrity, Availability`
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.edx.org/learn/cybersecurity/rochester-institute-of-technology-cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - | ✅ | [CS50's Introduction to Cybersecurity](https://cs50.harvard.edu/cybersecurity/) | [Own Certificate](https://certificates.cs50.io/0c356023-eb6f-4ee5-8721-e10b14ba3d92.pdf?size=A4)
[Cybersecurity Fundamentals](https://www.edx.org/learn/cybersecurity/rochester-institute-of-technology-cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - | ✅ | [Cyberwar, Surveillance and Security](https://learning.edx.org/course/course-v1:AdelaideX+Cyber101x+1T2016/home) | [Own Certificate](https://courses.edx.org/certificates/6d2f92bb12514c85a5186501d583c4a6)
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week | - | - | - | -
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week | - | - | - | -

Choose **one** of the following:

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++ Programming](https://www.coursera.org/learn/identifying-security-vulnerabilities-c-programming) | 4 weeks | 5 hours/week | - | - | - | -
[Exploiting and Securing Vulnerabilities in Java Applications](https://www.coursera.org/learn/exploiting-securing-vulnerabilities-java-applications) | 4 weeks | 5 hours/week | - | - | - | -

### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`ray tracing`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Databases: Modeling and Theory](https://www.edx.org/learn/databases/stanford-university-databases-modeling-and-theory)| 2 weeks | 10 hours/week | Core Programming | ✅ | [Introduction to SQL](https://www.sololearn.com/de/learn/courses/sql-introduction) and [Intermediate SQL](https://www.sololearn.com/de/learn/courses/sql-intermediate) | [Own Certificate](https://www.sololearn.com/certificates/CC-NQK6PTHO) and [Own Certificate](https://www.sololearn.com/certificates/CC-OLKX4KPI)
[Databases: Relational Databases and SQL](https://www.edx.org/learn/relational-databases/stanford-university-databases-relational-databases-and-sql)| 2 weeks | 10 hours/week | Core Programming | ✅ | [Introduction to SQL](https://www.sololearn.com/de/learn/courses/sql-introduction) and [Intermediate SQL](https://www.sololearn.com/de/learn/courses/sql-intermediate) | [Own Certificate](https://www.sololearn.com/certificates/CC-NQK6PTHO) and [Own Certificate](https://www.sololearn.com/certificates/CC-OLKX4KPI)
[Databases: Semistructured Data](https://www.edx.org/learn/relational-databases/stanford-university-databases-semistructured-data)| 2 weeks | 10 hours/week | Core Programming | ✅ | [Introduction to SQL](https://www.sololearn.com/de/learn/courses/sql-introduction) and [Intermediate SQL](https://www.sololearn.com/de/learn/courses/sql-intermediate) | [Own Certificate](https://www.sololearn.com/certificates/CC-NQK6PTHO) and [Own Certificate](https://www.sololearn.com/certificates/CC-OLKX4KPI)
[Machine Learning](https://www.deeplearning.ai/courses/machine-learning-specialization/)| 11 weeks | 9 hours/week | Basic Coding | - | - | -
[Computer Graphics](https://www.edx.org/learn/computer-graphics/the-university-of-california-san-diego-computer-graphics) ([alternative](https://cseweb.ucsd.edu/~viscomp/classes/cse167/wi22/schedule.html))| 6 weeks | 12 hours/week | C++ or Java, [Basic Linear Algebra](https://ossu.dev/precollege-math/coursepages/precalculus) | - | - | -
[Software Engineering: Introduction](https://www.edx.org/learn/software-engineering/university-of-british-columbia-software-engineering-introduction) ([alternative](https://github.com/ubccpsc/310/blob/main/resources/README.md)) | 6 weeks | 8-10 hours/week | Core Programming, [Sizable Project](FAQ.md#why-require-experience-with-a-sizable-project-before-the-Software-Engineering-courses) | - | - | -

### Core ethics

**Topics covered**:
`Social Context`
`Analytical Tools`
`Professional Ethics`
`Intellectual Property`
`Privacy and Civil Liberties`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Ethics, Technology and Engineering](https://www.coursera.org/learn/ethics-technology-engineering) | 9 weeks | 2 hours/week | - | ✅ | [Justice](https://www.edx.org/learn/justice/harvard-university-justice) and [Justice Today](https://www.edx.org/learn/justice/harvard-university-justice-today-money-markets-and-morals) | [Own Certificate](https://courses.edx.org/certificates/b3ad4ae46b6d47b89006e92705f56048) and [Own Certificate](https://courses.edx.org/certificates/1c950a39428a4689a9b30ab8be1698dd)
[Introduction to Intellectual Property](https://www.coursera.org/learn/introduction-intellectual-property) | 4 weeks | 2 hours/week | - | ✅ | [Justice](https://www.edx.org/learn/justice/harvard-university-justice) and [Justice Today](https://www.edx.org/learn/justice/harvard-university-justice-today-money-markets-and-morals) | [Own Certificate](https://courses.edx.org/certificates/b3ad4ae46b6d47b89006e92705f56048) and [Own Certificate](https://courses.edx.org/certificates/1c950a39428a4689a9b30ab8be1698dd)
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy) | 3 weeks | 3 hours/week | - | ✅ |  [Justice](https://www.edx.org/learn/justice/harvard-university-justice) and [Justice Today](https://www.edx.org/learn/justice/harvard-university-justice-today-money-markets-and-morals)  | [Own Certificate](https://courses.edx.org/certificates/b3ad4ae46b6d47b89006e92705f56048) and [Own Certificate](https://courses.edx.org/certificates/1c950a39428a4689a9b30ab8be1698dd)

## Core Voluntary Bonuses

### Core artificial intelligence

**Topics covered**:
`Artificial Intelligence`
`Search Algorithms`
`Machine Learning`
`Probability and Statistics`
`Optimization`
`Neural Networks`
`Language Processing`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Elements of AI](https://www.elementsofai.com/) | 6 weeks | 10 hours/week | - | ✅ | [Elements of AI](https://www.elementsofai.com/) | [Own Certificate](https://certificates.mooc.fi/validate/mro58gy02yl)
[Building AI](https://buildingai.elementsofai.com/) | 5 weeks | 10 hours/week | Python, Core Programming, [Elements of AI](https://www.elementsofai.com/) | ✅ | [Building AI](https://buildingai.elementsofai.com/) | [Own Certificate](https://certificates.mooc.fi/validate/sdnqa8u17h)
[CS50's Introduction to Artificial Intelligence with Python](https://www.edx.org/learn/artificial-intelligence/harvard-university-cs50-s-introduction-to-artificial-intelligence-with-python) ([alternative](https://cs50.harvard.edu/ai/)) | 7 weeks | 10-30 hours/week | Python, Core CS, Core Programming | 🚧 | [CS50's Introduction to Artificial Intelligence with Python](https://www.edx.org/learn/artificial-intelligence/harvard-university-cs50-s-introduction-to-artificial-intelligence-with-python) ([alternative](https://cs50.harvard.edu/ai/)) | No Proof Yet

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming)| 4 weeks | 6-8 hours/week | Scala Programming | - | - | - 
[Compilers](https://www.edx.org/learn/computer-science/stanford-university-compilers) | 9 weeks | 6-8 hours/week | - | - | - | - 
[Introduction to Haskell](https://www.seas.upenn.edu/~cis194/fall16/) | 14 weeks | - | - | - | - | - 
[Learn Prolog Now!](https://www.let.rug.nl/bos/lpn//lpnpage.php?pageid=online) ([alternative](https://github.com/ossu/computer-science/files/6085884/lpn.pdf))*| 12 weeks | - | - | - | - | - 
[Software Debugging](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkxK63TiT88oEe-AIBhr96A) | 8 weeks | 6 hours/week | Python, Object-Oriented Programming | - | - | - 
[Software Testing](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkWVHeC_8aSIbSxE_NXI76g) | 4 weeks | 6 hours/week | Python, Programming Experience | - | - | - 

(*) book by Blackburn, Bos, Striegnitz (compiled from [source](https://github.com/LearnPrologNow/lpn), redistributed under [CC license](https://creativecommons.org/licenses/by-sa/4.0/))

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Courses | Duration | Effort | Prerequisites | Notes | Passed | Taken | Proof 
:--: | :--: | :--: | :--: | :--:| :--: | :--: | :--: 
[Computation Structures 1: Digital Circuits](https://learning.edx.org/course/course-v1:MITx+6.004.1x_3+3T2016) ([alternative 1](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/) / [alternative 2](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/)) | 10 weeks | 6 hours/week | [Nand2Tetris II](https://www.coursera.org/learn/nand2tetris2) | Alternative links contain all three courses | - | - | - 
[Computation Structures 2: Computer Architecture](https://learning.edx.org/course/course-v1:MITx+6.004.2x+3T2015) | 10 weeks | 6 hours/week | [Computation Structures 1](https://learning.edx.org/course/course-v1:MITx+6.004.1x_3+3T2016) | -  | - | - | - 
[Computation Structures 3: Computer Organization](https://learning.edx.org/course/course-v1:MITx+6.004.3x_2+1T2017) | 10 weeks | 6 hours/week | [Computation Structures 2](https://learning.edx.org/course/course-v1:MITx+6.004.2x+3T2015) | - | - | - | - 

### Advanced theory

**Topics covered**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`game trees`
`and more`

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof 
:--: | :--: | :--: | :--:| :--: | :--: | :--: 
[Theory of Computation](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/) ([alternative](https://www.youtube.com/playlist?list=PLEE7DF8F5E0203A56)) | 13 weeks | 10 hours/week | [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about), [Logic](https://forallx.openlogicproject.org/), Core Algorithms | - | - | - 
[Computational Geometry](https://www.edx.org/learn/geometry/tsinghua-university-ji-suan-ji-he-computational-geometry) | 16 weeks | 8 hours/week | Algorithms, C++ | - | - | - 
[Algorithmic Game Theory](https://timroughgarden.org/f13/f13.html) | 10 weeks | 12 hours/week | Core Theory | - | - | - 

### Advanced Information Security

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--: 
[Web Security Fundamentals](https://www.edx.org/learn/computer-security/ku-leuven-web-security-fundamentals) | 5 weeks | 4-6 hours/week | Understanding Basic Web Technologies  | - | - | -
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | - | - | - | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security | ✅ | [Computer Forensics](https://www.edx.org/learn/computer-forensics/rochester-institute-of-technology-computer-forensics) | No Proof Yet
[Secure Software Development: Requirements, Design, and Reuse](https://www.edx.org/learn/software-development/the-linux-foundation-secure-software-development-requirements-design-and-reuse) | 7 weeks | 1-2 hours/week | Core Programming and Core Security | - | - | - 
[Secure Software Development: Implementation](https://www.edx.org/learn/software-development/the-linux-foundation-secure-software-development-implementation) | 7 weeks | 1-2 hours/week | Secure Software Development: Requirements, Design, and Reuse | - | - | - 
[Secure Software Development: Verification and More Specialized Topics](https://www.edx.org/learn/software-engineering/the-linux-foundation-secure-software-development-verification-and-more-specialized-topics) | 7 weeks | 1-2 hours/week | Secure Software Development: Implementation | - | - | - 

### Advanced math

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [High School Math](https://ossu.dev/precollege-math) | ✅ | [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) | [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment)
[Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | 14 weeks | 12 hours/week | [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | ❌ | [Per HWR Curriculum](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Curriculum) | [Per HWR Enrollment](https://github.com/Cranjah/Cranjah/tree/main/studies/HWR-Berlin-Enrollment)
[Introduction to Numerical Methods](https://ocw.mit.edu/courses/mathematics/18-335j-introduction-to-numerical-methods-spring-2019/index.htm)| 14 weeks | 12 hours/week | [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | - | - | -
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) | 🚧 | [Per eBook Reading](https://forallx.openlogicproject.org/) | [Per eBook Reading](https://forallx.openlogicproject.org/)
[Probability](https://stat110.hsites.harvard.edu/) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](https://www.edx.org/course/calculus-1b-integration) | - | - | -

## Final project

Part of learning is doing.
The assignments and exams for each course are to prepare you to use your knowledge to solve real-world problems.

After you've completed Core CS and the parts of Advanced CS relevant to you,
you should identify a problem that you can solve using the knowledge you've acquired.
You can create something entirely new, or you can improve some tool / program that you use.

Students who would like more guidance in creating a project may choose to use a series of project oriented courses.
Here is a sample of options
(many more are available, at this point you should be capable of identifying a series that is interesting and relevant to you):

Courses | Duration | Effort | Prerequisites | Passed | Taken | Proof
:--: | :--: | :--: | :--: | :--: | :--: | :--:
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | Core Programming | - | - | - 
[Modern Robotics](https://modernrobotics.northwestern.edu) | 26 weeks | 2-5 hours/week | Freshman-Level Physics, Linear Algebra, Calculus, [Linear Ordinary Differential Equations](https://www.khanacademy.org/math/differential-equations) | - | - | - 
[Data Mining (Specialization)](https://www.coursera.org/specializations/data-mining) | 30 weeks | 2-5 hours/week | [Machine Learning](https://www.deeplearning.ai/courses/machine-learning-specialization/) | - | - | - 
[Big Data (Specialization)](https://www.coursera.org/specializations/big-data) | 30 weeks | 3-5 hours/week | - | - | - | - 
[Internet of Things (Specialization)](https://www.coursera.org/specializations/internet-of-things) | 30 weeks | 1-5 hours/week | Strong Programming | - | - | - 
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ Programming | - | - | - 
[Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | - | - | - | - 
[Functional Programming in Scala (Specialization)](https://www.coursera.org/specializations/scala) | 29 weeks | 4-5 hours/week | One Year Programming Experience | - | - | - 
[Game Design and Development with Unity 2020 (Specialization)](https://www.coursera.org/specializations/game-design-and-development) | 6 months | 5 hours/week | Programming, Interactive Design | - | - | -

## Congratulations

After completing the requirements of the curriculum above, you will have completed the equivalent of a full bachelor's degree in Computer Science. Congratulations!

What is next for you? The possibilities are boundless and overlapping:

- Look for a job as a developer!
- Check out the [readings](extras/readings.md) for classic books you can read that will sharpen your skills and expand your knowledge.
- Join a local developer meetup (e.g. via [meetup.com](https://www.meetup.com/)).
- Pay attention to emerging technologies in the world of software development:
  + Explore the **actor model** through [Elixir](https://elixir-lang.org/), a new functional programming language for the web based on the battle-tested Erlang Virtual Machine!
  + Explore **borrowing and lifetimes** through [Rust](https://www.rust-lang.org/), a systems language which achieves memory- and thread-safety without a garbage collector!
  + Explore **dependent type systems** through [Idris](https://www.idris-lang.org/), a new Haskell-inspired language with unprecedented support for type-driven development.

<img src="images/keep-learning.png" alt="Keep Learning."/>

# Code of Conduct
[OSSU's code of conduct](https://github.com/ossu/code-of-conduct).

## How to show your progress

[Fork](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/) the [GitHub Repo](https://github.com/ossu/computer-science) into your own GitHub Account and put ✅ next to the stuff you've completed as you complete it. This can serve as your [Kanban Board](https://en.wikipedia.org/wiki/Kanban_board) and will be faster to implement than any other solution (giving you time to spend on the courses). Use the ❌ to mark courses you did not pass (just in case) and 🚧 for things you are working on at the moment, might be a course / reading in progress or something else - be creative!

# Team

* **[Eric Douglas](https://github.com/ericdouglas)**: founder of OSSU
* **[Josh Hanson](https://github.com/joshmhanson)**: lead technical maintainer
* **[Waciuma Wanjohi](https://github.com/waciumawanjohi)**: lead academic maintainer
* **[Marc-Michel Münch](https://github.com/cranjah)**: student of this OSSU repo
* **[Contributors](https://github.com/ossu/computer-science/graphs/contributors)**

