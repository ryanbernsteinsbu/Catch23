# Catch23

Catch23 is an open-source fantasy baseball platform designed to provide commissioners and league members with a flexible alternative to traditional fantasy sports services.
This web application was built using a full custom CI/CD pipeline through github actions, vercel, and agile sprints using Jira 

## Guide
Inside of this repository you will find 2 sub-modules:
* Catch23-web frontend stack, backend stack, and scripts for Catch23's webapp
* Catch23-public website, business logic, and backend stack for Catch23's public API

## Licenseable API
* Catch23 hosts a liscenceable API service, found at get-catch23.vercel.app, which provides player information, projections, and pick recommendations
* Useage of the API is tracked per API key to emulate a liscencing model.
* API account management is also implemented on the get-catch23 web page

## Web application

### League Management

* Create and manage fantasy baseball leagues
* Custom league settings and rules
* AL-only, NL-only, and Mixed league support
* Commissioner administration tools

### Draft System

* Salary-cap auction drafts
* Configurable draft settings
* Player budgeting and roster management
* Draft tracking and history

### Keepers

* Keeper player support
* Custom keeper rules
* Salary and contract tracking
* Offseason roster retention

### Player Data

* MLB player database integration
* Position eligibility tracking
* Injury and roster status support
* Statistical projections and analysis

## Modern Tech Stack

* Next.js frontend
* TypeScript throughout the application
* Express.js REST API
* PostgreSQL database
* Sequelize ORM
* Vercel deployment

