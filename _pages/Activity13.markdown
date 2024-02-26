---
layout: post
title: "Activity 13: Graph Traversal"
categories: Activity Graph DFS BFS
---

## Learning Goals

You will work towards being able to...

1. Familiarize yourself with common algorithms (Depth \& Breadth First Search)

2. Translate problem specifications into graph problems to be solved with standard algorithms.

## Instructions
Work with your groups on the following problems. You may work on them in any order:

1. **Articulate a Plan**: Let's dig a bit further into finding articulation points/cut-vertices in a graph. Draw a DFS tree starting at A, and annotate that tree with (1) the depth of each node within the tree, (2) dashed lines for the backward edges, and finally (3) the lowest depth of a neighbor of that node (including backward edges). Compare these to the conditions of of being an articulation vertex outlined in Skiena! Write out pseudocode for this *specific* articulation vertex finding algorithm (not the genericized version Skiena gives you to demonstrate that it's a variant of BFS!) [^1]

<img src="{{ site.url }}/assets/imgs/articulation.png" width="700" />

2. **Two-Tabled Wedding** (Skiena 7-15): You are organizing seating for a wedding where all guests in a list $V$ must be organized into two tables. You also have a list $E$ of pairs of people who hate each other. Discuss how you might, if possible, construct a table assignment that avoids any enemies being at the same table.

**Hint**: Think back to the problem specifications from your reading!

#### Submission
Submit an artifact of your work for problem 1 or 2.

---
[^1]: I would add a bit of flavor to this problem (perhaps something about oil pipelines or critical telecommunications infrastructure), but I really need to be clear that COMP221 does not officially endorse any crimes. 
