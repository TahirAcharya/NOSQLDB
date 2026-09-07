# 🗄️ NoSQL Databases — BCD515C

> **5th Semester | Professional Elective | 2026–2027 ODD | L:T:P - 3:0:0 | 40 Hours | 3 Credits**

A structured, course repository for **NoSQL Databases (BCD515C)**.  
This repository is designed to keep the syllabus, module notes, presentations, examples, tools, practice material and project resources in one place.

## ZERO SESSION
[PPT Link](https://docs.google.com/presentation/d/1Gw6JMsPUvkZvm7psJs84A1y6KqxrPY-5/edit?usp=sharing&ouid=102189640680844426038&rtpof=true&sd=true)

## SYLLABUS
[Syllabus Link](https://drive.google.com/file/d/1AY7Gqu1uvb7T7ISgokrS9LxiDGrjPEuU/view?usp=sharing)

<p align="center">
  <img src="https://img.shields.io/badge/Academic%20Year-2026--2027%20ODD-1f6feb?style=for-the-badge">
  <img src="https://img.shields.io/badge/Semester-V-8250df?style=for-the-badge">
  <img src="https://img.shields.io/badge/Course-BCD515C-0a7f5a?style=for-the-badge">
  <img src="https://img.shields.io/badge/Hours-40-f59e0b?style=for-the-badge">
  <img src="https://img.shields.io/badge/Credits-03-e11d48?style=for-the-badge">
</p>

<p align="center">
  <b>Professional Elective Course · Department of AI&ML · Acharya Institute of Technology</b><br>
  <i>Learn the model → understand the architecture → use the tool → solve the problem → justify the trade-off.</i>
</p>

---

## 📌 Course Snapshot

| Item | Details |
|---|---|
| **Course Title** | NoSQL Databases |
| **Course Code** | BCD515C |
| **Course Type** | Professional Elective Course |
| **Semester** | V |
| **Academic Year** | 2026–2027 (ODD) |
| **Teaching Hours / Week** | L:T:P:S = **3:0:0:0** |
| **Total Pedagogy** | **40 Hours** |
| **Credits** | **03** |
| **CIE / SEE** | **50 / 50** |
| **SEE Duration** | **03 Hours** |
| **Examination** | Theory |

> **Official syllabus basis:** 5 modules × 8 hours = 40 hours. The course objectives focus on the need for NoSQL, MapReduce/Key–Value databases, Document databases and Graph database use cases.

---

# 🧭 Course Roadmap

```text
             WHY NoSQL?
                  │
                  ▼
       AGGREGATE DATA MODELS
                  │
                  ▼
     DISTRIBUTION + CONSISTENCY
                  │
                  ▼
         CAP + VERSION STAMPS
                  │
                  ▼
       MAPREDUCE + KEY–VALUE
                  │
          ┌───────┴────────┐
          ▼                ▼
     DOCUMENT           GRAPH
     DATABASES         DATABASES
          │                │
          └───────┬────────┘
                  ▼
       REAL-WORLD NoSQL DESIGN
```

---

# 🎯 Course Objectives

The syllabus expects students to:

- Understand the importance and need of NoSQL.
- Gain exposure to MapReduce and Key–Value databases.
- Understand fundamentals of Document Databases.
- Identify use cases where Graph databases are advantageous.

---

# 📚 Module-wise Syllabus

## 01 · Why NoSQL & Aggregate Data Models
**8 Hours · Textbook 1: Chapters 1, 2, 3**

### Why NoSQL
- The Value of Relational Databases
- Getting at Persistent Data
- Concurrency
- Integration
- A (Mostly) Standard Model
- Impedance Mismatch
- Application and Integration Databases
- Attack of the Clusters
- The Emergence of NoSQL

### Aggregate Data Models
- Aggregates
- Examples of Relations and Aggregates
- Consequences of Aggregate Orientation
- Summarizing Aggregate-Oriented Databases

### More Details on Data Models
- Relationships
- Graph Databases
- Schema-less Databases
- Materialized Views

**Suggested exploration:** MongoDB, JSON/document modelling, Neo4j.

---

## 02 · Distribution Models, Consistency & CAP
**8 Hours · Textbook 1: Chapters 4, 5, 6**

### Distribution Models
- Single Server
- Sharding
- Master–Slave Replication
- Peer-to-Peer Replication
- Combining Sharding and Replication

### Consistency
- Update Consistency
- Read Consistency
- Relaxing Consistency
- CAP Theorem

### Version Stamps
- Business Transactions
- System Transactions
- Version Stamps on Multiple Nodes

**Suggested exploration:** MongoDB Atlas, Cassandra, DynamoDB.

---

## 03 · MapReduce & Key–Value Databases
**8 Hours · Textbook 1: Chapters 7, 8**

### MapReduce
- Basic MapReduce
- Partitioning and Combining
- Composing MapReduce Calculations
- Two-Stage MapReduce Example
- Incremental MapReduce

### Key–Value Databases
- What is a Key–Value Store?
- Consistency
- Transactions
- Query Features
- Structure of Data
- Scaling

### Suitable Use Cases
- Session information
- User profiles
- Preferences
- Shopping cart data

### When Not to Use
- Relationships among data
- Multi-operation transactions
- Query by data
- Operations by sets

**Suggested exploration:** Redis, Hadoop MapReduce, DynamoDB.

---

## 04 · Document Databases
**8 Hours · Textbook 1: Chapter 9**

- What is a Document Database?
- Consistency
- Transactions
- Availability
- Query Features
- Scaling

### Suitable Use Cases
- Event Logging
- Content Management Systems
- Blogging Platforms
- Web Analytics / Real-Time Analytics
- E-Commerce Applications

### When Not to Use
- Complex transactions spanning different operations
- Queries against varying aggregate structure

**Suggested exploration:** MongoDB / MongoDB Atlas / MongoDB Compass.

---

## 05 · Graph Databases
**8 Hours · Textbook 1: Chapter 11**

- What is a Graph Database?
- Features
- Consistency
- Transactions
- Availability
- Query Features
- Scaling

### Suitable Use Cases
- Connected Data
- Routing
- Dispatch
- Location-Based Services
- Recommendation Engines

### Also Understand
- When graph databases should **not** be used.

**Suggested exploration:** Neo4j, Cypher, Neo4j Aura.

---

# 🧠 Course Outcomes

By the end of the course, students should be able to:

| CO | Expected capability | RBT |
|---|---|---|
| **CO1** | Explain concepts, architecture and data models of NoSQL databases. | L2 |
| **CO2** | Discuss distribution models, consistency mechanisms and CAP theorem. | L2 |
| **CO3** | Implement MapReduce programming and Key–Value databases for scalable processing/storage. | L3 |
| **CO4** | Demonstrate document database concepts and query mechanisms for suitable scenarios. | L3 |
| **CO5** | Apply graph database concepts and query techniques for connected-data applications. | L3 |

---

# 🧰 NoSQL Tool Directory

The `tools/` folder is intentionally designed to be updated throughout the semester.

| Tool | Model / Focus | Official Resources |
|---|---|---|
| **MongoDB** | Document | [Docs](https://www.mongodb.com/docs/manual/) · [University](https://learn.mongodb.com/) |
| **Redis** | Key–Value / Data Structures | [Docs](https://redis.io/docs/latest/) · [Quick Starts](https://redis.io/docs/latest/develop/get-started/) |
| **Apache Cassandra** | Distributed / Wide-Column | [Docs](https://cassandra.apache.org/doc/stable/) · [Quickstart](https://cassandra.apache.org/doc/stable/cassandra/getting-started/cassandra-quickstart.html) |
| **Amazon DynamoDB** | Key–Value + Document | [Docs](https://docs.aws.amazon.com/dynamodb/) · [Getting Started](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html) |
| **Neo4j** | Graph | [Docs](https://neo4j.com/docs/) · [Cypher](https://neo4j.com/docs/cypher-manual/current/) |
| **Hadoop MapReduce** | Distributed Processing | [Docs](https://hadoop.apache.org/docs/current/) · [MapReduce Tutorial](https://hadoop.apache.org/docs/stable1/mapred_tutorial.html) |

### ➕ Add a new tool

Update `tools/TOOLS.md` using:

```markdown
## Tool Name
- **Type:** Document / Key–Value / Wide-Column / Graph / Other
- **Official Website:** 
- **Documentation:** 
- **Learning Resource:** 
- **Best Module:** 
- **Student Activity:** 
- **Notes:** 
```

---

# 📝 Notes Management System

Each module has a dedicated folder:

```text
notes/
├── module-01/
├── module-02/
├── module-03/
├── module-04/
└── module-05/
```

Recommended files:

```text
module-01/
├── lecture-notes.md
├── one-shot-revision.md
├── diagrams.md
└── important-questions.md
```

### 🔄 Update workflow

```bash
git pull
# edit notes
git add .
git commit -m "Update Module 2 CAP theorem notes"
git push
```

### Naming convention

Use:

`M01_01_Why_NoSQL.md`

`M01_02_Aggregate_Models.md`

`M04_01_Document_Databases.md`

This keeps the repository easy to maintain and easy for students to navigate.

---

# 🎞️ Presentation Management

```text
slides/
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

# 🌐 E-Resources & Self-Learning

## 🟢 MongoDB — Module 1 & 4

- [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
- [MongoDB Tutorials](https://www.mongodb.com/docs/manual/tutorial/)
- [MongoDB University](https://learn.mongodb.com/)
- [MongoDB 5-Minute Interactive Tutorial](https://www.mongodb.com/docs/manual/tutorial/getting-started/)

**Recommended path:** Introduction → Documents → CRUD → Aggregation → Data Modelling → Indexes → Replication → Sharding.

---

## 🔴 Redis — Module 3

- [Redis Documentation](https://redis.io/docs/latest/)
- [Redis Quick Starts](https://redis.io/docs/latest/develop/get-started/)
- [Redis Data-Store Quick Start](https://redis.io/docs/latest/develop/get-started/data-store/)
- [Redis Tools](https://redis.io/docs/latest/operate/)

**Recommended path:** Keys → Strings → Hashes → Lists → Sets → Sorted Sets → Persistence → Transactions → Pub/Sub.

---

## 🟣 Apache Cassandra — Module 2

- [Cassandra Documentation](https://cassandra.apache.org/doc/stable/)
- [Cassandra Getting Started](https://cassandra.apache.org/doc/stable/cassandra/getting-started/)
- [Cassandra Quickstart](https://cassandra.apache.org/doc/stable/cassandra/getting-started/cassandra-quickstart.html)

**Recommended path:** Architecture → Replication → Partitioning → Data Modelling → CQL → Distributed operations.

---

## 🟠 Amazon DynamoDB — Modules 2 & 3

- [DynamoDB Documentation](https://docs.aws.amazon.com/dynamodb/)
- [Getting Started](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GettingStartedDynamoDB.html)
- [Learning Resources & Tools](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/AdditionalResources.html)

**Recommended path:** Tables → Items → Keys → Query/Scan → Indexes → Partitions → Consistency → Data modelling.

---

## 🔵 Neo4j — Module 5

- [Neo4j Documentation](https://neo4j.com/docs/)
- [Cypher Manual](https://neo4j.com/docs/cypher-manual/current/)
- [GraphAcademy](https://graphacademy.neo4j.com/)
- [Neo4j Fundamentals](https://graphacademy.neo4j.com/courses/neo4j-fundamentals/)
- [Cypher Fundamentals](https://graphacademy.neo4j.com/courses/cypher-fundamentals/)

**Recommended path:** Graph thinking → Nodes → Relationships → Properties → MATCH → CREATE → WHERE → Aggregation → Pattern traversal.

---

## 🟡 Hadoop MapReduce — Module 3

- [Apache Hadoop Documentation](https://hadoop.apache.org/docs/current/)
- [MapReduce Tutorial](https://hadoop.apache.org/docs/stable1/mapred_tutorial.html)

**Recommended path:** Mapper → Shuffle/Sort → Reducer → Combiner → Partitioner → WordCount → Multi-stage processing.

---

# 📖 Prescribed & Reference Books

### Prescribed Textbook
**Pramod J. Sadalage & Martin Fowler**  
*NoSQL Distilled: A Brief Guide to the Emerging World of Polyglot Persistence*, Pearson Addison Wesley, 2012.

### Reference Books
1. Dan Sullivan — *NoSQL For Mere Mortals*, 1st Edition, Pearson Education India, 2015.
2. Dan McCreary & Ann Kelly — *Making Sense of NoSQL: A Guide for Managers and the Rest of Us*, 1st Edition, Manning/Dreamtech Press, 2013.
3. Kristina Chodorow — *MongoDB: The Definitive Guide – Powerful and Scalable Data Storage*, 2nd Edition, O'Reilly Publications, 2013.

---

# 🧪 Student-Centric Learning

The course presentation proposes:

| Module | Participative | Experiential | Problem Solving | ICT / Tool |
|---|---|---|---|---|
| M1 | SQL vs NoSQL discussion | MongoDB Atlas exploration | Database selection | Atlas / simulators |
| M2 | CAP discussion | Replication & sharding | Distributed DB cases | MongoDB Atlas |
| M3 | MapReduce team discussion | MapReduce + Redis | Large-scale processing | Redis / MapReduce |
| M4 | Document schema discussion | CRUD, indexing, aggregation | Optimize document models | MongoDB Compass/Atlas |
| M5 | Graph application presentation | Neo4j graph modelling | Recommendation/network cases | Neo4j Desktop/Aura |

### 🚀 Augmented Course Project

**E-Commerce Platform — Polyglot Persistence Design**

Students can use generative AI to scaffold schemas/queries for different stores and, most importantly, **justify why each NoSQL type was selected for each sub-problem**.

---

# 📝 Assessment

The course presentation specifies:

- **CIE:** 50 marks
- **SEE:** 50 marks
- **Assignment:** Team-based mini project, assessed for 25 marks after scaling
- **T1/T2:** conducted at the specified syllabus-coverage stages
- **Course Project:** team-based; the syllabus suggests 2–4 students and use of any NoSQL software.

> Keep `question-bank/`, `projects/`, and `activities/` updated alongside the teaching progress.

---

# 🧩 Suggested Repository Workflow

```text
BEFORE CLASS
   ↓
Read module notes
   ↓
Open presentation
   ↓
Review e-resource
   ↓
CLASS
   ↓
Concept + discussion + demo
   ↓
HANDS-ON
   ↓
Tool / simulator / query
   ↓
AFTER CLASS
   ↓
One-shot revision + question bank
   ↓
PROJECT
   ↓
Apply + compare + justify
```

---

# 📂 Complete Repository Structure

```text
NoSQL-Databases-BCD515C/
│
├── README.md
│
├── slides/
│   ├── 00-zero-session/
│   ├── 01-module-01/
│   ├── 02-module-02/
│   ├── 03-module-03/
│   ├── 04-module-04/
│   └── 05-module-05/
│
├── notes/
│   ├── module-01/
│   ├── module-02/
│   ├── module-03/
│   ├── module-04/
│   └── module-05/
│
├── tools/
├── resources/
├── examples/
├── activities/
├── question-bank/
├── projects/
└── datasets/
```

---

# ⭐ Teaching Mantra

> **Don't just learn NoSQL tools. Learn to make a database choice and defend it.**

A strong NoSQL learner should be able to answer:

1. **Why NoSQL?**
2. **Which data model?**
3. **How will it scale?**
4. **What consistency is required?**
5. **Which database/tool fits the workload?**
6. **What are the trade-offs?**

---

<p align="center">
  <b>BCD515C · NoSQL Databases · Semester V · 2026–2027 ODD</b><br>
  <sub>Course repository designed for continuous notes, slides, tools, e-resources, activities and project updates.</sub>
</p>

