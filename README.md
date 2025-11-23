# Graphical Resource Allocation Graph (RAG) Simulator  
A Python Tkinter-based graphical simulator to create, visualize, and analyze Resource Allocation Graphs (RAG) used in Operating Systems for deadlock detection.

## Features
- Add **Process Nodes (P1, P2, …)**  
- Add **Resource Nodes (R1, R2, …)**  
- Create **Request & Allocation Edges**  
- Visual, interactive canvas for graph display  
- **Cycle Detection using DFS**  
- Cycles (deadlocks) get highlighted in **red**  
- Easy-to-use GUI buttons and dialogs

---

## GUI Overview
The application window includes:
- A large **canvas** where processes & resources appear  
- Buttons to:
  - Add Process  
  - Add Resource  
  - Add Edge  
  - Detect Deadlock  

Nodes are automatically positioned without overlap.

---

## Tech Stack
- **Python 3**
- **Tkinter (GUI)**
- Standard libraries only (no external dependencies)

---

## Installation
1. Install Python 3.x  
2. Save the program as `rag_gui.py`  
3. Run:


