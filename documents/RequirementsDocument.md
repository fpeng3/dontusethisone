# Software Requirements and Use Cases

## Your Project Title
--------
Prepared by:

* `<Cristian>`,`<Pineda Delgado>`
* `<Aiden>`,`<Damaso>`
* `<Fulin>`,`<Peng>`
* `<Nathanael>`,`<Chao>`

---

**Course** : CS 3733 - Software Engineering

**Instructor**: Sakire Arslan Ay

---

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Requirements Specification](#2-requirements-specification)
  - [2.1 Customer, Users, and Stakeholders](#21-customer-users-and-stakeholders)
  - [2.2 User Stories](#22-user-stories)
  - [2.3 Use Cases](#23-use-cases)
- [3. User Interface](#3-user-interface)
- [4. Product Backlog](#4-product-backlog)
- [4. References](#4-references)
- [Appendix: Grading Rubric](#appendix-grading-rubric)

<a name="revision-history"> </a>

## Document Revision History

| Name | Date | Changes | Version |
| ------ | ------ | --------- | --------- |
|Revision 1 |2024-11-07 |Initial draft | 1.0        |
|      |      |         |         |
|      |      |         |         |

----
# 1. Introduction

Provide a short description of the software being specified. Describe its purpose, including relevant benefits, objectives, and goals. <br>

This application has the purpose of matching students with research positions. The objective is that professors who need help with research can post a position, a student can apply, and the professor can accept or deny them. The goal is that professors can see the qualifications of each student to find the best fit for their position. The benefits of this application would be that it would act as one unified hub the connects students and professors with similar specialties. 

----
# 2. Requirements Specification

This section specifies the software product's requirements. Specify all of the software requirements to a level of detail sufficient to enable designers to design a software system to satisfy those requirements, and to enable testers to test that the software system satisfies those requirements. <br>
Teachers and Students will both be able to log into this application in order to post research positions and apply to said positions respectively. The following subsections provide further requirement details. 

## 2.1 Customer, Users, and Stakeholders
_A brief description of the customer, stakeholders, and users of your software._

- General user: either a student or professor
- Students who want to find research opportunities
- Professors (Faculty) who want to find students to help with their research

----
## 2.2 User Stories
This section will include the user stories you identified for your project. Make sure to write your user stories in the form : 
"As a **[Role]**, I want **[Feature]** so that **[Reason/Benefit]** "

1. As a **student**, I would like to **input relevant information about myself**, so that I can be matched to appropriate professors (Manage Profile)
2. As a **student**, I would like to **be able to apply for lab positions**, so that I can participate (View Positions)
3. As a **student**, I want to **be able to cancel my applications** in case **I change my mind**. (Delete Request)
  
4. As a **general user**, I would like to **create a profile**, so that I can log in/out (Authentication)
5. As a **general user**, I would like to **log in and log out using my school credentials or single-sign-on** (Authentication)
6. As a **general user**, I want to **be able to edit my profile**, in case I want to make changes (Manage Profile)
7. As a **general user**, I would like to **be able to view the available list of positions** . (View Positions)
8. As a **student**, I would like to **be able to filter the available list of positions**. (View Positions)
9. As a **professor**, I would like to **be able to filter the list of applicants**. (View Requests)

10. As a **professor**, I want to **be able to create positions**, so that students can apply to them (Manage Positions)
11. As a **professor**, I want to **be able accept and reject students from positions I offered** (View Requests)
12. As a **professor**, I want to **be able to view student profiles**, so that I can see their qualifications (View Requests)
13. As a **professor**, I want to **be able to view pending requests from my profile page**, so I can see who wants the positions I am offering (View Requests)
14. As a **professor**, I want to **be able to edit positions**, so that I can make changes to them (Manage Positions)
15. As a **professor**, I want to **be able to delete positions**, in case they are already full (Manage Positions) 
16. As a **professor**, I want to **be able to remove students from a position**, in case plans change (Delete Request)

----
## 2.3 Use Cases

-- Manage Profile (Cristian)
-- View Positions (Fulin)
-- Delete Request (Nathanael)
-- Authentication (Cristian)
-- View Requests (Fulin)
-- Manage Positions (Aiden)

This section will include the specification for your project in the form of use cases. 

Group the related user stories and provide a use case for each user story group. You don't need to draw the use-case diagram for the use cases; you will only provide the textual descriptions.  **Also, you don't need to include the use cases for "registration" and "login" use cases for both student and faculty users.**

  * First, provide a short description of the actors involved (e.g., regular user, administrator, etc.) and then follow with a list of the use cases.
  * Then, for each use case, include the following:

    * Name,
    * Participating actors,
    * Entry condition(s) (in what system state is this use case applicable),
    * Exit condition(s) (what is the system state after the use case is done),
    * Flow of events (how will the user interact with the system; list the user actions and the system responses to those),
    * Alternative flow of events (what are the exceptional cases in the flow of events and they will be handles)
    * Iteration # (which sprint do you plan to work on this use case) 

Each use case should also have a field called "Iteration" where you specify in which iteration you plan to implement this feature.

You may use the following table template for your use cases. Copy-paste this table for each use case you will include in your document. 

| Use case # 1      |   |
| ------------------ |--|
| Name              | "enter your reponse here"  |
| Participating actor  | "enter your reponse here"  |
| Entry condition(s)     | "enter your reponse here"  |
| Exit condition(s)           | "enter your reponse here"  |
| Flow of events | "enter your reponse here"  |
| Alternative flow of events    | "enter your reponse here"  |
| Iteration #         | "enter your reponse here"  |



| Use case # 2     |   |
| ------------------ |--|
| Name              | Delete Application (Student) or Delete Research Position (Faculty)   |
| Participating actor  |  Professors and Students  |
| Entry condition(s)     | Post to be deleted exists  |
| Exit condition(s)           | Post is successfully deleted  |
| Flow of events | 1.  User selects their "delete post." <br> 2.  System asks user for confirmation to delete post. <br> 3. User confirms deletion. <br> - System deletes post.     |
| Alternative flow of events    | - If the user is a teacher, posts to be deleted will be research positions <br> - If the user is a student, the posts to be deleted will be applications to research positions <br> - At step 2, the user has the option to click a post to get more detailed information before they delete <br> - At step 3, the user choose "cancel" option to stop use case   |
| Iteration #         | 1  |


----
# 3. User Interface

Here you should include the sketches or mockups for the main parts of the interface.
You may use Figma to design your interface:

  Example image. The image file is in the `./images` directory.
  <kbd>
      <img src="images/figma.jpg"  border="2">
  </kbd>
  
----
# 4. Product Backlog

Here you should include a link to your GitHub repo issues page, i.e., your product backlog. Make sure to create an issue for each user story.  

----
# 5. References

Cite your references here.

For the papers you cite give the authors, the title of the article, the journal name, journal volume number, date of publication and inclusive page numbers. Giving only the URL for the journal is not appropriate.

For the websites, give the title, author (if applicable) and the website URL.

----
----
# Appendix: Grading Rubric
(Please remove this part in your final submission)

These is the grading rubric that we will use to evaluate your document. 

| Max Points  | **Content** |
| ----------- | ------- |
| 4          | Do the requirements clearly state the customers’ needs? |
| 2          | Do the requirements avoid specifying a design (note: customer-specified design elements are allowed)? |
| | |  
|    | **Completeness** |
| 14 | Are user stories complete? Are all major user stories included in the document?  |
| 5 | Are user stories written in correct form? | 
| 14 |  Are all major use cases (except registeration and login) included in the document? |
| 15 | Are use cases written in sufficient detail to allow for design and planning? Are the "flow of events" in use case descriptions written in the form of "user actions and system responses to those"? Are alternate flow of events provided (when applicable)? | 
| 6 |  Are the User Interface Requirements given with some detail? Are there some sketches, mockups?  |
| | |  
|   | **Clarity** |
| 5 | Is the document carefully written, without typos and grammatical errors? <br> Is each part of the document in agreement with all other parts? <br> Are all items clear and not ambiguous? |
| | |
|**65**|**TOTAL**|


