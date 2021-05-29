# SEMANTIC
This repository contains the code which implements a methodology for reverse engineering android mobile applications. The methodology was developed in the context of a final dissertation of the Master in Software Engineering course at Universidade do Porto - FEUP.

The instalation and utilization guides are provided bellow for easier usage of the tool.

[Installation Manual](Manuals/InstallationManual.md)

[Utilization Manual](Manuals/UserManual.md)



## Motivation and Goal

The motivation behind the development of this tool was the need to find a solution to a common problem among software engineers. Nowadays, with the constant evolution of software, it may be hard not only to maintain artifacts, but also to keep track of every change on an application. Moreover, Android has an exponential learning curve that makes developers need to spend more time to fully understand all the components of Android and their lifecycles in the case of Fragments and Activities. 

The main goal of SEMANTIC is exactly to tackle these problems. This is done by the development of a mixed analysis reverse engineering methodology that takes advantage of the source code of an android mobile application, to analyse it extracting artifacts (Dependency Graphs and intent information) and transform the code, so that the user can interact with his application and check information about activities and fragments' lifecycles. 


## Overview

SEMANTIC is a mixed technique methodology. With this in mind, it is composed of a static analysis and a dynamic analysis phases. The static analysis part involves providing the Kadabra Java Weaver with the source code of the application that is to be analysed. Kadabra will then analyse it and extract the dependency graph and intent information. Also at this stage, Kadabra transforms the code to later allow the dynamic analysis to take place, adding missing lifecycle methods of activities and fragments, as well as the script related to the socket.

The dynamic analysis is performed using a desktop application connected to the mobile app through the previously mentioned socket. In this part of the analysis, the user can explore the mobile application and check the diagrams related to activities and fragments on the desktop app in order to check in real time which activity/fragment is being called and at which state it is.


## Future
?

## Contibutors
?

## Contact
?

## License?
