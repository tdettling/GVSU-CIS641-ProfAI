# Overview
This odcument sevres as a cenetral location for all artifacts within this application. 


# Software Requirements
## Overview
The purpose of this document is to record and maintain requirements specification for ProfAI. Requirements are sorted by type: Functional and Non-Functional. 

## Functional Requirements

1. Account
    1. The system shall require users to enter in an email address when creating an account. 
    2. The system shall require users to enter in a password when creating an account. 
    3. The system shall require users to enter in their first and last name when creating an account. 
    4. The system shall allow users to delete their API key on the 'Account' page. 
    5. The system shall allow users to add their API key on the 'Account' page. 
    6. The system shall prompt users to enter a valid API key for HeyGen after account creation. 

2. Avatar Importing with HeyGen
    1. The system shall require users to create an account with their first name, last name, and email address before they can view avatars.
    2. The system shall require the user to create an API key from HeyGen before viewing their list of avatars.
    3. The system shall allow the user to view their list of avatar names. 
    4. The system shall display a preview image of each of the available avatars for selection. 
    5. The system shall allow users to select an avatar for video generation. 

3. Slide Generation
    1. The system shall generate slides based off an approved script only.
    2. The system shall generate a minimum of 4 slides in a slideshow. 
    3. The system shall allow a maximum for 25 slides per slideshow generated. 
    4. The system shall allow a maximum of 7 bullet points per slide on a generated slideshow. 
    5. The system shall allow users to download the slideshow after generation. 
    6. The system shall allow users to adjust the content of generated slides.
    7. The system shall allow users to resubmit a slideshow for approval. 
    8. The system shall automatically download a generated slideshow after a user's approval. 

4. Voice Generation
    1. The system shall display a list of avatar voice names upon a user selecting the 'Voices' tab. 
    2. The system shall display a list of avatar voice images upon a user selecting the 'Voices' tab. 
    3. The system shall allow users to select a voice different from an avatar's automatic voice for video creation. 
    4. The system shall not allow the change of an avatar voice after the video is created. 
    5. The system shall allow users to change the selection of a voice before a video has een generated. 

5. Script Generation
    1. The system shall prompt users for content to generate a script. 
    2. The system shall allow users to reject a generated script. 
    3. The system shall allow users to edit a rejected script.
    4. The system shall allow users to approve a script. 
    5. The system shall lock a generated script for editing after the script has been approved by the user. 

6. Video Generation 
    1. The system shall only allow a video to be generated if a user has a saved API key. 
    2. The system shall generate a video when an avatar, script, title, and voice have been entered/selected. 
    3. The system shall save the video to a user's account to view and download. 
    4. The system shall save a generated avatar-only video to a user's HeyGen account. 
    5. The system shall allow users to view a generated video in-browser. 
    6. The system shall allow users to download a generated video. 

## Non-Functional Requirements

1. Accessibility
    1. The system shall maintain a color-blind friendly color pallet for accessibility. 
    2. The system shall maintain a consistent color pallet. 
    3. The system shall generate a slideshow as part of the video with a consistent template. 
    4. The system shall maintain a consistent template for slideshows. 
    5. The system shall allow users to download video content in multiple formats. 
    6. The system shall allow users to download slideshow content in multiple formats. 

2. Security 
    1. The system shall provide constraints around emails. 
    2. The system shall provide constraints around passwords. 
    3. The system shall encrypt all API keys that are stored. 
    4. The system shall encrypt all passwords that are stored.
    5. The system shall automatically log out a user after 1 hour of inactivity. 

3. Usability
    1. The system shall process text inputs within 20 seconds. 
    2. The system shall display the list of avatars for a user within 1 minute. 
    3. The system shall provide the created video to the user within 15 minutes. 
    4. The system shall display a spinning 'loading' icon upon any clickable action from the user. 
    5. The system will provide 'Go Back' buttons throughout the video generation process. 
    6. The system shall use near-exact script language when generating a slideshow.  

4. Instructive Content
    1. The system will provide a readable and easy-to-follow set of instructions for generating an API from HeyGen. 
    2. The system shall provide a step-by-step guide for users creating their first generated video. 
    3. The system shall provide instructions on the homepage of the application for use. 
    4. The system will provide information on prompting techniques for use with LLM's on the homepage. 
    5. The system shall provide an avatar video explaining the use of the application for users to view.

5. Compatibility
    1. The system shall function across Chrome, Microsoft Edge, and Safari. 
    2. The system shall allow voices to be in any HeyGen V2 supported language.
    3. The system shall allow users to download videos in several different formats. 
    4. The system shall allow users to submit edits to scripts in different languages. 
    5. The system shall update the allowed voices and avatars based on a user's account for HeyGen. 



# Change management plan
This section details the change management plan for ProfAI.


### Sponsor
Erik Fredericks, Professor, College of Computing, Grand Valley State University


### Change Agent
Information Technology Innovation and Research, Information Technology, Grand Valley State University


### Potential Adopters
* Faculty Members
* IT Staff Members


### Plan

#### Revising Management Policies
We plan to evaluate IT's current policies to identify if any policies conflict with our product. With the pending launch of any new AI policies or procedures, we will assess if any action needs to be taken for our product. Proposed changes will be submitted as a formal request to IT Innovation and Research. Any proposed changes to our system will be reviewed by both IT Innovation and Research, and IT Security. If needed, approvals may need to be revised and approved again. This review is intended to resolve any integration issues, policy conflicts, and user experience pain points. All changes will be compatible with GVSU systems.


#### Assessing the Cost and Benefits
For any requested changes, IT Innovation and Research will evaluate the costs associated, such as software licensing, working hours and development time, etc. Benefits and downsides of proposed changes will also be considered. In the assessment, any potential risks will be identified and judged for approval/denial.


#### Motivating Adoption
Any approved implemented change will be announced by IT Innovation and Research. Test groups, motivated by free beta testing, will be asked to verify that the change was successful. Surveys will be sent to early testers to request feedback.


#### Training
Training content will be provided to faculty who are registered on the application. Appropriate training will also be given to staff members supporting the application upon any approved and implemented change. Any major change to this application will include a series of training articles (Knowledge Base Articles) to enhance community member understanding. 



# Traceability links
This section links any related artifacts to final requirements. 
## Use Case and Activity Diagram Traceability
| Artifact ID     | Artifact Name                     | Requirement ID |
| :-------------: | :----------:                      | :----------: |
| 2.1 | Importing Avatars (Use Case and Activity) | FR2 |
| 2.2 | Video Generation (Use Case and Activity)| FR5, FR6 |
| 2.3 | Slideshow Generation (Use Case Only)| FR3|
| 2.4 | User Account Information (Use Case Only)| FR1, NFR2 |
| TBD | TBD | FR4, NFR1, NFR3, NFR4, NFR5 |


## Class and Object Diagram Traceability
| Artifact ID     | Artifact Name | Requirement ID |
| :-------------: |:----------: | :----------: |
| 4.1 | Models Class and Object Diagram | FR1, NFR2 |
| 4.2 | Overall Project Class and Object Diagram | FR1-6, NFR3, NFR4 |
| TBD | TBD | NFR1, NFR2, NFR5|


## CRC Cards, Sequence and State, and Windows Navigation Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 3.1 | Models CRC | FR1, NFR2 |
| 3.2 | Movies CRC | FR1, FR6, NFR1 |
| 3.3 | Views CRC | FR1-6, NFR2 |
| 5.1 | API Key Handling Sequence and State | FR1, FR2, FR5, NFR2 |
| 6.1 | Homepage and Dashboard Navigation | FR1-F6, NFR3, NFR4 |
| TBD | TBD | NFR1, NFR5|







# Software Artifacts
This section provides direct links to all related artifacts for this application. Artifacts are sorted by the following ID's. 
| Artifact ID Level| Artifact Type |  Artifact Link |
| :-------------: | :----------: | :----------: |
|1.0| Software Requirements | [https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/docs/software_requirements_specification_final.md](Software Requirements) |
|2.0| Use Case and Activity Diagrams |[https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/artifacts/use_case_diagrams.pdf](Use Case and Activity Diagrams) |
|3.0| CRC Cards | [https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/artifacts/crc_cards.pdf](CRC Cards) |
|4.0| Class and Object Diagrams | [https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/artifacts/class_object_diagrams.pdf](Class and Object Diagrams) |
|5.0| Sequence and State Diagrams | [https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/artifacts/sequence_state_diagrams.pdf](Sequence and State Diagrams)  |
|6.0| Windows Navigation Diagrams | [https://github.com/tdettling/GVSU-CIS641-ProfAI/blob/main/artifacts/windows_nav_diagrams.pdf](Windows Navigation Diagrams)  |



