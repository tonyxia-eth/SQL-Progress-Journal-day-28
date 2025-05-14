# SQL-Progress-Journal-day-28

# Day 29 - SQL Learning Journey 🚀  
**Date:** 13 May 2025  
**Course:** CS50's Introduction to Databases with SQL  
**Focus:** Table Creation, Column Constraints, and Primary Keys  

---

## 🧠 What I Learned Today

Today I took a new approach to deepen my understanding of **database design fundamentals**. I watched the full lecture on schema design and worked alongside the examples to reinforce concepts like:

- Using `CREATE TABLE` to define custom table structures
- Applying **column constraints** like `PRIMARY KEY`, `NOT NULL`, and `UNIQUE`
- Understanding data types: `TEXT`, `INTEGER`, `REAL`, etc.
- Why constraints are crucial for ensuring **data integrity**
- How primary keys help uniquely identify records (like `player_id` in the Moneyball dataset)


Today marks a new mile stone, starting the next phase of my SQL learning by developing my own database and making real world applications.
---

## 🧩 Real-World Reference: Moneyball Dataset

I linked the lesson back to the **Moneyball** database I’ve worked with. For example:

```sql
CREATE TABLE players (
    player_id TEXT PRIMARY KEY,
    name TEXT,
    birth_year INTEGER
);
