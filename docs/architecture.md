# Architecture

## System Overview
  - This app focuses on a fooad and grocery delivery solution.
  - Target users include restaurants, grocery stores, consumers.
  - The system will just facilitate a delivery of the package from source to the user.

## Goals
  - Scalability
  - 

## Non-Goals
  - Quick delivery
  -

## High-Level Architecture
The system follows a client-server architecture consisting of:

  - Web frontend (React)
  - Backend API (Java, spring)
  - PostgreSQL database
  - Redis cache

## Components 
### Frontend/Client
   - React
   - Allow the user to place orders and track them, allow the restaurants to manage menues and accept orders.
### Backend/Server
   - Java Spring
   - Maintains all the states and activities of the users both consumers and restaurants.
### Database/Data Layer
   - PostgreSQL
   - Users,restaurants,orders

## Data Flow
   
## API Design
  - REST

## Security Considerations
  - Auth
  - RBAC

## Deployment Architecture
  - Docker

## Scalability & Performance

## Reliability & Fault Handling

## Observability

## Trade-Offs & Decisions

## Limitations

## Future Improvements
