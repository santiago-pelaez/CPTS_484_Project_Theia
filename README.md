# Theia Software Project Management Plan

**Version 1.2 Final**

CPT_S 484

Prepared by  
Anh Duong, Jim Kino, Santiago Pelaez, Gregory Shanygin

October 18, 2026

---

## Table of Contents

1. Introduction
   1. Project Purpose, Objectives, and Success Criteria
   2. Project Deliverables
   3. Evolution and Change Control
   4. References
   5. Definitions and Acronyms
2. Project Organization
   1. Process Model
   2. Organizational Structure
   3. Roles and Responsibilities
3. Managerial Process Plans
   1. Management objectives and priorities
   2. Assumptions, dependencies, and constraints
   3. Risk management
4. Technical Process Plans
   1. Methods, tools, and techniques
   2. Software documentation

---

## Revision History

| Name | Date | Reason for Changes | Version |
|---|---|---|---|
| Preliminary Plan | 9/20/26 | initial draft | 1.0 draft 1 |
| Minor updates | 9/25/26 | Updated based on feedback | 1.1 |
| Final Project Plan | 10/18/26 | Finalize the plan | 1.2 |

---

## 1. Introduction

### 1.1. Project Purpose, Objectives, and Success Criteria

Indoor navigation presents severe accessibility challenges for visually impaired individuals. Navigating indoor spaces requires high-precision location determination, route selection, directional orientation, turn recognition, obstacle avoidance, and destination verification. Research on indoor navigation supports treating localization, movement direction, landmarks, and uncertainty as distinct requirements concerns.

Theia is a proposed smartphone application designed to address this problem by providing safe indoor navigation guidance through audio and haptic feedback. Core system concerns include safety, accessibility, reliability, and route efficiency. The project will use the perceivable, operable, understandable, and robust principles of WCAG 2.2 as a design-review reference for mobile interaction. The project also accounts for secondary stakeholders, including building administrators, sighted assistants, and emergency personnel.

Phase I is a dedicated requirements-engineering study to decide precisely what Theia should do before any full software construction begins. The team will examine the preliminary product definition to discover and resolve requirements defects and produce a clarified World-Requirements-Specifications (WRS) document.

To capture the complete user experience, the team will model four AS-IS/TO-BE scenario pairs, create an accessibility-conscious prototype, and draft a preliminary user manual tied directly to those scenarios. All work products will be validated together so that the scenarios, WRS, prototype, manual, and presentation describe one coherent system.

This plan organizes Phase I execution by assigning a point person for each work package, establishing review gates, recording project risks, and setting repository management standards. Phase I will be considered successful when all the required deliverables are complete, consistent, verified against peer-review checklists, stored in the team repository, and submitted with working links.

### 1.2. Project Deliverables

The following are the planned course deliverables for Phase I. They are limited to the items identified in the project specification.

| Deliverable | Delivery Date | Contents and Acceptance Target | Point Person | Submission Location |
|---|---|---|---|---|
| AS-IS/TO-BE scenarios and presentation | 10/18/2026 | Four AS-IS/TO-BE scenario pairs, analysis of the top priority scenario, prepared slides, and a recorded presentation. | Gregory | AS-IS/TO-BE scenarios and presentation |
| WRS - Issues | 10/18/2026 | Issues found in the preliminary definition. | Anh | WRS - Issues |
| WRS - Improved Understanding | 10/18/2026 | Clarified WRS. | Santiago | WRS - Improved Understanding |
| Prototype and Preliminary User Manual | 10/18/2026 | Simple mock-up demonstrating the accessible interaction. Instructions for performing the TO-BE scenarios. | Gregory | Prototype and Preliminary User Manual |
| Phase I Project Plan | 10/18/2026 | Final Phase I Project Plan. | Jim | Phase I Project Plan |
| AI Usage and Teamwork Report | 10/18/2026 | Evidence of AI use, revisions made by the team, and description of collaboration. | All members | AI Usage and Teamwork Report |

### 1.3. Evolution and Change Control

This document is version-controlled in the team repository. The initial version established the initial assignments and schedule. The team will update it when dates, ownership, dependencies, or deliverable content change. Each substantive update will include a version number, date, responsible person, and brief change description.

### 1.4. References

1. Fusco, Giovanni, and James M. Coughlan. "Indoor Localization for Visually Impaired Travelers Using Computer Vision on a Smartphone." Proceedings of the 17th International Web for All Conference, Apr. 2020, pp. 1–11, https://doi.org/10.1145/3371300.3383345.
2. Legge, Gordon E., et al. "Indoor Navigation by People With Visual Impairment Using a Digital Sign System." PLoS ONE, edited by Peter Bex, vol. 8, no. 10, Oct. 2013, p. e76783, https://doi.org/10.1371/journal.pone.0076783.
3. U.S. Department of Justice Civil Rights Division. "ADA Requirements - Effective Communication." ADA.Gov, 18 Nov. 2022, https://www.ada.gov/resources/effective-communication/.
4. W3C. "Web Content Accessibility Guidelines (WCAG) 2.2." Www.W3.Org, W3C, 12 Dec. 2024, https://www.w3.org/TR/WCAG22/.
5. Yang, Zhuorui, and Aura Ganz. "A Sensing Framework for Indoor Spatial Awareness for Blind and Visually Impaired Users." IEEE Access, vol. 7, 2019, pp. 10343–52, https://doi.org/10.1109/access.2018.2886308.

### 1.5. Definitions and Acronyms

| Term or Acronym | Meaning and Definition |
|---|---|
| AI - Artificial Intelligence | Computational techniques that perform tasks normally associated with human reasoning. |
| AS-IS scenario | Description of how a user currently performs a task without Theia. |
| GORE | Goal Oriented Requirements Engineering. |
| RE - Requirements Engineering | Systematic process of eliciting, analyzing, documenting, validating, and managing requirements. |
| RS - Requirements Specification | Specific, verifiable statement describing required system behavior or quality. |
| TO-BE Scenario | Description of how a user is expected to perform a task with Theia. |
| Traceability | Explicit links among Problems, Goals, Objectives, and Requirements Specifications. |
| WRS | World Requirements Specifications. |

---

## 2. Project Organization

### 2.1. Process Model

We will be using an iterative requirements-engineering process. Because Phase I focuses solely on requirements elicitation and documentation, we will start by reviewing the preliminary definition and identifying all necessary requirements. Then, we will draft the WRS and conceptualize low-fidelity mockups to explore how the app will fulfill those requirements. Finally, we will conduct peer reviews to iron out any inconsistencies before finalizing the deliverables. Through this iterative process, we will refine the details and edge cases to ensure the requirements accurately capture the system vision.

### 2.2. Organizational Structure

The structure of the team will be equal, as all members will contribute equally to the project as requirements analysts and documentation authors. The members are Anh Duong, Jim Kino, Santiago Pelaez, and Gregory Shanygin. Jim Kino will serve as the Team Liaison and Coordinator. As such, the Liaison will handle communications between the project team and the instructor. Communications within the team will be done through Discord and GitHub for version control.

GitHub link: https://github.com/santiago-pelaez/CPTS_484_Project_Theia/tree/main

### 2.3. Roles and Responsibilities

| Role | Description | Person |
|---|---|---|
| Team Liaison and Coordinator | Coordinates the project and meetings, and submits all deliverables. | Jim |
| WRS - Issues | Handles creating the issues for the WRS documents. | Anh |
| WRS - Improved Understanding | Handles improved understanding of issues and traceability. | Santiago |
| Prototype and User Manual | Manages prototypes and user manuals. | Gregory |
| AS-IS/TO-BE Scenarios | Leads scenario development and presentation slides. | Gregory |
| Final Review and Integration | Write presentation/reports and review the final work. | All |

---

## 3. Managerial Process Plans

### 3.1. Management objectives and priorities

Phase I's objective is to ensure that all deliverables are completed on time and consistent throughout. This involves dividing the tasks among the group members and using Discord for communications and meetings.

The WRS paper is going to be of utmost importance since this accounts for most of the marks of Phase I. Reviewing all parts of the paper will be done collectively to ensure coherence.

### 3.2. Assumptions, dependencies, and constraints

The team assumes that all members will have access to Canvas, Discord, the shared documents, and the Git repository.

The project depends on the Preliminary Definition, course templates, and instructions provided by the professor. Phase I mainly focuses on requirements engineering, so the project plan will focus on course deliverables, task distribution, and scheduling rather than unnecessary software development documents.

### 3.3. Risk management

During the first phase, the team will analyze and discuss potential risks associated with the project within the scope of team meetings and Discord. Risks will be evaluated depending on the probability of their occurrence and the potential effect on the project.

In case the risk happens, the team will think of possible measures and make adjustments to the tasks and deadlines accordingly. Each individual from the team should bring up any issues right away. Major risks will be discussed at regular meetings of the team and necessary adjustments will be made.

| Risk | Likelihood / Impact | Description |
|---|---|---|
| Missing deadlines | Medium / High | A section may not be completed early enough for review. |
| Inconsistent sections | Medium / High | Work from different members may not match. |
| Team member unavailable | Medium / Medium | Scheduling conflicts may delay work. |
| Misunderstanding requirements | Medium / High | The team may interpret project instructions incorrectly. |
| Incorrect AI output | Medium / High | AI-generated content may contain errors and must be reviewed. |

---

## 4. Technical Process Plans

### 4.1. Methods, tools, and techniques

The team will use the following Phase I methods and tools.

- **Requirements methods:** stakeholder analysis, requirements elicitation, AS-IS/TO-BE scenario analysis, structured issue analysis, goal and objective decomposition, and traceability from Problems to Goals, Objectives, and Requirement Specifications.
- **Analysis and review methods:** requirements inspection, peer review, checklist-based review, accessibility-focused walkthroughs, terminology checks, and cross-artifact consistency reviews.
- **Modeling methods:** scenario models, requirements traceability tables, and other analysis models required by the course materials. Models will be used to clarify the problem and requirements; they will not be treated as unnecessary implementation documentation.
- **Collaboration tools:** Discord for team communication and meetings, Canvas for course instructions and submissions, and the team Git repository for version control and shared project artifacts.
- **Documentation tools:** the course-provided project-plan and WRS templates, word-processing software for documents, and presentation software for AS-IS/TO-BE slides.
- **Prototype tools:** a wireframing tool, presentation software, or a simple mock-up tool may be used to demonstrate the intended accessible interaction. The prototype is for requirements exploration and demonstration, not production implementation.
- **Presentation tools:** the team will record the presentation using an available recording tool and submit an unlisted video link if required by the course instructions.

The team will use members' personal computers for document preparation, repository work, communication, and prototype creation. The prototype will be reviewed through walkthroughs and demonstrations on the available computers or mobile devices.

### 4.2. Software documentation

The team will use the WRS and Project Management Plan templates for documentation. Phase I documentation will include the WRS Issues, WRS Improved Understanding, AS-IS/TO-BE scenarios, presentation slides, prototype and preliminary user manual, project plan, and AI Usage and Teamwork Report. All documents will be reviewed by the team, stored in the team repository, and submitted through Canvas as required.
