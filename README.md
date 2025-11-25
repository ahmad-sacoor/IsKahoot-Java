# IsKahoot Distributed Quiz Game (Java)

This repository contains the documentation and structure overview of a distributed multiplayer quiz system developed in Java.  
This is a final-year, first-semester university project. 

## Overview

IsKahoot is a distributed client-server quiz game where multiple players connect to a central server, participate in timed questions, and compete for points.  
The system uses TCP sockets, dedicated client-handler threads, and custom synchronization logic to coordinate game rounds and scoring.

## Key Features
- Client–server architecture using TCP sockets  
- Multithreading with per-client handler threads  
- Custom synchronization structures, inspired by the course specification (barriers, condition variables, modified CountDownLatch)  
- Timed rounds and coordinated answer collection  
- Thread-safe shared game state and centralized score tracking  
- JSON-based question loading  
- GUI client for player interaction  
- Modular design separating server, client, and shared components

## Repository Status
To comply with academic integrity guidelines, the source code and full implementation will be published once the academic evaluation period ends (expected late January 2026).
