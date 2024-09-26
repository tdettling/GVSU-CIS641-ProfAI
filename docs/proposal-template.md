Team name: ProfAI

Team members: L Dettling 

# Introduction
Students have varying preferences for learning, requiring flexible, dynamic content to suit their needs. Studies show that longer lectures with minimal engagement from students leads to poor retention and interest from students (see sources [1.1](https://www.lifescied.org/doi/10.1187/cbe.16-03-0125) , [1.2](https://www.researchgate.net/publication/248528255_A_Cognitive_Theory_of_Multimedia_Learning_Implications_for_Design_Principles) , and [1.3](https://www.sciencedirect.com/science/article/abs/pii/S0360131516301798) for more inforamtion). Additionally, instructors are struggling to produce meaningful content for students due to the technical requirements of content creation. With these motivating factors in mind, GVSU IT Innovation and Research is proposing ProfAI, a dynamic generative AI content creation web application to allow AI to dynamically create curated content for faculty memebrs.


ProfAI will first request faculty members to generate a realistic avatar of themselves by going to [HeyGen](https://heygen.com/?sid=rewardful&via=ixm&gad_source=1&gclid=CjwKCAjw6c63BhAiEiwAF0EH1K1eGktiLLk8hvrOuXJV9O0kO6zw9fuNTza5qae9bgCVln0pxvn_2RoCj0MQAvD_BwE), and following the website's series of insturtions. After an avatar has been created, the proposed application will then generate a script based on the faculty member's topic of choosing. Upon receiving approval of the script from the faculty member, the web application will then generate a video of the avatar speaking the approved script, alongside a slideshow in a downloadable 2-5 minute video. Faculty members may then upload the video in whichever way they would like to deploy to students. After the initial launch of the project, IT Innovation and Research will conduct student interviews with the students that have seen the video of their faculty member to determine the value and authenticity of the content.



# Anticipated Technologies

We predict the use of several technologies for this project. At this time, we are planning to keep user data stored and secured with MongoDB, although may choose to upgrade to a larger-scale storage system later on after the completion of this course. We are looking into [ChatGPT'S Open AI Platform API](https://platform.openai.com/docs/assistants/overview) for script generation. Next, we plan to use [ElevenLabs API](https://elevenlabs.io/docs/api-reference/getting-started) for voice generation. Although we have not finalized this decision yet, we are deciding to use either [SlideSpeak API](https://slidespeak.co/slidespeak-api/) or [Magic Slides API](https://www.magicslides.app/magicslides-api/docs)  for slideshow generation based on the generated script. We plan to use [HeyGen's API](https://docs.heygen.com/docs/quick-start) for secure avatar generation and video generation.


We are planning to adopt GitHub for the storage and management of our code. We plan to use Trello as a project management tool. For our web development tools, we intend to use React and Django. 

# Method/Approach

This project currently includes a staff member from IT Innovation and Research, an undergraduate student form GVSU, and myself. We plan to use an agile development methodology because of the flexibility it offers and the focus on working software. As a slight deviation from traditional agile methodologies, our team plans to create a workflow for changing requirements so that we can sustain our timeline for the semester (rather than the traditional "embracing" of changing requirements).


The staff member in IT Innovation and Research is serving as the project manager. He will be running weekly check-in both individually and as a team for this project, ensuring direct and consistent communication. The undergraduate student will be serving primarily as a front-end developer. I will be serving as both a product manager and as a backend developer, with my respincibilites including submiiting the any course deliverbales (reuirements, UML dioagrams, etc.). To keep myself honest and responcible for my portion of this project, I have also initiated weekly meetings with the undergraduate student to ensure regular communication between those who are contributing code.


# Estimated Timeline

We anticipate there being several milestones for this project. First, we will need to finalize our technical specifications for this project, which will outline what technologies will be implemented. This milesotne will be done before October. Our next major milestone will be to finish creating our mission critical high-level requirements and finalize our user stories before October 13th. This will allow us to move forward with the next stage of our development process. Moving forward, we will then hope to plan a sprint with completion around the 25th of October for some of our critical requirements. Because this will be the first sprint, I consider this a milestone. Several sprints will be planned for the next few weeks, with a mid-sprint check-in planned near Novemebr 8th. As this is a larger scale project, having a mid-sprint check-in can be vital for developer feedback. Finally, we hope to reach a working prototype ready for a trial launch in late November for IT Innovation and Research. This will give us time to hear formal feedback from both IT and from our selected faculty who choose to use this tool.

# Anticipated Problems

One of the major challenges we foresee is the lack of knowledge about web development from the developers. Although I am familiar with languages like Julia, Python, and Java, I have never done web development. Our other developer has been learning web development for the last month, so the technical abilities of our team in terms of web development is low. However, there are available resources online for developers to learn web development.  Since the beginning of the semester, I have been practicing and watching tutorials to prepare for this challenge.


I believe that scope creep will also be a challenge - this is the type of project that could get far too large in requirements for a semester long class. Although expectations have been communicated between myself and the project manager, we need to make sure to be extra cautious that new requirements are not thrown in at the last minute, and that we are firm about the size and scope of this inital implementation. Our hope is that our weekly meetings and consistent communication between our team members will alleviate some of this challenge. As mentioned in the Method/Approach section, we also plan to come up with a process for approving/declining changing requirements so that the critical requirements don't get too large.


