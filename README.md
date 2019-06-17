# OntoSyllabus

The syllabus is a relevant document to organize how the teaching-learning process will be carried out during anacademic course in Higher Education Institutions (HEI). Usually, this document is written in a human-readable format  that  not  enable  automatic  processing  through  intelligent  services  to  support  teaching  and  learning. Therefore, we created OntoSyllabus, an ontology for the semantic representation of syllabuses. We applyed the NeOn Methodology and Waterfall Life Cycle Model. OntoSyllabus will allow the comprehension of a syllabus for both: machines and humans. It will facilitate the interchange of the data between different services and applications. The semantic description was created based on the results of our three previous studies which helped us to determinate the terms and relations in OntoSyllabus.

<p align="center">
  <img src="https://user-images.githubusercontent.com/43136359/56052216-b25a6900-5d05-11e9-8fbe-60f99f25c257.PNG">
</p>

## Waterfall Life Cycle Model
To develop an ontology it is necessary to follow a life cycle model. A life cycle is a process divided into phases in which a product is developed. The waterfall model was selected because it is recommended in projects with a short duration. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/43136359/56053398-d5d2e300-5d08-11e9-9a4a-8297048ca761.PNG">
</p>

## NeOn Methodology
NeOn is a methodology that supports to build ontologies and ontology networks. It is a new trend that is the opposite of building new ontologies from scratch. The NeOn methodology defines nine scenarios. We used Scenario 3 and we combined it with Scenario 1 as is the suggestion of the methodology's author. We fit in Scenario 3 because there are a variety of ontologies available on the Web, in the academic context which can be reused for building an ontology for syllabuses.

<p align="center">
  <img src="https://user-images.githubusercontent.com/43136359/56053061-e171da00-5d07-11e9-9cf3-04d33bc2e5ec.PNG">
</p>

## OntoSyllabus Creation
NeOn methodology proposes a set of activities to carry out the building of an ontology. In the next graph, we show the activities that we followed in the syllabus ontology creation.

<p align="center">
  <img src="https://user-images.githubusercontent.com/43136359/56059536-25b9a600-5d19-11e9-9f3b-375242b3f5f2.PNG">
</p>

## Ontology Requirements Specification Document (ORCID)
|   | Ontology Requirements Specification Document                                                                                                                                                                                                                                                                          |
|---|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Purpose Provide a consensual knowledge model of syllabus domain. This model is a compilation of the main terms and objects for this domain and could be used by HEI.                                                                                                                                                  |
| 2 | Scope The level of granularity is directly related to the competency questions and terms identified.                                                                                                                                                                                                                  |
| 3 | Implementation Language Ontology Web Language (OWL-DL) through the software Protégé.                                                                                                                                                                                                                                  |
| 4 | Intended End-Users Students, instructors, HEI staff.                                                                                                                                                                                                                                                                  |
| 5 | Intended Uses Monitoring and control of the syllabus.  Homologation of studies. Subject recommendation to help students to explore and select courses in the context of mobility programs. Learning paths (sequence) generation.  Manage an integrated format of the syllabus.  Measure the progress of the students. |
| 6 | Non-Functional Requirements The ontology will be written in English. The elements that compose the ontology must be appropriately documented to allow subsequent maintenance or reuse in derivative works.                                                                                                            |
| 7 | Functional Requirements Groups of Competency Question and Answer                                                                                                                                                                                                                                                                     |
| Question                                                                         | Answer                                                                     |
|----------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| What are the information resources available  to teach or learn the course?      | Bibliography resources, learning resources.                                |
| What are the subjects of the course?                                             | Table of contents, topics, concepts.                                       |
| Which are the assessments and their deadlines?                                   | Assessment type, number of assessments, deadline.                          |
| In which classroom the course is dictated?                                       | Classroom number, classroom type.                                          |
| Who is the instructor?                                                           | Name, department, university, academic degree, email, telephone.           |
| Where can I find help with the subjects or  with any necessity that comes about? | Study strategies, help.                                                    |
| Which are the requisites for taking the  course?                                 | Requirements, prerequisites.                                               |
| How   many   hours and credits have the  course?                                 |  Number of credits, lecture hours, lab hours, autonomous hours,  workload. |
| How is the course methodology?                                                   | Description.                                                               |
| Which are the learning outcomes of the course?                                   | Competencies, learning objectives, goal statement, Bloom verb.             |
| Who creates and approves the syllabus?                                           | Creator, reviewer.                                                         |
| Are there some policies about the course?                                        | Attendance policy, accessibility, drop out, policy, qualification  policy. |
## OntoSyllabus Documentation
The documentation of OntoSyllabus is available in [this link.](https://jachicaiza.github.io/ontologyDoc/)

## OntoSyllabus OWL and RDF files
The OWL and RDF files of OntoSyllabus is available [here.](https://github.com/mayetapia/ontosyllabus/tree/master/Ontology)








