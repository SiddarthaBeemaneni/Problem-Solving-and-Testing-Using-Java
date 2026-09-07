# 📘 Week 6 — Advanced String & Palindrome Problem Solving

> Deep dive into string algorithms: rotations, palindromes, substring matching, and sliding-window techniques.

---

## 🗂️ Problems

| # | Problem | Technique |
|---|---|---|
| 1 | String Similarity | String comparison |
| 2 | Circular Palindromes | Rotation + palindrome (advanced) |
| 3 | Repeated Substring Pattern | Divisibility / substring construction |
| 4 | Two Strings | Common character detection |
| 5 | Rotate String | Substring / concatenation |
| 6 | Mars Exploration | Character comparison |
| 7 | Find All Anagrams in a String | Sliding window + frequency array |
| 8 | Palindrome Index | Two pointers |
| 9 | Find the Index of the First Occurrence in a String | Substring search |
| 10 | Longest Palindromic Substring | Expand around center |

---

## 🧠 Skills Practiced

```mermaid
mindmap
  root((Week 6<br/>Skills))
    String Traversal
    Character Frequency Counting
    Sliding Window
    Two Pointers
    Palindrome Checking
      Expand Around Center
    String Rotation
    Substring Searching
    Anagram Detection
    Pattern Matching
```

---

## 🔗 Pattern → Problem Map

```mermaid
flowchart LR
    A[Two Pointers / Center Expansion] --> A1[Palindrome Index]
    A --> A2[Longest Palindromic Substring]
    B[Frequency Arrays + Sliding Window] --> B1[Find All Anagrams in a String]
    C[Boolean / Frequency Arrays] --> C1[Two Strings]
    D[Substring / Concatenation] --> D1[Rotate String]
    D --> D2[Circular Palindromes]
    E[Direct Substring Matching] --> E1[Find the Index of the First Occurrence in a String]
    F[Divisibility + Substring Construction] --> F1[Repeated Substring Pattern]
    G[Direct Character Comparison] --> G1[Mars Exploration]
    G --> G2[String Similarity]
```

---

## 🚀 Advanced Topic: Circular Palindromes

Combines **string rotation** with **palindrome processing** — a significantly harder problem than the rest of the set.

```mermaid
flowchart TD
    S[Input String] --> R[Generate / Consider Rotations]
    R --> P{Is rotation a palindrome?}
    P -->|Naive check per rotation| N[O(n²) — too slow at scale]
    P -->|Optimized| M["Manacher's Algorithm +\nRange-based Processing"]
    M --> O[O(n) / O(n log n) solution]
```

---

## 🎯 Learning Goal

Build strong **string-algorithm fundamentals**, progressing from simple character comparisons to advanced **palindrome and substring techniques**.

---

## 📈 Where This Fits in the Journey

```mermaid
flowchart LR
    W1["Week 1\nJava Fundamentals"] --> W2["Week 2\nArray Practice"] --> W3["Week 3\nCollections & Date/Time"] --> W4["Week 4\nArrays · Matrices · Strings"] --> W5["Week 5\nSliding Window · Subarrays"] --> W6["Week 6\nAdvanced Strings & Palindromes"]:::current

    classDef current fill:#8a1538,color:#fff,stroke:#8a1538;
```