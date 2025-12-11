# Fantasy Sports – Frontend Integration Guide

This repository contains the frontend file `index.html` that will be used to interact with all microservices:

- Player Service (Sasha)
- Team Service
- Performance Tracking Service
- Leaderboard Service (optional)

## Workflow for Teammates

1. Open the `index.html` file.
2. Add your microservice API base URL:
   - TEAM_API_BASE
   - PERFORMANCE_API_BASE
3. Add your fetch calls inside the appropriate UI sections.
4. Commit and push your changes to GitHub.
5. Notify Sasha when your integration is completed.

## Deployment

Sasha will deploy (or try at least) the final combined `index.html` to Azure once all microservices are connected.
Do NOT upload this file to Azure before integration is 100% complete.
