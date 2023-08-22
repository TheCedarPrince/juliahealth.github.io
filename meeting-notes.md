@def title = "JuliaHealth - Meeting Notes"
@def hasmath = true

These are the public notes for the JuliaHealth Community.
Notes are published publicly here and are available for comments and review on the [public HackMD](https://hackmd.io/@AQm1lp9PSPyir6IoTPAZeQ/SJNu_d3uh). 
Additionally, the notes are [hosted publicly on the GitHub](https://github.com/JuliaHealth/juliahealth.github.io/blob/dev/meeting-notes.md) and are open for PRs or edits as needed.

# August 25 2023

**In Attendance:** 

**Location:** Virtual (JuliaHealth Google Meet)

**Summary:** 

**Keywords:** 

## Agenda

1. New member introductions 

2. Running tasks follow-ups:

  a. Short-term task follow-ups:

    i. @Jacob Set-up HackMD to take notes going forward

      - Copy and paste meeting minutes over to JuliaHealth PR to update at end of meetings

    ii. @Dilum finds out how to live stream JuliaHealth BoF

  b. Long-term task follow-ups:

    i. Creating a template repository 

3. Debrief from JuliaCon

  a. Interoperability of Julia with health research ecosystems (R)

  b. Develop and document tutorials showcasing compositional solutions to JuliaHealth ecosystem problems

  c. Coordinate with bigger Julia Blog to bridge between communities even better

  d. Databases and JuliaHealth

4. Open discussion on next steps for the JuliaHealth community

## Meeting Outcomes

### Short-Term Outcomes



### Long-Term Outcomes



## Notes



# July 28 2023

**In Attendance:** [Attendance Waived for In-Person Meeting

**Location:** JuliaCon 2023 JuliaHealth Birds of a Feather

**Summary:** New member backgrounds, problems within the Julia ecosystem related to healthcare, thoughts on addressing issues within a JuliaHealth context, and learning resources for Julia within the context of health.

**Keywords:** #ehr #genomics #biology #interoperability #database #sql #outreach 

## Agenda

1. Introductions and what people in the community are using Julia for in health research

2. What is missing of painful in Julia that is needed to drive health research forward

3. Thoughts on how to address some of these problems

4. Open discussion and next steps for JuliaHealth

### Short-Term Outcomes

Not Available

### Long-Term Outcomes

- ACTION: Develop and document tutorials showcasing compositional solutions to JuliaHealth ecosystem problems.

- ACTION: Establish cohesive and organized Julia Blog to guide users and highlight official blogs.

## Meeting Notes

- Attendee interests and background

  * Here to learn

  * From EHR development and background

  * Genie folks here to support JuliaHealth endeavors

  * Genomics research and prevention

  * Quebec Heart and Lung Institute

  * Representing PumasAI 

  * Consulting group

    + Developing health research in Michigan area

    + Aggregating claims data

    + To learn what is going on in the community

  * Creator of [MetaAnalysis.jl](https://github.com/arinbasu/MetaAnalysis.jl)

  * Involved with backend of healthcare IT

  * Working on JuliaHub

    + Learning about packages that are out there

    + Here to support JuliaHealth members

    + New Zealand longitudinal child health 

      + Have own secure system 

      + Post-COVID syndrome 

    + Computational biology 

      + Sickle Cell 

      + Applying some ML

* Problems within the Julia ecosystem

  + Julia needs more database connectivity to more easily do operations research

  + Databases are a pain point and composing with other aspects of the ecosystem

  + Interoperability within Julia and other sorts of resources

  + I end up doing the bare minimum in SQL

    + Do we have RAM?

    + Can we pull this into the Julia ecosystem?

    + Crank up the RAM! But only so much scaling

    + Minimal SQL writing

      + Searchlight.jl: Julia ORM layer within 

    + Is Genie like a shiny?

      + No, more of a full-stack

      + Goes beyond just visualization dashboards

  + Sequencing data

    + Equally data 

    + Everyone uploads data in slightly different ways

    + Make simple ways to pull that data

    + R Conductor --> JuliaConductor? 

      + Would make genomic pipelines within Julia pipelines a lot easier

    + We need to understand the underlying structures

    + One of the big pain points

      + Often to have roll your own

  + EpiR --> EpiJ?

    + Power calculators

  + Co-founder of start-up

    + Found unmet need for remote monitoring for neuotropenia

    + Non-invasive screen for neutropenia

    + Device runs Julia 

    + Pain points:

      + Testability of hardware

      + LOTS of CI -- bit of a pain

      + How much repetition happens in CI

    + Part of the problem for these problems:

      + There are still going to be folks who use the same organizations

      + Overcoming inertia to do the same or similar things in Julia

      + Wrapping around Julia? 

        + Bringing it into the R ecosystem

        + Leading to big impacts for callable things from R by having smaller static binaries

        + Wrapping Julia packages in R

      + N3C -- National COVID Cohort Collaborative

        + Went to many healthcare systems across the US to get COVID data

        + Shelled out to Palantir

        + Open source tools within the ecosystem

        + JuliaHub has Boeing board member

          + Trusted within security community

          + Could help in this situation

- Thoughts on how to address some of these problems

  * Using other packages outside of Julia

    + If you have some way to wrap around it

    + Getting support 

    + PythonCall.jl or RCall.jl

      + Not clear how to make this compositional

  * The paradox of compositionality

    + Blog posts go a huge ways to solving problems

    + Tutorials showing how things can be combined together

    + Promotional type material

    + Nice docs are *nice* 

  * The Julia Blog itself

    + Mentions JuliaBloggers but doesn't help with guiding users to read

    + Blogs need to go on as official blogs

    + Julia Forem -- is it maintained?

      + Hook into the tags from blogs

      + Cross-posting where appropriate

  * How to learn Julia within the context of health 

    + Carpentries for learning resources

# June 30 2023

## Meeting Summary

**In Attendance:** Jacob Zelko, Fareeda Abdelazeez, Zachary Christensen

**Location:** Virtual

**Summary:** Discussed new members, upcoming JuliaCon, JuliaHealth Birds of a Feather discussion on topics like neural decoding and OMOP tooling, managing logistics for Julia organizations, and JuliaHealth PR reviews.

**Keywords:** #brain #imaging #neural #decoding #collaboration #community #engagement

## Agenda

1. New member welcomes!

2. Planning JuliaHealth Birds of a Feather

   1. Topics?
   2. Facilitators?
   3. Creating actionable outcomes?

3. Open discussion on [Julia Orgs, How Do You Manage Logistics?](https://discourse.julialang.org/t/julia-orgs-how-do-you-manage-logistics/100430/11?u=thecedarprince)

4. Misc topics

  1. Julia for Health Informatics Research & Bridging community organizations

    1. Open Discussion on [The Graphs Ecosystem](https://discourse.julialang.org/t/the-graphs-ecosystem/99463?u=thecedarprince)

## Meeting Outcomes

### Short-Term Outcomes

- @Jacob Set-up HackMD to take notes going forward

  - Copy and paste meeting minutes over to JuliaHealth PR to update at end of meetings

### Long-Term Outcomes

- ACTION: Creating a template repository 

## Meeting Notes

- New members:

  - Zachary Christensen

    - Neuroimaging research

    - MD/PhD

      - Trying to finish this year!!!

    - Lots of background work like in JuliaData

    - Works on making Julia interface

- Announcement: JuliaCon about 1 month away!

  - We have our own track: biology and medicine
  - Many people working on different things

- JuliaHealth Birds of a Feather Discussion

  - Possible Topics:

    - Neural decoding 

      - Inspired by MATLAB: <http://www.readout.info> 
      - Sister organization: <https://julianeuro.github.io/packages>

    - OMOP Tooling for Real World Data

    - How to start collaborations?

      - Maybe grant collaborations?

      - Getting access to datasets

        - Coming up with different research questions

    - How can we integrate across the community?

      - What problem can we solve?

        - Become a community resource to point to packages

        - Don’t need to keep recreating or developing new packages

          - Packages could be applications built on top of a specific use case
          - Combining old packages in new ways

- Open discussion on [Julia Orgs, How Do You Manage Logistics?](https://discourse.julialang.org/t/julia-orgs-how-do-you-manage-logistics/100430/11?u=thecedarprince)

  - Have multiple persons part of the organizations

  - Sharing meeting documentation

    - Share Google Doc at the beginning or before a meeting in announcement

    - Publish notes on website publicly

      - PR to update the JuliaHealth website with new tab for meeting minutes

        - ACTION: Using HackMD to take notes going forward
        - Copy and paste meeting minutes over to JuliaHealth PR to update at end of meetings

  - Consistent APIs for JuliaHealth

    - Initial first pass with HealthBase.jl: <https://github.com/JuliaHealth/HealthBase.jl> 

    - As free as possible from niche

    - Could become quickly overwhelming or run risk of bikeshedding

    - ArrayInterface is a learning example in this context

    - Light dependency package is great with a well-described API 

    - How to move forward and get momentum

      - Without it turning into a mess

    - Common ontologies: <http://obofoundry.org> 

  - JuliaHealth PR Reviews

    - PR Checklist:

      - Purpose

      - Reduce cognitive load

    - JuliaHealth package forks: <https://github.com/JuliaCI/PkgTemplates.jl> 

    - ACTION: Creating a template repository 

# May 26 2023

## Meeting Summary

**In Attendance:** Jacob Zelko, Dilum Aluthge, Asher Wasserman, Fareeda Abdelazeez, Kyle Beggs

**Location:** Virtual 

**Summary:** First JuliaHealth community call to meet other Julians, learn how we can galvanize the Juliahealth Community, and open discussion on paths forward

**Keywords:** #data #analysis #hemodynamics #omop #machine #learning

## Agenda

1. Introductions

2. What people are using Julia for in health research

3. Selected topics and state within the Julia ecosystem:

   1. Observational Health
   2. Medical Imaging
   3. Machine Learning and Health
   4. Interoperability Standards
   5. Drug Discovery

4. Standard Interfaces

## Meeting Outcomes

### Short-Term Outcomes

- @Dilum finds out how to live stream JuliaHealth BoF

### Long-Term Outcomes



## Meeting Notes

1. Introductions

   1. Dilum Aluthge – MD/PhD Student Brown University (BCBI), PumasAI

      1. Julia Community Involvement

         1. Pkg
         2. General Registry
         3. Continuous Integration

      2. JuliaHealth and beyond

         1. Originally created JuliaHealth to bring people together in health
         2. BioJulia folks are a great source of inspiration for packages!

      3. Birds of a Feather!!! COME VISIT! – Friday July 28th, 4PM EST in Boston, MA!

   2. Asher Wasserman – Astronomy PhD, Data Scientist in BioTech

      1. Julia Community Involvement

         1. Differential Equations
         2. One off deployments

   3. Fareeda Abdelazeez – GSoC JuliaHealth (First GSoC Student!!!!!)

      1. Julia Community Involvement

         1. Observational Health tooling JuliaHealth!

   4. Kyle Beggs – Software Engineer in small Optics company, Finishing PhD in MechE

      1. Julia Community Involvement

         1. PDEs
         2. Hemodynamics research focus
         3. Take advantage of these tools for imaging, segmentation

2. What people are using Julia for in health research

   1. Asher: Cancer patient data

      1. PDFs and other data formats 

         1. CDA documents

      2. How to structure this ad hoc type of data into common data model

      3. Developing processes to automatically make these documents useful

      4. How do we clean the data to match actual reality

      5. How do we make this data actionable/useful

      6. Could match towards goals of OHDSI/observational health

         1. Analyses at population level?
         2. Outcome propensity scores?
         3. Patient phenotype development?

      7. Role of Julia:

         1. Mainly as a scripting language

         2. Supplement to a lot of SQL scripting (FunSQL discovered)

         3. Python is generally being deployed because of software devs

            1. How to not crash AWS, etc.

         4. Julia deployment for risk (?)

         5. Survival Analysis in Julia; lifelines in Python otherwise

   2. Kyle: Vascular Surgical Planning

      1. Unobvious on where to place graft, etc – educated guesses

      2. Creating a tool to simulate operations

      3. Why Julia?

         1. Existing tools are open source but really GUI-driven

         2. Integration across ecosystem would be even better for hemodynamics in Julia

         3. Give a base to simulate the mechanics involved with this

            1. JuliaFEM, etc. 

      4. Mesh list methods

         1. Point clouds
         2. Main application is within hemodynamics

   3. Fareeda: JuliaHealth GSoC Student

      1. Working on OMOP Common Data Model

      2. Standard model for observational health patient data

      3. Develop infrastructure of JuliaHealth to work with OMOP CDM data

         1. Improve DBConnector
         2. OMOPCDMCohortCreator.jl – add tooling
         3. OHDSIAPI.jl – creating interfaces for ATHENA/ATLAS

      4. Patient Level Prediction tooling

         1. Using MLJ algorithms

         2. Attempting to solve a research question

            1. Evaluate success of package

      5. Stretch goals:

         1. Cohort Quality and underlying data is “good”
         2. Build support for OBDC connections

   4. Overlap with other organizations

      1. Doesn’t happen in a vacuum

      2. Serving as a bridge between a bridge and a community between other groups

      3. What should be JuliaHealth?

         1. Bringing together people 

3. Selected topics and state within the Julia ecosystem:

   1. Observational Health
   2. Medical Imaging
   3. Machine Learning and Health
   4. Interoperability Standards
   5. Drug Discovery

4. Standard Interfaces


June 30th, 2023

Attending: 

Agenda:

1. New member welcomes!

2. Planning JuliaHealth Birds of a Feather

   1. Topics?
   2. Facilitators?
   3. Creating actionable outcomes?

3. Open discussion on [Julia Orgs, How Do You Manage Logistics?](https://discourse.julialang.org/t/julia-orgs-how-do-you-manage-logistics/100430/11?u=thecedarprince)

4. Misc topics

   1. Julia for Health Informatics Research & Bridging community organizations

      1. Open Discussion on [The Graphs Ecosystem](https://discourse.julialang.org/t/the-graphs-ecosystem/99463?u=thecedarprince)

Notes: 

- New members:

  - Zachary Christensen

    - Neuroimaging research

    - MD/PhD

      - Trying to finish this year!!!

    - Lots of background work like in JuliaData

    - Works on making Julia interface

- Announcement: JuliaCon about 1 month away!

  - We have our own track: biology and medicine
  - Many people working on different things

- JuliaHealth Birds of a Feather Discussion

  - Possible Topics:

    - Neural decoding 

      - Inspired by MATLAB: <http://www.readout.info> 
      - Sister organization: <https://julianeuro.github.io/packages>

    - OMOP Tooling for Real World Data

    - How to start collaborations?

      - Maybe grant collaborations?

      - Getting access to datasets

        - Coming up with different research questions

    - How can we integrate across the community?

      - What problem can we solve?

        - Become a community resource to point to packages

        - Don’t need to keep recreating or developing new packages

          - Packages could be applications built on top of a specific use case
          - Combining old packages in new ways

- Open discussion on [Julia Orgs, How Do You Manage Logistics?](https://discourse.julialang.org/t/julia-orgs-how-do-you-manage-logistics/100430/11?u=thecedarprince)

  - Have multiple persons part of the organizations

  - Sharing meeting documentation

    - Share Google Doc at the beginning or before a meeting in announcement

    - Publish notes on website publicly

      - PR to update the JuliaHealth website with new tab for meeting minutes

        - ACTION: Using HackMD to take notes going forward
        - Copy and paste meeting minutes over to JuliaHealth PR to update at end of meetings

  - Consistent APIs for JuliaHealth

    - Initial first pass with HealthBase.jl: <https://github.com/JuliaHealth/HealthBase.jl> 

    - As free as possible from niche

    - Could become quickly overwhelming or run risk of bikeshedding

    - ArrayInterface is a learning example in this context

    - Light dependency package is great with a well-described API 

    - How to move forward and get momentum

      - Without it turning into a mess

    - Common ontologies: <http://obofoundry.org> 

  - JuliaHealth PR Reviews

    - PR Checklist:

      - Purpose
      - Reduce cognitive load

    - JuliaHealth package forks: <https://github.com/JuliaCI/PkgTemplates.jl> 

    - ACTION: Creating a template repository 

