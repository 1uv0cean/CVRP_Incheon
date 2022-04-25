# CVRP_Incheon
Incheon Recycling Waste Capacitated Vehicle Routing Problem (CVRP)   

Logistics: optimize delivery of goods by minimizing the total distance. The notebook contains an example of CVRP implemented using CPLEX as solver and map visualization with Folium.   

- From address -> get latitude and longitude with **Google Geocoding API**
- Create distance matrix calculating distances with **Google Distance API** (store duration/distance and polylines for plotting)
- Solve optimisation problem with **docplex** (IBM Decision Optimization CPLEX Modeling for Python)
- Display results with **Folium** and the **TimestampedGeoJson** plugin

