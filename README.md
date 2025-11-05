# 📍 C++ Route Planner for Maharashtra

A C++ console application that models the transportation network of 36 major districts in Maharashtra. It uses graph algorithms (Dijkstra's and Prim's) to find optimal routes, calculate travel costs, and simulate a ticket booking process.

*(Suggestion: Record a short terminal session and save it as a GIF. You can add it here for a great visual demonstration!)*
`![Demo GIF of the Route Planner](demo.gif)`

---

## 🚀 Features

* **📍 Shortest Path (Dijkstra's):** Finds the fastest, shortest travel path between any two stations.
* **🎫 Ticket Booking:** Simulates a booking process by calculating travel costs (at 3.5 RS/km) and recording passenger details with a live timestamp.
* **🌳 Minimum Spanning Tree (Prim's):** Calculates the minimum total distance required to connect *all* 36 stations in the network, ideal for planning infrastructure.
* **🚉 Station Directory:** Displays a complete, easy-to-read list of all 36 stations and their corresponding codes.
* **🗺️ Network Visualization:**
    * **Adjacency Matrix:** Displays the raw 36x36 graph matrix.
    * **ASCII Map:** Provides a simple text-based map of the station network.

---

## ⚙️ How to Compile and Run

You can compile and run this program using any standard C++ compiler.

1.  **Clone or Download** the `main.cpp` file.
2.  **Open your terminal** and navigate to the directory.
3.  **Compile the code** (e.g., using `g++`):
    ```bash
    g++ main.cpp -o route_planner
    ```
4.  **Run the application:**
    ```bash
    ./route_planner
    ```
    *(On Windows, just type `route_planner`)*

---

## 🖥️ Interactive Menu

Once running, you will be greeted with a simple menu:

1.  **Display all stations with their station_code:** Lists all 36 stations.
2.  **Display adjacency matrix:** Shows the 36x36 graph matrix.
3.  **Travel to all stations with min cost (Prim's):** Calculates the Minimum Spanning Tree.
4.  **Display map of all station:** Shows the ASCII art map.
5.  **Travel from one to another station (Dijkstra's):** Finds the shortest path and allows for ticket booking.

