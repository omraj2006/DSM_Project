📌 Exam Slot Allocation System (Graph Theory Based)

This project is a web-based implementation of an Exam Slot Allocation System using concepts from Graph Theory, specifically the Graph Coloring algorithm.

In real-world exam scheduling, some subjects cannot be placed in the same time slot due to student overlaps. This problem is modeled as a graph where:

Each subject is represented as a vertex
A conflict between two subjects is represented as an edge

The goal is to assign the minimum number of time slots such that no two conflicting subjects are scheduled at the same time.

🚀 What this project does
Allows users to add subjects (vertices)
Define conflicts between subjects (edges)
Visualizes the graph using an interactive network
Applies a Greedy Graph Coloring algorithm to assign slots
Displays optimized exam slots where no conflicts occur

🧠 Algorithm Used

We use a Greedy Graph Coloring approach with degree-based ordering, where:

Subjects with more conflicts are prioritized first
Each subject is assigned the lowest possible slot (color) that does not conflict with its neighbors

This helps in reducing the total number of slots required.

✨ Features
Interactive graph visualization
Input validation (no duplicate subjects or conflicts)
Prevention of invalid inputs (like self-conflicts)
Displays total number of slots required
Clear graph functionality for re-testing scenarios

🎯 Objective: To demonstrate how Discrete Mathematics concepts (Graph Coloring) can be applied to solve real-world problems like exam scheduling and resource allocation efficiently.

🛠️ Tech Stack
HTML, CSS, JavaScript
vis-network for graph visualization


