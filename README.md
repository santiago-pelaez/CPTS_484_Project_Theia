# Project Management Plan for Theia

Version 1.0 draft 1

Prepared by  
Anh Duong, Jim Kino, Santiago Pelaez, Gregory Shanygin  
CPTS 484  
September 20, 2026

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
5. User Manual and Quick Prototype

---

## Revision History

| Name | Date | Reason for Changes | Version |
|---|---|---|---|
| Preliminary Plan | 9/20/26 | initial draft | 1.0 draft 1 |

---

## 1. Introduction

### 1.1. Project Purpose, Objectives, and Success Criteria

Indoor navigation presents severe accessibility challenges for visually impaired individuals. Navigating indoor spaces requires high-precision location determination, route selection, directional orientation, turn recognition, obstacle avoidance, and destination verification. Research on indoor navigation supports treating localization, movement direction, landmarks, and uncertainty as distinct requirements concerns125.

Theia is a proposed smartphone application designed to address this problem by providing safe indoor navigation guidance through audio and haptic feedback3. Core system concerns include safety, accessibility, reliability, and route efficiency. The project will use the perceivable, operable, understandable, and robust principles of WCAG 2.2 as a design-review reference for mobile interaction4. The project also accounts for secondary stakeholders, including building administrators, sighted assistants and emergency personnel.

Phase I is a dedicated requirements-engineering study to decide precisely what Theia should do before any full software construction begins. The team will examine the preliminary product definition to discover and resolve requirements defects and produce a clarified World-Requirements-Specifications document.

To capture the complete user experience, the team will model four AS-IS/TO-BE scenario pairs, create an accessibility-conscious prototype, and draft a preliminary user manual tied directly to those scenarios. All work products will be validated together so that the scenarios, WRS, prototype, manual, and presentation describe one coherent system.

This plan organizes Phase I execution by assigning a point person for each work package, establishing review gates, recording project risks, and setting repository management standards. Phase I will be considered successful when all the required deliverables are complete, consistent, verified against peer-review checklists, stored in the team repository, and submitted with working links.

### 1.2. Project Deliverables

The following are the planned course deliverables for Phase I. They are limited to the items identified in the project specification.

| Deliverable | Delivery Date | Contents and Acceptance Target | Submission Location | Point Person |
|---|---|---|---|---|
| AS-IS/TO-BE scenarios and presentation | 10/18/2026 | Four AS-IS/TO-BE scenario pairs, analysis of the top priority scenario, prepared slides, and a recorded presentation. | Slides in repository. Unlisted video link submitted. | All members |
| WRS - Issues | 10/18/2026 | Issues found in the preliminary definition. | WRS document in repository and course submission. | Anh |
| WRS - Improved Understanding | 10/18/2026 | Clarified WRS. | WRS document in repository and course submission. | Santiago |
| Prototype and Preliminary User Manual | 10/18/2026 | Simple mock-up demonstrating the accessible interaction. Instructions for performing the TO-BE scenarios. | Repository and course submission. | Gregory |
| Phase I Project Plan | 09/20/2026 | Preliminary plan. | Repository and course submission. | Jim |
| AI Usage and Teamwork Report | 10/18/2026 | Evidence of AI use, revisions made by the team, and description of collaboration. | Repository and course submission. | All members |

### 1.3. Evolution and Change Control

This document is version-controlled in the team repository and the document itself. The preliminary version established the initial assignments and schedule. The team will update it when dates, ownership, dependencies, or deliverable content change. Each substantive update will include a version number, date, responsible person, and brief change description.

### 1.4. References

1. Fusco, Giovanni, and James M. Coughlan. “Indoor Localization for Visually Impaired Travelers Using Computer Vision on a Smartphone.” Proceedings of the 17th International Web for All Conference, Apr. 2020, pp. 1–11, https://doi.org/10.1145/3371300.3383345.
2. Legge, Gordon E., et al. “Indoor Navigation by People With Visual Impairment Using a Digital Sign System.” PLoS ONE, edited by Peter Bex, vol. 8, no. 10, Oct. 2013, p. e76783, https://doi.org/10.1371/journal.pone.0076783.
3. U.S. Department of Justice Civil Rights Division. “ADA Requirements - Effective Communication.” ADA.Gov, 18 Nov. 2022, https://www.ada.gov/resources/effective-communication/.
4. W3C. “Web Content Accessibility Guidelines (WCAG) 2.2.” Www.W3.Org, W3C, 12 Dec. 2024, https://www.w3.org/TR/WCAG22/.
5. Yang, Zhuorui, and Aura Ganz. “A Sensing Framework for Indoor Spatial Awareness for Blind and Visually Impaired Users.” IEEE Access, vol. 7, 2019, pp. 10343–52, https://doi.org/10.1109/access.2018.2886308.

### 1.5. Definitions and Acronyms

| Term or Acronym | Meaning and Definition |
|---|---|
| AI – Artificial Intelligence | Computational techniques that perform tasks normally associated with human reasoning. |
| AS-IS scenario | Description of how a user currently performs a task without Theia. |
| GORE – Goal Oriented Requirements Engineering | Requirements approach that derives objectives and requirements from stakeholder goals. |
| RE – Requirements Engineering | Systematic process of eliciting, analyzing, documenting, validating, and managing requirements. |
| RS – Requirements Specification | Specific, verifiable statement describing required system behavior or quality. |
| TO-BE Scenario | Description of how a user is expected to perform a task with Theia. |
| Traceability | Explicit links among Problems, Goals, Objectives and Requirements Specifications. |
| WRS – World Requirements Specifications | Document connecting the problem domain, stakeholder needs and detailed requirements. |
| Phase I | The initial understanding phase of the Theia project. |

---

## 2. Project Organization

### 2.1. Process Model

We will be using the prototyping model in this project, so we are able to quickly iterate through various concepts and ideas and iron out all the details for the final product. We will start by first going over all the details of the projects and identifying all requirements. Then we will start conceptualizing ideas and prototypes on how the app would work to fulfill all the requirements. Finally, we will develop a basic prototype to figure out any issues present in the prototype before iterating on the design. Through this process we will be able to iron out all the details and edge cases to satisfy all requirements.

### 2.2. Organizational Structure

The structure of the team will be equal, as all members will contribute equally to the project and its development as the developer. The members are Anh Duong, Jim Kino, Santiago Pelaez, Gregory Shanygin. Jim Kino will serve as the Team Liaison and Coordinator. As such the Liaison will handle communications between the project team and client. Communications within the team will be done through Discord and GitHub for prototyping.

### 2.3. Roles and Responsibilities

| Role | Description | Person |
|---|---|---|
| Team Liaison and Coordinator | Coordinates the project and meeting, and submits all deliverables | Jim |
| WRS Issues | Handles creating the issues for the WRS documents | Anh |
| WRS Improved Understanding and Traceability | Handles the improved understanding of issues | Santiago |
| Prototype and User Manual | Manages prototypes and user manuals | Gregory |
| Deliverables Creation | Writes all presentation, reports, and reviews work done | All |

---

## 3. Managerial Process Plans

### 3.1. Management objectives and priorities

Phase I’s objective is to ensure that all deliverables are completed on time and consistent throughout. This involves dividing the tasks among the group members and using Discord for communications and meetings.

The WRS paper is going to be of utmost importance since this accounts for most of the marks of Phase I. Also, reviewing all parts of the paper will be done collectively.

### 3.2. Assumptions, dependencies, and constraints

The team assumes that all members will have access to Canvas, Discord, the shared documents, and the Git repository.

The project depends on the Preliminary Definition, course templates, and instructions provided by the professor. Phase I mainly focuses on requirements engineering, so the project plan will focus on course deliverables, task distribution, and scheduling rather than unnecessary software development documents.

### 3.3. Risk management

During the first phase, the team will analyze and discuss potential risks associated with the project within the scope of team meetings and Discord. Risks will be evaluated depending on the probability of their occurrence and the potential effect on the project.

In case the risk happens, the team will think of possible measures and make adjustments to the tasks and deadlines accordingly. Typical risks include the failure to meet deadlines, inconsistencies between sections, team member availability, miscommunication of the requirements, and mistakes of AI-generated content.

Each individual from the team should bring up any issues right away. Major risks will be discussed at regular meetings of the team and necessary adjustments will be made.

| Risk | Likelihood / Impact | Description |
|---|---|---|
| Missing deadlines | Medium / High | A section may not be completed early enough for review. |
| Inconsistent sections | Medium / High | Work from different members may not match. |
| Team member unavailable | Medium / Medium | Scheduling conflicts may delay work. |
| Misunderstanding requirements | Medium / High | The team may interpret project instructions incorrectly. |
| Incorrect AI output | Medium / High | AI-generated content may contain errors and must be reviewed. |

The course requires teams to review and refine AI-generated material before using it in the final submission.

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

The team will use members’ personal computers for document preparation, repository work, communication, and prototype creation. Because Phase I does not include production implementation, there is no separate operational or deployment environment. The prototype will be reviewed through walkthroughs and demonstrations on the available computers or mobile devices.

### 4.2. Software documentation

The team will use the WRS and Project Management Plan templates for documentation. Phase I documentation will include the WRS Issues, WRS Improved Understanding, AS-IS/TO-BE scenarios, presentation slides, prototype and preliminary user manual, project plan, and AI Usage and Teamwork Report. All documents will be reviewed by the team, stored in the team repository, and submitted through Canvas as required.

---

## 5. User Manual and Quick Prototype

### Theia Preliminary User Manual

1) Voice and Audio permissions are turned on by phone

- Vocal directions, or using vibrations (two quick buzzes left, one quick buzz right, one long buzz for arrival/started, 3 quick buzzes for hazard, arrival will have a jig tone)

```text
================================================================================
SCREEN 1: IDLE / DESTINATION SELECTION (HOME SCREEN)
================================================================================
Screen Reader Accessibility Order:
  [Focus 1] Status Bar (Indoor Location & Signal)
  [Focus 2] Voice Input Target (Top 60% of Display)
  [Focus 3] Quick Preset: Nearest Restroom (Bottom-Left 20%)
  [Focus 4] Quick Preset: Emergency Exit (Bottom-Right 20%)
 
+------------------------------------------------------------------------------+
| [LOCATION STATUS] Dana Hall, Floor 2 | Bluetooth Beacons: Active             |
+------------------------------------------------------------------------------+
|                                                                              |
|                                                                              |
|                        TAP ANYWHERE OR HOLD VOLUME UP                         |
|                                                                              |
|                                 (( 🎙️ ))                                     |
|                                                                              |
|                       "Where would you like to go?"                          |
|                                                                              |
|                [ High-Contrast: 72pt Bold White on True Black ]              |
|                                                                              |
|                                                                              |
+---------------------------------------+--------------------------------------+
| [BUTTON: QUICK PRESET 1]              | [BUTTON: QUICK PRESET 2]             |
|                                       |                                      |
|            🚻 NEAREST RESTROOM         |            🚨 EMERGENCY EXIT         |
|                                       |                                      |
|   (Accessibility Label: "Navigate     |   (Accessibility Label: "Direct      |
|    to closest ADA restroom")          |    route to nearest exterior exit")  |
+---------------------------------------+--------------------------------------+
 
Audio Readout (TTS):
"Theia ready. Currently on the second floor of Dana Hall. Tap the screen to speak a destination."
 
Haptic Signal Output:
Single subtle pulse (50ms) on screen load to confirm app readiness.
```

2) Step-by-Step TO-BE Scenarios

**Destination/Navigation**

- Press up/down volume button simultaneously to activate new voice
- Enter address/building No as well as room number
- Give either floor nav directions or tell to ask concierge
- Have phone camera facing on with phone on chest
- Follow cues until destination with one signal long buzz and audio music

```text
================================================================================
SCREEN 2: ROUTE CONFIRMATION & INITIALIZATION
================================================================================
Screen Reader Accessibility Order:
  [Focus 1] Route Summary Header
  [Focus 2] Path Details & Waypoints
  [Focus 3] Confirm Navigation Button (Double-tap anywhere)
  [Focus 4] Cancel / Change Destination
 
+------------------------------------------------------------------------------+
| [ROUTE CONFIRMATION] Dana Hall -> Room 214                                   |
+------------------------------------------------------------------------------+
|                                                                              |
|                              DESTINATION FOUND                               |
|                                                                              |
|                                  ROOM 214                                    |
|                             Computer Science Lab                             |
|                                                                              |
|  --------------------------------------------------------------------------  |
|  * Distance: 120 Feet                                                        |
|  * Elevation: Same Level (Floor 2)                                           |
|  * Turns: 2 Turns (1 Right, 1 Left)                                          |
|  * Obstacles Reported: None                                                  |
|  --------------------------------------------------------------------------  |
|                                                                              |
|                     DOUBLE-TAP WITH TWO FINGERS TO START                     |
|                                                                              |
+------------------------------------------------------------------------------+
| [CANCEL / RE-TRY] Swipe Down or Say "Cancel"                                 |
+------------------------------------------------------------------------------+
 
Audio Readout (TTS):
"Route to Room 214 calculated. Total distance is 120 feet with two turns on the current floor. Double-tap to begin guidance."
 
Haptic Signal Output:
One medium pulse (150ms) confirming voice destination recognized.
```

3) Re-Routing, Hazards

- Alert Pulse is activated if anything is noted
- Paused
- Listen to detour voice nav/app waits to give next vibration
- Proceed once the reroute confirmation buzz is received.

```text
================================================================================
SCREEN 3: DYNAMIC HAZARD DETECTED & REROUTING
================================================================================
Screen Reader Accessibility Order:
  [Focus 1] Hazard Warning Banner
  [Focus 2] Detour Action Description
  [Focus 3] Confirm Detour Button
 
+------------------------------------------------------------------------------+
| [ALERT] PATHWAY OBSTRUCTED                             | Dana Hall, Floor 2  |
+------------------------------------------------------------------------------+
|                                                                              |
|                                     ⚠️                                       |
|                                                                              |
|                             STOP: OBSTACLE AHEAD                             |
|                                                                              |
|                             Custodial Maintenance                            |
|                                                                              |
|  --------------------------------------------------------------------------  |
|                      (( 📳 • • • • • • • • ))                                |
|                 HAPTIC: RAPID INTERMITTENT WARNING                           |
|  --------------------------------------------------------------------------  |
|                                                                              |
|                          RECALCULATING SAFE ROUTE...                         |
|                    "Turn 180 degrees to take East Hallway"                   |
|                                                                              |
+------------------------------------------------------------------------------+
| [AWAITING SAFE ORIENTATION: Turn around slowly until haptic buzz aligns]     |
+------------------------------------------------------------------------------+
 
Audio Readout (TTS):
"Caution. Pathway blocked by maintenance ahead. Please stop. Recalculating route via the East Hallway. Turn around completely."
 
Haptic Signal Output:
Rapid intermittent vibration bursts (100ms on / 50ms off) to signal a halt, followed by steady directional beaconing once aligned[cite: 1].
```

4) Activating Emergency Evacuation Mode

- Triple-tap the lower-right quadrant of the screen or press both volume buttons simultaneously.
- Theia immediately overrides active routes and maps the closest accessible emergency exit.
- High-priority audio prompts and directional pulses steer you to the nearest fire/emergency stairwell or exterior exit
- Your indoor floor location is automatically broadcast to emergency personnel or building administration.

```text
================================================================================
SCREEN 4: EMERGENCY EVACUATION MODE
================================================================================
Screen Reader Accessibility Order:
  [Focus 1] Emergency State Indicator
  [Focus 2] Primary Escape Vector Directions
  [Focus 3] First Responder Broadcast Status
  [Focus 4] Cancel Emergency Button (Hold for 5s)
 
+------------------------------------------------------------------------------+
| [EMERGENCY ACTIVE] Dana Hall - 2nd Floor, Sector B                           |
+------------------------------------------------------------------------------+
|                                                                              |
|                                    🚨 🚪                                     |
|                                                                              |
|                           EVACUATION ROUTE ACTIVE                            |
|                                                                              |
|                         STAIRWELL 'B' (EXIT TO GROUND)                       |
|                                                                              |
|                             PROCEED 45 FEET AHEAD                            |
|                                                                              |
|  --------------------------------------------------------------------------  |
|                          (( 📳 — • — • — • ))                                |
|                 HAPTIC: CONTINUOUS METRONOME CADENCE                         |
|  --------------------------------------------------------------------------  |
|                                                                              |
| [BEACON STATUS] Location broadcasted to building dispatch and 911 responders |
|                                                                              |
+------------------------------------------------------------------------------+
| [FALSE ALARM: Press and hold volume down for 5 seconds to cancel]            |
+------------------------------------------------------------------------------+
 
Audio Readout (TTS):
"Emergency evacuation active. Proceed straight for 45 feet toward Stairwell B. Your location has been shared with emergency personnel."[cite: 1]
 
Haptic Signal Output:
Continuous rhythmic metronome pulses to anchor the user's forward walking tempo toward the exit[cite: 1].
```
