[README.md](https://github.com/user-attachments/files/24691676/README.md)
# Pakistan's Smart Travel Planner (DSA Semester Project)

## 1. Problem Statement
Finding the optimized travel route between major cities in Pakistan is a common logistical challenge. This project uses **Dijkstra's Algorithm** to calculate the most efficient path based on either distance (km) or cost (PKR), simulating a real-world bus terminal network (like Daewoo or Faisal Movers).

## 2. Core Features
- **Interactive Geo-Maps**: Uses Folium to display 17+ Pakistani hubs on a real-world map.
- **Shortest Path Calculation**: Uses Dijkstra's algorithm for path optimization.
- **Real Data**: Accurate distances and PKR ticket pricing for major terminals.
- **Visual Feedback**: The calculated path is highlighted in red on the interactive map.
- **Human-Readable Logic**: Modular Python code focused on Data Structures & Algorithms.

## 3. Algorithm Details

### Dijkstra's Algorithm
The core engine of this project. It ensures that even in a complex network with 17 cities, the system always finds the mathematically optimal "shortest" path.
- **Time Complexity**: O((V + E) log V) using a Min-Priority Queue.
- **Space Complexity**: O(V + E) to store the adjacency list.

## 4. Technology Stack
- **Python**: Core logic.
- **Streamlit**: Modern Web Interface.
- **Folium**: Geographic Visualization.
- **Heapq**: Built-in Python library for the Priority Queue.

## 5. How to Run
1. Install dependencies:
   ```bash
   pip install streamlit folium streamlit-folium pandas
   ```
2. Launch the application:
   ```bash
   python -m streamlit run travel_planner/app.py
   ```

## 6. Project Structure
- `graph.py`: Custom Adjacency List implementation.
- `algorithms.py`: Dijkstra & BFS logic.
- `planner.py`: High-level management class.
- `app.py`: Streamlit & Folium UI.

---
**Developed By: M.Anas**
