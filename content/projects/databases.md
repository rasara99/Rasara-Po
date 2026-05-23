---
title: "Database Management Projects"
date: 2025-05-15
tags: ["MySQL", "MongoDB", "Database Design", "SQL", "NoSQL", "CRUD Operations", "Query Optimization"]
description: "Projects showcasing relational and non-relational database design, CRUD implementation, and query performance optimizations."
summary: "Designed and developed structured database solutions using MySQL and MongoDB for inventory and student management systems."
showToc: true
---

### Overview

These projects demonstrate my understanding of database theory, schema design, and hands-on implementation of relational and non-relational database models. I have built fully functional backend systems focusing on data integrity, optimization, and reliable CRUD (Create, Read, Update, Delete) operations.

---

### Key Projects & Core Architectures

#### 1. Inventory Management System
* **Database Type**: Relational (MySQL)
* **Goal**: Establish a system to track stock levels, suppliers, and purchase transactions.
* **Implementation**:
  * Designed entity-relationship (ER) diagrams mapping relationships (one-to-many, many-to-many) between items, categories, and vendors.
  * Formulated primary and foreign keys to enforce referential integrity constraints.
  * Wrote optimized SQL queries using indexes, joins, and aggregations to retrieve real-time inventory levels.

#### 2. Student Management System
* **Database Type**: Document-Based (MongoDB)
* **Goal**: Manage flexible student profiles, course registrations, and grading records.
* **Implementation**:
  * Leveraged MongoDB's dynamic schemas to store hierarchical records (e.g., nesting contact information and grades within student documents).
  * Built endpoints to process CRUD requests efficiently.
  * Conducted query optimization tasks, utilizing indexes on frequently queried fields like `student_id` and `email` to reduce search latency.

---

### Core Database Capabilities

* **Database Design & Modeling**: Creating structured, normalized tables for SQL databases (up to 3NF) and logical document boundaries for NoSQL databases.
* **Query Optimization**: Using tools like `EXPLAIN` in MySQL and index evaluations in MongoDB to identify bottleneck queries and restructure indexing paths.
* **Data Integrity & Validation**: Implementing validation rules at the application and database layers to prevent invalid data entry and ensure schema compliance.

---

### Technologies Applied

| Paradigm | Technologies & Tools |
| :--- | :--- |
| **Relational (SQL)** | MySQL, WorkBench, Structured Query Language (SQL) |
| **Non-Relational (NoSQL)** | MongoDB, Compass, Mongoose ODM |
| **Methods** | Database Design & Modeling, CRUD Operations, Query Optimization |
