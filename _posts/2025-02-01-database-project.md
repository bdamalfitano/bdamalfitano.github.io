---
layout: page
title: "Hospital Scheduling Database System"
permalink: /database-project/
header-img: "img/city2.jpg"
tags:
  - SQL
  - PostgreSQL
  - MongoDB
  - Database Design
  - UML
  - Data Modeling
  - System Architecture
  - Backend Development
---

<div class="project-tags">
  <span>SQL</span>
  <span>PostgreSQL</span>
  <span>MongoDB</span>
  <span>Database Design</span>
  <span>UML</span>
  <span>Data Modeling</span>
  <span>System Architecture</span>
</div>

## Overview

Designed and implemented a mock hospital job scheduling system from the ground up. The project simulated how hospitals manage staff scheduling, departmental coordination, and shift assignments while maintaining structured and scalable data models.

The system began as a UML design before being implemented in both relational and non-relational database environments using PostgreSQL and MongoDB.

## Technologies Used

- SQL  
- PostgreSQL  
- MongoDB  
- UML Diagrams  
- Moon Modeler  
- Database Normalization  
- Data Modeling  

## System Design Process

### Step 1 UML Modeling

The project began with UML diagrams to define:

- Core entities (Doctors, Nurses, Departments, Shifts, Schedules)
- Relationships between staff and job assignments
- Attributes, constraints, and dependencies
- Scalability considerations

Designing the system visually first ensured logical consistency before implementation.

### Step 2 Relational Database Implementation (PostgreSQL)

The relational model focused on:

- Normalized table structure to reduce redundancy  
- Foreign key constraints to enforce relationships  
- Shift assignment logic using JOIN operations  
- Optimized queries for schedule lookups and reporting  

This version emphasized structured querying and transactional integrity.

### Step 3 NoSQL Implementation (MongoDB)

The system was then adapted into a document-based model using MongoDB to explore:

- Embedded vs referenced document strategies  
- Flexible scheduling schema design  
- Differences in data retrieval patterns  
- Tradeoffs between relational and non-relational storage  

This phase allowed direct comparison between SQL normalization and NoSQL flexibility.

## Key Features

- Full hospital staff scheduling simulation  
- Multi-database architecture comparison  
- Structured normalization in PostgreSQL  
- Document-based modeling in MongoDB  
- End-to-end system design process  
