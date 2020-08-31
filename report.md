# Google Summer Of Code 2020 Report

|                        |                                 |
|------------------------|---------------------------------|
|__Orgainization__       | [Robocomp](https://robocomp.github.io/web/) |
|__Project name__        | Robocomp conversationalAgent Devlopement |
|__Primary repository__  | [robocomp-viriato](https://github.com/robocomp/robocomp-viriato)              |
|__Project Mentors__     | [Pedro Núñez Trujillo](https://github.com/pedromnunez), [Ramon Cintas](https://github.com/rcintas) |
|__Project Page__        | [Summer of Code Project Page](https://summerofcode.withgoogle.com/projects/#6375833284902912)   |
|__Status__              | Completed                       |



# Project Abstract
In the real world, a robot needs to follow social etiquettes while moving around so as to not hurt any human. To follow these etiquettes the robot will have to speak with the person that is creating an obstacle in the robot's movement.  

In this project, I have worked on the conversationalAgent which uses RASA to create personalized conversations according to the situation. I have also created a GUI for the displaying the conversation as well as for other functions.



## Major Task of the Project:
  - Creating a chatbot using RASA that will generate personalized conversations according to the situation.

  - Creating custom actions to link RASA chatbot with my RoboComp component. 

  - Adding ASR and TTS functionalities to make it easier for the user to communicate with the robot.

  - Writing rules in AGGL for the mission of the robot, and integrating my component with mission agent to auto activate when initial conditions of mission are full filled.

  - Creating GUI's for 1)component, 2)Dialogue and 3)Rasa functions.


## Component that I worked on:
During my GSoC duration i worked on these components:
- [Conversational Agent](https://github.com/rahulkatiyar19955/gsoc-gui-dev/tree/master/humanObserverAgent_GUI)



## Challenging part of Project:
There were many times when I used to get stuck with problems and wasn't able to figure them out, but with the help of mentors and a lot of googling I used to resolve them.

I will list a few such problems that I faced:
- The first problem that I faced is while setting up the robocomp environment, even a small mistake in the documentation or not correctly specifying the library version number leads to failing the setup.

- While linking the Graphical interface with Robocomp core functionality, I have to read the whole codebase first, which is in itself is a big task.

- Robocomp uses both python2 as well python3, which will make it more challenging to make the code compatible with both.

- Interfacing graphical interface with AGM is a lot more complicated than I thought, as there was no python tutorial available on AGM.


## Future Work:
- The chatbot created can be extended to more use cases.

- Therapy or other non-navigational chatbots can also be created and integrated. 


## Links for the Blogs:
1. [Introduction](https://robocomp.github.io/web/gsoc/2020/posts/rahul_katiyar/post01)
2. [Human Observer Agent GUI](https://robocomp.github.io/web/gsoc/2020/posts/rahul_katiyar/post02)
3. [Integrating Google Calendar with GUI](https://robocomp.github.io/web/gsoc/2020/posts/rahul_katiyar/post03)
4. [Human Scene Simulation](https://robocomp.github.io/web/gsoc/2020/posts/rahul_katiyar/post04)
5. [Automated tool to perform optimisation](https://robocomp.github.io/web/gsoc/2020/posts/rahul_katiyar/post05)

## Youtube links:
  [GSoC Robocomp playlist](https://www.youtube.com/playlist?list=PL15a54aGvXvnKV4LLaJrCyd4P8-Jpts6t)
- This playlist contains a tutorial and demonstration of the components that I implemented.


## Commits & Pull Requests

- **Pull Request:** [Add component conversationalAgent created during GSoC](https://github.com/robocomp/robocomp-viriato/pull/2)



## Conclusion
An amazing journey of 4 months comes to an end. I have learned a lot during this time. I thank my mentors who always guided me and encouraged me to work harder. Even though GSoC comes to an end I plan to continue contributing to RoboComp as well as open source in the future.

---

**Contact**:\
For any query or suggestions related to the work, feel free to contact me at:\
Email - [rishigondkar@gmail.com](mailto:rishigondkar@gmail.com) \
Github Profile - https://github.com/RishiGondkar \
Linkedin Profile - https://www.linkedin.com/in/rishi-gondkar-8b4199149/ \
Profile - https://rishigondkar.wixsite.com/profile