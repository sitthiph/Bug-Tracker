# Bug Tracker

## Introduction

This document lays out a project plan for the development of the “Bug Tracker” open source repository system by Sam Itthiphinyo.

The intended readers of this document are current and future developers working on “Bug Tracker” and the sponsors of the project. The plan will include, but is not restricted to, a summary of the system functionality, the scope of the project from the perspective of the “Bug Tracker” team, scheduling and delivery estimates, project risks and how those risks will be mitigated, the process by which I will develop the project, and metrics and measurements that will be recorded throughout the project.

## Overview

A bug tracking system or defect tracking system is a software application that keeps track of reported software bugs in software development projects, allowing end-users to enter bug reports directly. It may be regarded as a type of issue tracking system. A Bug Tracker is usually a necessary component of a good software development infrastructure, and consistent use of a bug or issue tracking system is considered one of the "hallmarks of a good software team"

### Customers

Software development team. It can be that of a personal level team or enterprise-level team.

### Functionality

* Users should be able to be authenticated and authorized.
* Track todos, bugs, feature requests, and more. As issues are created, they’ll appear in a searchable and filterable list.
* Ability to assign user(s), labels, due dates to each issue.
* Keep track of everything in your project and see exactly what changed since the last time you've open the application.
* Provide a clear centralized overview of development requests, including both bugs and improvements, and their state.
* Generate reports on the productivity of programmers.
* Display reports on the productivity of programmers.
* See the overall performance of yourself

### Platform

It will be launched as a Web-based application with mobile responsive.

### Development Responsibility

Sam I. - Responsible for planning the development, developing the software, creation of the Database, and project documentation.

## Risk Management

### Risk Identification and Mitigation

Following will be the risk involved in this project:
* <b>There is already multiple Bug Tracker in the industry. Why would someone start using this Bug Tracker?<br></b>
Even though most of the users would already be using other bug tracking systems, our platform would still offer them many things that are not there on their app. E.g.
  1. Provide reports on the productivity of programmers and display it.
  2. One-to-Many relationship between A user and projects(I.e. One user can track all of their assigned bug in all of their project in one place)
  
Thus, I think that there is a considerable amount of difference between other bug tracker and this application and it would attract many people.

## Scheduling and Estimates

| Milestone | Description | Release Date | Release Iteration |
| ----------- | ----------- | ----------- | ----------- |
| M1 | Completed overview of project planning, application view and design, and software architecture.| Dec 12, 2019 | Planning |
| M2 | MVP server-side with database | Dec 22, 2019 | Back-end Development |
| M3 | Add authentication and authorization | Jan 2, 2020 | Back-end Development |
| M4 | MVP client-side | Jan 21, 2020 | Front-end Development |
| M5 | Front-end integrated with back-end | Jan 25, 2020 | Alpha |
| M6 | Implement the ability to assign user(s), labels, due dates to each issue | Feb 7, 2020 | Beta |
| M7 | Unit testing and bug catches | Feb 11, 2020 | Release candidate |
| M8 | MVP Bug Tracker release | Feb 12, 2020 | Stable Release |
| M9 | Server-side report integrated | Feb 20, 2020 | Pre-Alpha |
| M10 | Client-side report integrated | Feb 27, 2020 | Beta |
| M11 | Unit testing and bug catches | March 2, 2020 | Release candidate |
| M12 | Bug Tracker with reports on the productivity of programmers | March 3, 2020 | Stable Release |
| M+ | Coming back after completing M8 to reevaluate Scheduling | TBA | Perpetual Beta |

## Technical Process

The following are the languages use to develop this application:
* <b>Client-side development -</b>
  * HTML5/CSS3/Javascript
  * [React](https://reactjs.org/)
    * [React-Redux](https://react-redux.js.org/)
  * [Ant Design](https://ant.design/)
* <b>Server0side development -</b>
  * [Java](https://www.java.com/en/)
  * [OAuth](https://oauth.net/2/)
  * [Spring](https://spring.io/)
    * [Spring Boot](https://spring.io/projects/spring-boot)
    * [WebSockets](https://spring.io/guides/gs/messaging-stomp-websocket/)
    * [Spring MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html)
  * [GraphQL](https://graphql.org/)
  * [Hibernate](https://hibernate.org/)
  * [MYSQL](https://www.mysql.com/)
