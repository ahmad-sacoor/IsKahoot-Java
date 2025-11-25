# IsKahoot Distributed Quiz Game (Java)

This repository contains the documentation and structure overview of a distributed multiplayer quiz system developed in Java.  
The full source code will be added after academic submission is completed.

## Overview

IsKahoot is a distributed client–server quiz game where multiple players connect to a central server, participate in timed questions, and compete for points.  
The system uses TCP sockets, dedicated threads for each client, and custom synchronization logic to coordinate rounds and scoring.

## Key Features
- Client–server architecture using TCP sockets  
- Multithreading with per-client handler threads  
- Custom synchronization: barriers, condition variables, modified CountDownLatch  
- Timed rounds with coordinated answer collection  
- Thread-safe shared state  
- JSON question loading  
- GUI client  
- Modular server and client design

## Repository Status
To comply with academic integrity guidelines, the source code will be published after evaluations are completed (expected late January 2026).
