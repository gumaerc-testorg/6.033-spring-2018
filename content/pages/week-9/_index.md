---
content_type: page
title: 'Week 9: Distributed Systems Part II'
uid: aa415ef7-5752-19ee-a10a-fb9dc2dbef65
---

Lecture 16: Atomicity via Logging
---------------------------------

### Lecture 16 Outline

1.  Introduction
2.  Motivating Example
3.  Basic Idea
4.  How to Use a Log for Transactions
5.  Performance of Log
6.  Cell Storage
7.  Performance of Log + Cell Storage
8.  Improving Performance
9.  What about Un-undo-able Actions?
10.  Summary

*   [Detailed Outline]({{< baseurl >}}/pages/week-9/lecture-16-outline)

### Lecture Slides

*   [Lecture 16 Slides: Atomicity via Logging (PDF)]({{< baseurl >}}/resources/mit6_033s18lec16)

### Reading

*   Book section 9.3

Recitation 16: Log-Structured File System (LFS)
-----------------------------------------------

*   Read ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)"[Log-structured File Systems (PDF)](http://pages.cs.wisc.edu/~remzi/OSTEP/file-lfs.pdf)" by R. & A. Arpaci-Dusseau
*   [Log-Structured File System (LFS) Assignment]({{< baseurl >}}/pages/week-9/log-structured-file-system-lfs-assignment)

Hands-on Assignment 6: Write Ahead Log (WAL) System
---------------------------------------------------

(Not available to OCW users.)

Lecture 17: Fault Tolerance: Isolation
--------------------------------------

### Lecture 17 Outline

1.  Introduction
2.  Serializability
3.  Conflict Serializability
4.  Conflict Graphs
5.  Interlude
6.  Two-phase Locking (2PL)
7.  Performance Improvement: Reader-Writer locks
8.  Another Possible Performance Improvement: Giving up on Conflict Serializability
9.  Summary

*   [Detailed Outline]({{< baseurl >}}/pages/week-9/lecture-17-outline)

### Lecture Slides

*   [Lecture 17 Slides: Fault Tolerance: Isolation (PDF)]({{< baseurl >}}/resources/mit6_033s18lec17)

### Reading

*   Book sections 9.4 before 9.4.1 and 9.5

Recitation 17: Databases
------------------------

*   Read "[Concurrency Control and Recovery](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.38.1437)" by M. J. Franklin
*   [Databases Assignment]({{< baseurl >}}/pages/week-9/databases-assignment)

Tutorial 9: \[No Tutorial this Week\]
-------------------------------------