---
layout: page
title: "General SQL Queries"
tags:
  - SQL
  - Database Design
  - ERD
  - UML
  - Data Modeling
  - Query Optimization
---

<div class="project-tags">
  <span>SQL</span>
  <span>Database Design</span>
  <span>ERD</span>
  <span>UML</span>
  <span>Data Modeling</span>
  <span>Query Optimization</span>
</div>

## Overview
While not a single standalone project, this section showcases database diagrams and SQL queries I designed to demonstrate my understanding of relational database architecture, data modeling, and query optimization.

## Technologies
- SQL
- Relational Databases
- MongoDB
- UML Diagrams
- Moon Modeler
- Entity-Relationship Diagrams (ERD)

## Examples Included
- Multi-table `JOIN` operations
- Aggregate functions with `GROUP BY`
- Subqueries and nested queries
- Data filtering and indexing strategies

---

## UML Diagram
The diagram below represents a sample "Schema" object created during the initial design phase. The UML model was used to define class structure, relationships, and system behavior before transitioning into database-specific modeling.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/umldiagram.jpg"
       alt="UML Diagram"
       style="max-width: 450px; width: 100%; height: auto;">
</div>

---

## ERD Diagram
The ERD was developed after the UML design to translate the system architecture into a database-oriented structure. This step shifts the focus from object design to relational modeling, including entities, attributes, primary keys, and foreign key relationships.

This intermediate stage ensures compatibility with database implementation tools and reduces schema design errors.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/entityrelationshipdiagram.png"
       alt="ERD Diagram"
       style="max-width: 450px; width: 100%; height: auto;">
</div>

---

## Moon Modeler
Moon Modeler was used as the final implementation stage of the schema design process. This tool connects directly to the database environment, allowing schema deployment and validation.

Although the UML, ERD, and Moon Modeler diagrams represent the same underlying system, each tool presents the structure differently. A significant challenge in this project involved reconciling the subtle differences between modeling standards and ensuring consistency across all representations.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/moonmodeler.png"
       alt="Moon Modeler Diagram"
       style="max-width: 750px; width: 100%; height: auto;">
</div>

---

## SQL Queries
The final examples demonstrate SQL queries designed for a mock order and delivery system.

From a business perspective, these queries extract meaningful insights such as:

- Number of orders placed by specific customers
- Total revenue grouped by city
- Sales trends over time
- Performance metrics by date or category

These queries emphasize efficient data retrieval, aggregation logic, and practical business-oriented reporting.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/SQL.png"
       alt="SQL Query Example 1"
       style="max-width: 700px; width: 100%; height: auto;">
</div>

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/SQL2.png"
       alt="SQL Query Example 2"
       style="max-width: 700px; width: 100%; height: auto;">
</div>