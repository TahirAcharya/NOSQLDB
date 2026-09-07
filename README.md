# 🗄️ NoSQL Databases — BCD515C

> **5th Semester | Professional Elective | 2026–2027 ODD | 3:0:0 | 40 Hours | 3 Credits**

A structured, student-friendly GitHub course repository for **NoSQL Databases (BCD515C)**.  
This repository is designed to keep the syllabus, module notes, presentations, examples, tools, practice material and project resources in one place.

# ZERO SESSION
[PPT Link](https://docs.google.com/presentation/d/1Gw6JMsPUvkZvm7psJs84A1y6KqxrPY-5/edit?usp=sharing&ouid=102189640680844426038&rtpof=true&sd=true)

SYLLABUS
[Syllabus Link](https://drive.google.com/file/d/1AY7Gqu1uvb7T7ISgokrS9LxiDGrjPEuU/view?usp=sharing)
---

## 🎯 Course at a Glance

| Item | Details |
|---|---|
| Course | **NoSQL Databases** |
| Course Code | **BCD515C** |
| Course Type | Professional Elective Course |
| Semester | **V** |
| Academic Year | **2026–2027 (ODD)** |
| L-T-P | **3:0:0** |
| Total Pedagogy | **40 Hours** |
| Credits | **03** |
| Examination | Theory |
| CIE / SEE | **50 / 50** |

### Course Objectives

By the end of the course, learners should be able to:

- Understand the importance and need for NoSQL databases.
- Understand MapReduce and Key–Value databases.
- Understand the fundamentals of Document databases.
- Identify situations where Graph databases are advantageous.
- Connect NoSQL concepts with scalable, distributed and real-world applications.

---

# 🧭 Course Roadmap

```text
WHY NoSQL
   ↓
DATA MODELS
   ↓
DISTRIBUTION + CONSISTENCY
   ↓
MAPREDUCE + KEY–VALUE
   ↓
DOCUMENT DATABASES
   ↓
GRAPH DATABASES
   ↓
REAL-WORLD NoSQL SYSTEM DESIGN
```

---

# 📚 Module-wise Syllabus

## Module 1 — Why NoSQL & Aggregate Data Models
**8 Hours**

### Topics
- Why NoSQL?
- Value of relational databases
- Persistent data
- Concurrency and integration
- Standard relational model
- Impedance mismatch
- Application and integration databases
- Attack of the clusters
- Emergence of NoSQL
- Aggregate data models
- Aggregates
- Relations vs aggregates
- Consequences of aggregate orientation
- Aggregate-oriented databases
- Relationships
- Graph databases
- Schemaless databases
- Materialized views

### Suggested tools
`MongoDB` · `Neo4j` · `JSON`

### Learning outcome
Students can explain **why NoSQL emerged**, distinguish relational and aggregate-oriented thinking, and identify suitable NoSQL data models.

---

## Module 2 — Distribution, Consistency & CAP
**8 Hours**

### Topics
- Single-server model
- Sharding
- Master–slave replication
- Peer-to-peer replication
- Combining sharding and replication
- Update consistency
- Read consistency
- Relaxing consistency
- CAP Theorem
- Version stamps
- Business and system transactions
- Version stamps on multiple nodes

### Suggested tools
`MongoDB` · `Cassandra` · `DynamoDB`

### Learning outcome
Students can reason about **scaling, replication, partitioning and consistency trade-offs** in distributed NoSQL systems.

---

## Module 3 — MapReduce & Key–Value Databases
**8 Hours**

### Topics
- Basic MapReduce
- Partitioning and combining
- Composing MapReduce calculations
- Two-stage MapReduce
- Incremental MapReduce
- Key–Value stores
- Consistency
- Transactions
- Query features
- Data structure
- Scaling
- Use cases:
  - Session information
  - User profiles
  - Preferences
  - Shopping carts
- When not to use Key–Value databases:
  - Relationships among data
  - Multi-operation transactions
  - Query-by-data
  - Set-based operations

### Suggested tools
`Redis` · `DynamoDB`

### Learning outcome
Students can select Key–Value storage for appropriate workloads and explain the basic MapReduce processing model.

---

## Module 4 — Document Databases
**8 Hours**

### Topics
- What is a Document Database?
- Consistency
- Transactions
- Availability
- Query features
- Scaling
- Suitable use cases:
  - Event logging
  - Content Management Systems
  - Blogging platforms
  - Web / real-time analytics
  - E-commerce applications
- When not to use:
  - Complex transactions spanning different operations
  - Queries against varying aggregate structures

### Suggested tools
`MongoDB` · `MongoDB Atlas`

### Learning outcome
Students can model application data as documents and identify appropriate document-database use cases.

---

## Module 5 — Graph Databases
**8 Hours**

### Topics
- What is a Graph Database?
- Nodes and relationships
- Graph database features
- Consistency
- Transactions
- Availability
- Query features
- Scaling
- Suitable use cases:
  - Connected data
  - Routing
  - Dispatch
  - Location-based services
  - Recommendation engines
- When not to use graph databases

### Suggested tools
`Neo4j` · `Cypher`

### Learning outcome
Students can identify relationship-heavy problems and model them using graph databases.

---

# 🧰 NoSQL Tools Lab / Demo Map

| Category | Tools | Best-fit learning |
|---|---|---|
| Document | MongoDB | Documents, CRUD, aggregation, indexing |
| Key–Value | Redis | Key–value operations, caching, sessions |
| Wide-column | Apache Cassandra | Distribution, replication, scalable writes |
| Key–Value + Document | Amazon DynamoDB | Partitioning, managed NoSQL, cloud scale |
| Graph | Neo4j | Nodes, relationships, Cypher, connected data |
| Processing | Hadoop MapReduce | Distributed batch processing concepts |

---

# 📝 Notes Repository

Keep notes separated by module so updates remain simple.

```text
notes/
├── module-01-why-nosql/
│   ├── lecture-notes.md
│   ├── quick-revision.md
│   └── important-questions.md
├── module-02-distribution-consistency/
│   ├── lecture-notes.md
│   ├── cap-theorem.md
│   └── quick-revision.md
├── module-03-mapreduce-keyvalue/
│   ├── lecture-notes.md
│   ├── mapreduce.md
│   └── key-value.md
├── module-04-document-databases/
│   ├── lecture-notes.md
│   ├── mongodb.md
│   └── quick-revision.md
└── module-05-graph-databases/
    ├── lecture-notes.md
    ├── neo4j-cypher.md
    └── quick-revision.md
```

### ✏️ How to update notes

1. Open the relevant module folder.
2. Edit `lecture-notes.md`.
3. Add diagrams, examples and references.
4. Keep each concept short and exam-oriented.
5. Commit using a clear message:

```bash
git add .
git commit -m "Update Module 4 MongoDB notes"
git push
```

---

# 🎞️ PPT / Presentation Repository

```text
presentations/
├── 00-zero-session/
├── 01-module-01/
├── 02-module-02/
├── 03-module-03/
├── 04-module-04/
└── 05-module-05/
```

Recommended naming:

```text
M01_Why_NoSQL.pptx
M02_Distribution_CAP.pptx
M03_MapReduce_KeyValue.pptx
M04_Document_Databases.pptx
M05_Graph_Databases.pptx
```

---

# 🌐 Official Learning Resources

### MongoDB
- Documentation: https://www.mongodb.com/docs/
- Manual: https://www.mongodb.com/docs/manual/
- MongoDB University: https://learn.mongodb.com/

### Redis
- Documentation: https://redis.io/docs/latest/
- Redis University: https://university.redis.com/

### Apache Cassandra
- Documentation: https://cassandra.apache.org/doc/latest/
- Getting Started: https://cassandra.apache.org/doc/latest/cassandra/getting-started/

### Amazon DynamoDB
- Documentation: https://docs.aws.amazon.com/dynamodb/
- Getting Started: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html

### Neo4j
- GraphAcademy: https://graphacademy.neo4j.com/
- Documentation: https://neo4j.com/docs/
- Cypher Manual: https://neo4j.com/docs/cypher-manual/current/

### Hadoop / MapReduce
- Apache Hadoop: https://hadoop.apache.org/
- MapReduce Tutorial: https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html

---

# 🎓 Recommended E-Resource Path

## Beginner
1. Understand SQL vs NoSQL.
2. Learn the four major NoSQL families.
3. Study CAP and distributed systems.
4. Try MongoDB CRUD.
5. Try Redis key–value operations.
6. Build a simple Neo4j graph.

## Intermediate
- Data modeling
- Indexing
- Aggregation
- Replication
- Sharding
- Consistency
- Query design
- Performance trade-offs

## Advanced / Project
- Polyglot persistence
- NoSQL architecture
- Distributed system design
- Recommendation systems
- Real-time analytics
- Event-driven applications
- Graph-based recommendations
- Cloud NoSQL

---

# 🧪 Suggested Student Activities

- **Activity 1:** SQL table → MongoDB document conversion
- **Activity 2:** Demonstrate CAP trade-offs
- **Activity 3:** Design a Redis-based session store
- **Activity 4:** Build a MongoDB e-commerce database
- **Activity 5:** Model a social network in Neo4j
- **Activity 6:** Compare MongoDB, Redis, Cassandra and Neo4j for one application
- **Activity 7:** Mini project using any NoSQL platform

### Mini-project idea

> **Design a scalable NoSQL solution for a real-world application.**

Possible domains:
- E-commerce
- Social networking
- Recommendation engine
- Food delivery
- Smart campus
- IoT analytics
- Travel / routing
- Learning management system

---

# 🧠 Quick Revision Matrix

| Concept | Remember |
|---|---|
| NoSQL | Not only SQL / non-relational approaches |
| Aggregate | Data grouped around an application access pattern |
| Sharding | Horizontal partitioning |
| Replication | Multiple copies of data |
| CAP | Consistency, Availability, Partition tolerance |
| Key–Value | Key → value |
| Document | JSON/BSON-like document |
| Graph | Nodes + relationships |
| MapReduce | Map → intermediate processing → Reduce |
| Polyglot persistence | Use different databases for different needs |

---

# 📖 Core Textbook

**Pramod J. Sadalage & Martin Fowler**  
*NoSQL Distilled: A Brief Guide to the Emerging World of Polyglot Persistence*  
Pearson / Addison-Wesley.

### Reference Books
- Dan Sullivan — *NoSQL for Mere Mortals*
- Dan McCreary & Ann Kelly — *Making Sense of NoSQL*
- Kristina Chodorow — *MongoDB: The Definitive Guide*

---

# 📌 Repository Contribution / Update Convention

Use this pattern for future additions:

```text
notes/       → lecture notes and revision material
slides/      → classroom presentations
examples/    → code and datasets
activities/  → classroom activities
projects/    → student project ideas
resources/   → external learning resources
question-bank/ → module-wise questions
```

### Commit examples

```text
Add Module 1 aggregate model notes
Add MongoDB CRUD examples
Update Module 2 CAP diagram
Add Neo4j Cypher resources
Add Module 5 question bank
```

---

## ⭐ Teaching Philosophy

> **Learn the model → See the architecture → Use the tool → Solve a problem → Explain the trade-off.**

NoSQL is not about replacing SQL.  
It is about choosing the **right data model and storage strategy for the problem**.

---

## 📅 Academic Version

**2026–2027 ODD | BCD515C | Semester V**

This repository is intended to evolve throughout the semester. New notes, examples, presentations, question banks, datasets and e-resources can be added without changing the overall structure.

