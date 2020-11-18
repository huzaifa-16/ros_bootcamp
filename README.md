# ros_bootcamp
INTRODUCTION ON ROS

What is ROS? Mentions its merits and limitations.

Roboting operating system is not an operating system,it is a meta operating system for a robot. It provides service like hardware abstraction, low-level control etc.
It needs another OS(operating system) to run.There are 2 types of ROS:
  ROS1 and ROS2
ROS runs on unix based OS. 
ROS noetic ninjemys is the latest ROS1. Roswiki is a platform which provides enough info.abt ROS.

MERITS OF ROS:
Thin:allows the flexibility to run the code in robots.

Free and open source:allows to adopt the code.

Peer to peer communication:allows easy management for multi-board robots.

Multi-language:allows coding in many languages like python,c++,octave etc.

Strong intgration with 3rd party like GAZEBO,RViz

LIMITATIONS:
Powerful hardware is required.

It will get slow if the code is large.

Its not a real time system.

Security issues for industrial scenarios.

INDUSTRIES WERE ROS IS USED:
BMW,EMBARK,INTEL,YASKAWA,MAGNA etc,.

WHAT IS WORKSPACE,ROS PACKAGE,NODES,TOPICS,MESSAGES,SERVICES?

WORKSPACE: it is a collection of packages in which we can create or modify existing  packages.

ROS PACKAGE: it is the main organisational software which contains nodes,library data etc,.

NODES: it is a process which perform computation. 

MESSAGES: Nodes use messages to communicate with other nodes. For example if we touch a hot plate our hand sense the heat and interact with our brain and we finally move our hand away from the hot plate, these interactions between our hand to brain are known as messages.

TOPIC: these are the channels through which messages are passed. For example an electrical wire which passes  electricity through it,here wire is known as topic and electricity is messages.

SERVICES: it requests and replies the interaction in robotic system. For example if you want to pick a pen from a table, your brain request the hand to pick the pen and the hand reply the brain my picking it up,so here the request and reply is known as service.



**INTRODUCTION ON ROS**

**What is ROS? Mentions its merits and limitations.**
Roboting operating system is not an operating system,it is a meta operating system for a robot. It provides service like hardware abstraction, low-level control etc.
It needs another OS(operating system) to run.There are 2 types of ROS:
ROS1 and ROS2
ROS runs on unix based OS. 
ROS noetic ninjemys is the latest ROS1. Roswiki is a platform which provides enough info.abt ROS.

**MERITS OF ROS:**
Thin:allows the flexibility to run the code in robots.
Free and open source:allows to adopt the code.
Peer to peer communication:allows easy management for multi-board robots.
Multi-language:allows coding in many languages like python,c++,octave etc.
Strong intgration with 3rd party like GAZEBO,RViz

**LIMITATIONS:**
Powerful hardware is required.
It will get slow if the code is large.
Its not a real time system.
Security issues for industrial scenarios.

**INDUSTRIES WERE ROS IS USED:**
BMW,EMBARK,INTEL,YASKAWA,MAGNA etc,.

**WHAT IS WORKSPACE,ROS PACKAGE,NODES,TOPICS,MESSAGES,SERVICES?**

WORKSPACE: it is a collection of packages in which we can create or modify existing  packages.

ROS PACKAGE: it is the main organisational software which contains nodes,library data etc,.

NODES: it is a process which perform computation. 

MESSAGES: Nodes use messages to communicate with other nodes. For example if we touch a hot plate our hand sense the heat and interact with our brain and we finally move our hand away from the hot plate, these interactions between our hand to brain are known as messages.

TOPIC: these are the channels through which messages are passed. For example an electrical wire which passes  electricity through it,here wire is known as topic and electricity is messages.

SERVICES: it requests and replies the interaction in robotic system. For example if you want to pick a pen from a table, your brain request the hand to pick the pen and the hand reply the brain my picking it up,so here the request and reply is known as service.
