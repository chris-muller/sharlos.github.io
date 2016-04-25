---
layout: project
title: "Destination"
description: "An intelligent destination-focused train timetable iPhone app."
order: 300
image: /img/destination-3.png
---

![]({{site.baseurl}}/img/destination-2.png#dest-one)

Destination is an iOS app that takes public transport data and uses phone location information to provide a seamless timetable experience that dynamically updates to provide the most relevant information to the user when they most need it.

In addition, the iPhone application is supported by a backend server that collects the transport data from a government portal and transforms it into useable JSON data that is sent to the iPhone application. 

### Process and Contribution
Project started with brainstorming and refining of the essential features. Once core features were settled I began collaborating with a product designer to develop wireframes and the app branding and design.

Backend web application includes the transport data retrieval and parsing, and the API endpoint for the iPhone application timetable updates. On the app client data models and an SQLite schema were created to store the transport data locally. With this data the homescreen view and journey creation views have been created using the storyboard and programmatically where appropriate.

### Technology Used
* iPhone application is coded completely in Swift using Xcode.
* The backend server is built with ASP.NET hosted on an Azure server.
* The parsed data is stored on the backend application using Dapper and MSSQL.
* Data is provided to the iPhone application via a JSON/XML REST API.
* Both the server and iPhone applications use Git as their version control with issue tracking managed in Bitbucket.
