# Immigration Case Management System - Backend

## Overview

This repository contains the backend implementation of an Immigration Case Management System developed as part of a Software Engineering team project at George Mason University.

The system supports immigration case tracking, review workflows, approval processes, and management of immigrant and dependent information.

## Technologies Used

- Java
- Jakarta Servlets
- Maven
- Tomcat
- SQL Database
- HTML/CSS Integration

## Features

- Immigration case management
- Review workflow processing
- Approval workflow processing
- Form submission handling
- Database connectivity
- Dependent and immigrant record management
- Server-side validation

## My Contributions

I was responsible for significant portions of the backend implementation, including:

### Domain Models
- Person.java
- Immigrant.java
- Dependent.java
- Review.java
- Approval.java
- Form.java

### Servlet Development
- ReviewServlet.java
- ApprovalServlet.java
- AppServlet.java
- DataEntryServlet.java

### Business Logic
- Review workflow processing
- Approval workflow processing
- Form handling and validation
- Data model integration

### Project Configuration
- Maven configuration (pom.xml)
- Backend project structure
- Tomcat deployment support

## Project Structure

src/
├── main/java/
│ └── edu/gmu/cs321/
│ ├── App.java
│ ├── AppServlet.java
│ ├── Approval.java
│ ├── ApprovalServlet.java
│ ├── DataEntry.java
│ ├── DataEntryServlet.java
│ ├── Dependent.java
│ ├── Form.java
│ ├── Immigrant.java
│ ├── Person.java
│ ├── Review.java
│ ├── ReviewServlet.java
│ └── WFUtil.java

## Academic Project

This project was developed for CS 321: Software Engineering at George Mason University as part of a team-based software development effort.
