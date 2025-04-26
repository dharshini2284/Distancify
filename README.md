# Distancify

A C++ project that helps find the most efficient way to deliver packages to various destinations while minimizing the total distance traveled. The delivery network is represented using a **graph structure with an unordered map**, and **Prim’s algorithm** is implemented to compute the **Minimum Spanning Tree (MST)**, ensuring the least overall delivery cost.

---

## 🚀 Features

- **Graph Representation**: Nodes and edges model the delivery locations and distances between them.
- **Custom Node and Edge Classes**: Enables flexible, efficient graph creation and manipulation.
- **Prim’s Algorithm Implementation**: Efficiently computes the Minimum Spanning Tree to minimize the total delivery distance.
- **User Input**: Dynamically enter nodes (destinations) and edges (routes with distances).
- **Priority Queue**: Used for selecting the next minimum weight edge efficiently.

---

## 🛠️ Technologies Used

- **C++** (Standard Library)
  - `unordered_map`, `priority_queue`, `set`, `vector`, `algorithm`
- **Object-Oriented Programming** (Classes for Node and Edge)
- **Greedy Algorithm** (Prim's Algorithm)

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/dharshini2284/Distancify.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Distancify
   ```
3. Compile the code:
   ```bash
   g++ -o distancify distancify.cpp
   ```
4. Run the executable:
   ```bash
   ./distancify
   ```

---

## 📋 Input Format

- Enter the number of nodes.
- Enter each node's name.
- Enter the number of edges.
- For each edge: input the starting node, ending node, and distance (weight).

Example:
```
Enter the number of nodes: 4
Enter node names:
A
B
C
D
Enter the edges and weights (from to weight):
A B 5
B C 10
A C 3
C D 4
```

---

## 📈 Output Example

```
From: A To: C Distance: 3
From: C To: D Distance: 4
From: A To: B Distance: 5
Total Minimum Spanning Tree Weight: 12
```

---

## 🧐 Concepts Demonstrated

- **Minimum Spanning Tree (MST)** for network optimization
- **Priority Queue usage** for efficient minimum selection
- **Graph traversal and management**
- **Object-oriented programming design**

---

## 📌 Repository Link

🔗 [Distancify GitHub Repository](https://github.com/dharshini2284/Distancify)

---


