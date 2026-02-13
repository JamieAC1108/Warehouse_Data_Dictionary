# Project Proposal

## 1. Project Identification
- **Project Title:** WareHouse_Data_Dictionary
- **Course:** CPT_298 : Computer Technology Capstone
- **Term:** Spring 2026
- **Student Name(s):** Jamie Cole, Teddy Robillard
- **Primary Contact:** Jamie Cole
- **Proposed Start Date:** 2/16/2026
- **Proposed End Date:** 3/08/2026

---

## 2. Project Selection & Motivation
Describe why you selected this project and why you are a good fit.

Include:
- Personal or professional motivation
- Alignment with career goals
- Relevant interests or prior exposure

    Teddy and I are both interested in the Networking and Data aspect of Computer Technology, so that simply lines up with what we'd want to do after college. I, specifically, and interested in working with data using SQL, Python, and other modes of data work. Both Teddy and Myself have taken classes and acquired skills that line up with this project, such as: SQL, Python, Process automation, Linux, and Web Development. This gives us skills in working with data, navigating linux, and HTML. 

---

## 3. Problem Statement
Clearly describe the problem, need, or opportunity this project addresses.

Answer:
- What problem exists?
- Who is affected?
- Why does this problem matter?

Limit to 1–2 focused paragraphs.

    The problem is that the warehouse datacenter dictionary is not automated, which creates an inconvienence to those trying to navigate and maintain the data dictionary in the warehouse. This matters because, the Datacenter Dictionary not being automated makes the job of people who use the Datacenter slow and inconvenient. Creating an automated data dictionary will make these jobs faster and lower effort, thus making the entire CPT department more functional. 

---

## 4. Proposed Solution Overview
Provide a high-level description of your proposed solution.

Include:
- What you intend to build, deploy, or configure
- Core features or capabilities
- Explicit exclusions (what the project will *not* include)

    Our group intends to build a program that processes the data base as a dictionary. Users will make requests using a website, that is then recieved by the program. The program will then find the requested data in the dictionary, and upload it to the web app that the user is on. Core features would include the ability to search for specific data using keywords. This would then display all data that matches the keyword(s). Another feature would allow one to surf through the data unfiltered, from newest to oldest. The exclusions would be a method to edit the data through the website, and restricting this to a website only. Most likely only accessible through the schools network. 

---

## 5. Technical Stack & Tools
List the technologies you expect to use.  Please note that this solution MUST live within the cpt.internal network and must be maintainable by future students.

- **Operating System(s):**
- **Programming Language(s):**
- **Frameworks / Libraries:**
- **Databases / Storage:**
- **Infrastructure (VMs, containers, etc.):**
- **Tools (Git, CI, monitoring, APIs, etc.):**

    - Linux
    - Python, SQL, HTML, CSS
    - Pandas, Request
    - The school database
    - Website stored on the school's servers. 
    - GIT, API's, VSCode
---

## 6. Prerequisite Knowledge & Skills
Assess your readiness for this project.

Include:
- Skills you already have
- Skills you need to learn
- Relevant coursework completed
- Prior projects or experience

Be honest—this section helps scope the project appropriately.

    Both Teddy and myself already have skills using pandas, requests, and API's to surf through data, specifically dictionaries. Teddy is familiar with Linux, more so than myself. I have very surface level experience using pgAdmin4 to create queries to databases. We both have experience writing programs in python, specifically to request and upload data. Both of us have experience creating websites using HTML and CSS. Some skills we would need to acquire is the actual process automation, and the connection of the Python script to the website itself. We also need to learn how to set up a dedicated domain for a website. 

---

## 7. Project Scope & Deliverables
Define what success looks like.

Include:
- Minimum viable deliverable (MVP)
- Required outputs (application, scripts, documentation, etc.)
- Optional stretch goals (if time permits)

---

    The minimum viable deliverable(s) would be the main.py, all html/css files, and the Linux process. Out outputs would be website, scripts being run, and possibly a readme that contains specifics regarding the website. Some stretch goals would be making the website far more intuitive in it's filters and search. 

## 8. Milestones & Timeline
Provide a rough timeline broken into phases.

Example:
- Phase 1: Research & Design
- Phase 2: Core Implementation
- Phase 3: Testing & Refinement
- Phase 4: Documentation & Presentation

Dates do not need to be exact, but planning is required.

    Phase 1: Research and Basic scripts and files.
    Phase 2: Connection to process, scripts, and websites. 
    Phase 3: Refining it, condensing it, prettifying it. 
    Phase 4: Write-up and Presentation. 

---

## 9. Risks, Constraints & Dependencies
Identify potential challenges.

Include:
- Technical risks
- Time constraints
- External dependencies (APIs, credentials, access)
- Mitigation strategies

    Our group is mostly going to be limited by our access to the data given that we are simply students. Our time is rather limited, as we are starting a little later than prefered. We only have about 4 weeks. We would need access to the data base itself, so we'd need to be given the valid credentials. Our mitigation strategy is simply doing all we can with our current access and technical level. For the time, we have scheduled out two times a week where we will meet, this forcing us on a timeline. 

---

## 10. Security, Ethics & Safety Considerations
Address any relevant concerns, such as:
- Authentication and authorization
- Data sensitivity
- Network exposure
- Logging, monitoring, or automation impact
- Ethical considerations

A brief assessment of all of these is required, even if it is "N/A".

    The group is worried that we are not capable of accessing everything we may need to make the dictionary. There is sensitive data in the school, so we may not even be able to access it. Having a process going upon request, thus being able to be ran all the time, could have some impact on the existing processes for the school. The ethical thing we need to consider is how much data we are putting on the table. 

---

## 11. Team Structure (If Applicable)
If working in a group, describe:
- Team roles
- Communication plan
- Conflict resolution approach
- Workload distribution

    Jamie: Responsible for the heavy lifting regarding the website (The programming and prettifying it), condensing code and making the wesbite user friendly. 
    Teddy: Responsible for the server that the process and website will have to run on, as well as the bulk of the program coding. 
    Both: Both are responsible for simple upkeep and communication throughout the process. 
    Conflict Resolution : Simply talk it out. 

---

## 12. Documentation & Knowledge Transfer Plan
Explain how this project will be documented.  Please note that this should include documentation in the UVDesk knowledgebase at the very least.  Programming projects should include readme.md files. 

Include:
- README or user documentation
- Deployment or maintenance guides
- How another student or administrator could continue the project

    The project will be documented through readme files, as well as notes including what was updated. On the website there will be an About page that serves as a tutorial, as well as examples of good tags to use. This could be continued in refining it and possibly turning it into a full fledged site. It could also be turned into an app. 

---

## 13. Faculty/cpt.internal Resources Requested
List any required resources:
- VM access
- Network access
- Credentials or APIs
- Special permissions
- Hardware (if applicable)

Please be sure to consider any future tickets you may need to submit to complete this work as those will need to be generated and assigned to the appropriate groups as soon as feasibly possible once the project kicks off to ensure timely delivery.  I will step in to help where required but you will likely be working with students in other classes so please be cognizant of their time!
    
    The group will need a credentials and the API for the data base. That could possibly need special permissions. The group would also simply need some space on the server to run our process. We would, of course, need access to the data base of the school. 

---

## 14. Acknowledgement of Expectations
By submitting this proposal, I acknowledge that:
- This is a self-directed technical project
- I am responsible for research and troubleshooting
- Evaluation will consider process, documentation, and professionalism

**Signature (Name & Date):**

Student 1:  ____Jamie Cole_____ Date: ___02/13/2026_____
Student 2:  ____Teddy Robillard______________ Date: ___02/13/2026___
Student 3:  ____________________________ Date: _______________
Student 4:  ____________________________ Date: _______________

Instructor: ____________________________ Date: _______________
