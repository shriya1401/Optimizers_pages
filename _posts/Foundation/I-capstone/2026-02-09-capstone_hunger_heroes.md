---
toc: True
layout: post
title: "Hunger Heroes"
description: A Design-Based Research (DBR) capstone project tackling food insecurity through innovative technology. Real-time food donation matching, graph-based proximity algorithms, and ML-powered demand prediction.
courses: {'csse': {'week': 25}}
type: capstone
categories: [Capstone]
permalink: /capstone/hunger-heroes
---

## Project Overview

**Hunger Heroes** is a DBR capstone project addressing food insecurity by connecting food donors with recipients through intelligent routing and real-time notifications.

**Team:** Ahaan, Shaurya, Arnav
**Status:** In Development

## Problem Statement

Food insecurity affects millions while significant amounts of food go to waste. There is a disconnect between food donors (restaurants, grocery stores, individuals) and those in need. Current systems lack real-time matching and efficient routing.

## Design / Intervention

A web platform that uses graph-based proximity algorithms and ML-powered demand prediction to match food donations with recipients in real-time.

### Key Features

- **Real-time food donation matching system** - Connects donors with nearby recipients instantly
- **Graph-based proximity algorithm** - Uses graph data structures for efficient routing and nearest-neighbor matching
- **ML-powered demand prediction** - Machine learning model predicts demand patterns to optimize distribution
- **Database integration** - SQLite/PostgreSQL for persistent storage of users, donations, and routing data
- **Real-time notifications** - Alerts recipients when matching donations are available
- **Interactive frontend** - JavaScript-based UI for browsing, donating, and receiving

## Technical Stack

| Component | Technology |
|-----------|------------|
| Backend | Python, Flask, RESTful APIs |
| Frontend | JavaScript |
| Database | SQLite / PostgreSQL |
| ML Model | Demand prediction (Python) |
| Data Structure | Graph (proximity/routing) |
| Deployment | TBD |

## DBR Iteration Cycles

### Cycle 1: Prototype
- Basic donor/recipient registration
- Simple matching algorithm
- Database schema design
- Initial frontend wireframes

### Cycle 2: Refinement
- Graph-based proximity matching
- ML model training on sample data
- User feedback collection
- UI/UX improvements

### Cycle 3: Deployment
- Full deployment with real-time notifications
- Performance optimization
- User acceptance testing
- Design principles documentation

## Impact

- Reduce food waste by connecting surplus with need
- Support UN SDG 2: Zero Hunger
- Produce reusable design principles for community matching platforms
- Demonstrate advanced CS concepts (graphs, ML, databases) in a real-world context
