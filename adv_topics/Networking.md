# Networking Advanced Topic Presentations

Before your presentation, use this file to get your talk outline approved. Be
sure to provide an estimated time to spend on teach topic (totalling 45 minutes)
and be sure not to repeat any topics covered in previous presentations.

## Presentation 1
### Pirates

- Topic 1: Networking Overview: (5 minutes)
  - Server Networking
  - P2P Networking
- Topic 2: P2P Topologies - The Basics (5 minutes)
  - Unstructured
  - N-Dimensional Grid
  - Tree
  - Ring
  - Polyring
  - Distributed Hash Table
  - Hybrid
    - Hub and Spoke
- Topic 3: Hub and Spoke - The Details (5 minutes)
  - Why use it?
  - Why use Client-Server?
  - Spoke to Spoke Communication
  - Connectivity
- Topic 4: Challenges of P2P (10 minutes)
  - Network Management
    - Joining
    - Leaving
    - Detecting fails
  - Storage and Location of Data
    - Storing Data
    - Locating Data
    - Accessing Data
    - Removing Data
    - Detecing Bad Data
  - Consensus
- Topic 5: Solutions (15 minutes)
  - Solution by Topology
  - Solution by Protocol
  - Solution by Algorithm
- Topic 6: Key Points and Conclusion (5 minutes)

## Presentation 2
### Cuscuta

- Topic 1: UDP vs TCP (5 minutes)
  - What is UDP?
  - What is TCP?
  - What does TCP give us that UDP does not?
      - What do we need from TCP's framework?
      - What is going in our UDP packets?
      - How does rust help us out?
      - Sequencing
      - Packet age
  - What impact do these have on design?
      - Engineering ease
          - How are we handling the packets?
          - Data structures
- Topic 2: Latency (5 minutes)
  - Propogation delay
  - Transmission delay
  - Queue delay
  - Packet loss/misordering
  - How to resolve packets arriving not in order
- Topic 3: Serialization (5 minutes)
  - Why?
  - How?
  - Our implementation
- Topic 4: Client Server model (20 minutes)
    (Basic Overview - 5 minutes)
    - Basic overview
    - Authoritative Server
      - Anti-cheat
      - Uh-oh, latency
    (Client-side prediction - 10 minutes)
    - Client side prediction!
      - Rubber Banding
      - Sequencing
        - Re-prediction
        - Discrepancies after reconcilliation
    (Entity Interpolation - 5 minutes)
    - Entity interpolation
      - Server Time Step / Dead Reckoning + issues with dead reckoning for our game
      -  Entity Interpolation -> Basic example
      - Issues with Interpolation in fast-paced games
      - Lag compensation 
- Topic 5: Our implementation (10 minutes)
  - Current Status
  - Code Examples
  - Things that went well / Things we need to fix
  - Plans moving forward- Topic 1 ... (XX minutes):
