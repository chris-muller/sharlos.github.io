---
layout: project
title:  "Wool Search"
description: "An industry directory for products and services provided by wool suppliers."
link: "http://www.woolmark.com/resources/wool-search"
order: 100
image: /img/woolsearch-thumb.png
---

![]({{site.baseurl}}/img/woolsearch-1.png#img-wool-hero)

Wool Search was a new section of the existing woolmark.com website, created to allow the user to search and filter wool suppliers based on the products and services they provide.

The data for Wool Search came from a pre-existing SalesForce data store and synced to an independent SQL database using a Cloud Sherpas service.

![]({{site.baseurl}}/img/woolsearch-2.png)

### Process and Contribution
My responsibilities during the course of the project included:

* Integrating the static HTML assets into the project as Razor views.
* Implementing REST API for use by the Angular frontend.
* Updating Dapper SQL queries and object mapping with to conform to changing database schema and requirements during the course of the project.
* Transforming provided business data into a usable format and structure for use in the project.
*  Building unit tests for core components of business logic.
* Connecting project into existing website EPiServer code.
* Indexed supplier data using EPiServer Find.

### Technology Used
* ASP.NET web application used to run an EPiServer website.
* Dapper used as an ORM for SQL queries to an MSSQL database.
* Tickets, project status and deployment managed using Jira and Bamboo.
* Git used as the version control tool.
  
![]({{site.baseurl}}/img/woolsearch-3.png#img-wool-footer)
