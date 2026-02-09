# Last-Mile Logistics Optimization via Vehicle Routing (VRP)

## Overview
This project models a real-world last-mile pharmaceutical delivery system as a **Capacitated Vehicle Routing Problem with Time Windows (CVRP-TW)**.  
The objective is to minimize fleet size and total travel time while satisfying delivery demand, vehicle capacity, and time-window constraints.

The optimization is formulated as a Mixed Integer Linear Program (MILP) and solved using **Constraint Programming with Guided Local Search** through **Google OR-Tools** to handle large-scale instances efficiently.

## Key Features
- Formulated delivery routing as **CVRP-TW optimization**
- Multi-day simulation across optimistic, pessimistic, and most-likely demand scenarios
- Fleet utilization minimization through vehicle activation penalty
- Constraint-based routing using **Google OR-Tools**
- Sensitivity analysis evaluating network resilience under traffic variability

## Methodology
- MILP formulation defining routing decisions, capacity constraints, and time windows
- Metaheuristic solution approach (Guided Local Search) for scalable routing optimization
- Multi-scenario evaluation comparing routing efficiency and fleet requirements
- Performance evaluation across nine operational days

## Results
- Efficient delivery plans requiring **3–4 vehicles** on average from a 15-vehicle fleet
- Robust solutions maintained **100% service levels** under both optimistic and pessimistic conditions
- Demonstrated resilience to increased travel-time variability while maintaining operational feasibility

## Technologies Used
- Python
- Google OR-Tools
- Pandas / NumPy
- Optimization Modeling (MILP, Constraint Programming)

## Repository Contents
- Project report (problem formulation, experiments, and findings)
- Optimization implementation (VRP solver using OR-Tools)
- Scenario analysis and routing outputs
