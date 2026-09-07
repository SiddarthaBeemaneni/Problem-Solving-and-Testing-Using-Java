# 📘 Week 3 — Java Collections, Date/Time & Sorting

> Introduces the Java Collections Framework and practical Java APIs, alongside continued algorithmic practice.

---

## 🗂️ Problems / Topics

| # | Problem / Topic | Java API Focus |
|---|---|---|
| 1 | Day of the Week | Date/Time API |
| 2 | Day of the Year | Date/Time API |
| 3 | Java ArrayList | Collections |
| 4 | Java Date and Time | Date/Time API |
| 5 | Java Priority Queue | Collections |
| 6 | Largest Number | Custom sorting |
| 7 | Number of Days Between Two Dates | Date/Time API |
| 8 | Sort the People | Custom sorting |

---

## 🧠 Skills Practiced

```mermaid
mindmap
  root((Week 3<br/>Skills))
    Collections
      ArrayList
      PriorityQueue
    Date & Time APIs
    Sorting
      Custom ordering
    String & Number Manipulation
    Collection-based Problem Solving
```

---

## 🔗 Topic Grouping

```mermaid
flowchart TB
    subgraph Collections
      ArrayList[Java ArrayList]
      PQ[Java Priority Queue]
    end
    subgraph DateTime[Date & Time]
      DOW[Day of the Week]
      DOY[Day of the Year]
      JDT[Java Date and Time]
      DBD[Number of Days Between Two Dates]
    end
    subgraph Sorting
      LN[Largest Number]
      STP[Sort the People]
    end
```

---

## 🧭 Suggested Practice Order

```mermaid
flowchart LR
    S1[ArrayList] --> S2[Sorting] --> S3[Date / Time] --> S4[Priority Queue] --> S5[Custom Ordering]
```

---

## 🎯 Learning Goal

Get comfortable with **Java's collection framework** and commonly used library classes, while continuing to sharpen algorithmic thinking.

---

## 📈 Where This Fits in the Journey

```mermaid
flowchart LR
    W1["Week 1\nJava Fundamentals"] --> W2["Week 2\nArray Practice"] --> W3["Week 3\nCollections & Date/Time"]:::current --> W4["Week 4\nArrays · Matrices · Strings"] --> W5["Week 5\nSliding Window · Subarrays"] --> W6["Week 6\nAdvanced Strings & Palindromes"]

    classDef current fill:#8a1538,color:#fff,stroke:#8a1538;
```