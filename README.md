# Graph Algorithms in Real-World Applications  
**Course:** ENCA351 — Design and Analysis of Algorithms (Lab Assignment 3)  
**Name:** Kartik Singh  
**Semester:** V  

---

## 📘 Overview
This project demonstrates how classical **graph algorithms** are applied to real-world scenarios.  
The notebook implements and analyzes four problems:

| No. | Problem | Algorithm | Type |
|-----|----------|------------|------|
| 1️⃣ | Social Network Friend Suggestion | BFS / DFS | Unweighted Graph |
| 2️⃣ | Route Finding (Google Maps) | Bellman–Ford | Weighted Directed Graph |
| 3️⃣ | Emergency Response Routing | Dijkstra’s Algorithm | Weighted Graph (Positive Edges) |
| 4️⃣ | Network Cable Installation | Minimum Spanning Tree (Kruskal / Prim) | Undirected Weighted Graph |

Each problem includes:
- Python implementation  
- Realistic sample graph data  
- Profiling (time and memory)    
- Analysis of complexity and scalability  

---

## ⚙️ How to Run (Google Colab / Local)
### 🟢 On Google Colab
1. Upload the notebook file `graph_realworld.ipynb` to Colab.  
2. Run the setup cell (install dependencies):  
   ```python
   !pip install matplotlib networkx memory_profiler
