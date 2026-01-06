# SQL Backend Basics

This repository covers **core SQL fundamentals required for backend development**.  
It is designed as a **learning-first, backend-oriented** SQL reference that focuses on clarity over completeness.

The examples and queries in this repository are intentionally simple and map directly to
real-world backend use cases such as fetching users, creating orders, and summarizing data.

---

## SQL Types Covered

- **DDL (Data Definition Language)**  
  Creating and removing database structures such as tables and relationships.

- **DML (Data Manipulation Language)**  
  Inserting, updating, and deleting records — the backbone of CRUD operations.

- **DQL (Data Query Language)**  
  Reading data using filters, joins, and aggregations commonly used in APIs.

- **TCL (Transaction Control Language)**  
  Understanding how multiple operations are executed safely as a single unit of work.

- **DCL (Data Control Language)**  
  Basic access control concepts to understand database permissions at a high level.

---

## Tables Used

- **users** – represents application users
- **orders** – represents orders placed by users

The schema is intentionally small to keep the focus on **query logic and relationships** rather than complex modeling.

---

## Intended Audience

- Backend developers learning SQL
- Java / Spring Boot learners
- Anyone who wants a **clean and minimal SQL foundation** before moving to advanced topics

---

## Scope & Philosophy

This repository **does not attempt to cover advanced SQL features** such as:
- Complex joins
- Stored procedures
- Database-specific optimizations

The goal is to build a **strong foundation** that can later be extended with:
- Pagination
- Indexing
- Transactions in depth
- ORM integration (Spring Data JPA)

---

## How to Use This Repository

1. Start with the `ddl` folder to understand table creation
2. Use `dml` to practice basic CRUD operations
3. Explore `dql` to write queries used in backend APIs
4. Review `tcl` to understand transactional behavior

---

## Next Steps

After completing this repository, you can:
- Connect the schema to a Spring Boot application
- Practice writing REST APIs using these queries
- Gradually extend the database model

---

**This repository is intentionally minimal — and that is by design.**
