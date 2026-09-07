# 📘 Week 5 — Strings, Subarrays & Sliding Window

> Important string and subarray patterns: Kadane's algorithm, sliding windows, pattern matching, parsing, and circular-array techniques.

---

## 🗂️ Problems

| # | Problem | Technique |
|---|---|---|
| 1 | Maximum Sum Circular Subarray | Kadane's algorithm (circular) |
| 2 | Alternating Characters | Traversal / counting |
| 3 | Find and Replace Pattern | Mapping / bijection |
| 4 | Maximum Subarray | Kadane's algorithm |
| 5 | String to Integer (atoi) | Parsing |
| 6 | Subarray Division | Fixed-size sliding window |
| 7 | Substring Without Repeating Characters | Sliding window |
| 8 | The Max Subarray | Kadane's algorithm |

---

## 🧠 Skills Practiced

```mermaid
mindmap
  root((Week 5<br/>Skills))
    Kadane's Algorithm
    Circular Subarrays
    Sliding Window
      Fixed size
      Variable size
    Frequency / Count Arrays
    String Parsing
    Pattern Matching
    Two Pointers
    Subarray Sum
    Edge Case Handling
```

---

## 🔗 Pattern → Problem Map

```mermaid
flowchart LR
    A[Kadane's Algorithm] --> A1[Maximum Subarray]
    A --> A2[The Max Subarray]
    B["Circular Max = Total − Min Subarray"] --> B1[Maximum Sum Circular Subarray]
    C[Sliding Window] --> C1[Substring Without Repeating Characters]
    C --> C2[Subarray Division]
    D[Mapping / Bijection] --> D1[Find and Replace Pattern]
    E[Parsing] --> E1[String to Integer atoi]
    F[Traversal / Counting] --> F1[Alternating Characters]
```

---

## 🪜 From Brute Force to Optimal

```mermaid
flowchart LR
    BF[Brute Force\nO(n²) or O(n³)] -->|recognize pattern| OPT[Optimized\nO(n) via Kadane / Sliding Window]
```

---

## 🎯 Learning Goal

Recognize common **interview patterns** and improve the ability to optimize brute-force solutions into **linear or near-linear algorithms**.

---

## 📈 Where This Fits in the Journey

```mermaid
flowchart LR
    W1["Week 1\nJava Fundamentals"] --> W2["Week 2\nArray Practice"] --> W3["Week 3\nCollections & Date/Time"] --> W4["Week 4\nArrays · Matrices · Strings"] --> W5["Week 5\nSliding Window · Subarrays"]:::current --> W6["Week 6\nAdvanced Strings & Palindromes"]

    classDef current fill:#8a1538,color:#fff,stroke:#8a1538;
```