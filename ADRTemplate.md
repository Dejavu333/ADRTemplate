# Architectural Decision Records
___
## <span style="color:green;">Lifecycle 
    - Big-bang
    - Code-and-fix
    - Waterfall
    - Spiral
        - Devops Lifecycle
___
## <span style="color:green;">Repository
    - Monorepo
    - Multirepo
___
## <span style="color:green;">Data Desintegrators
    - Some data requires frequent read access, while another requires high-frequency write access.
    - Easier to enforce compliance with regulations that specify how certain types of data should be handled
    - Geographical Distribution
    - Technology Stack Variation
___
## <span style="color:green;">Service Desintegrators
    - Part of the system has higher load
    - Part of the system needs much more security
    - Part of the system evolves in a slower/faster pace
___
## <span style="color:green;">Interprocess Communication
    - Syncronous
        - Direct Call
        - Remote Call
            - REST
            - gRPC
            - GraphQL
            - SOAP

    - Asyncronous
        - Queue
        - File
        - Eventstore 
---
## <span style="color:green;">Data Access
    - Through Shared Database
    - Through Owner
    - CQRS
    - API Composition
    - Through Replica
---
## <span style="color:green;">Deployment
    - Monolith
    - Distributed
---
## <span style="color:green;">Coordination
    - Orchestrated
    - Choreographed
    - Free4All
---
## <span style="color:green;">Consistency
    - Eventual
    - Atomic
---
## <span style="color:green;">Requirements

#### Functionality
    - Book Rooms
    - Follow Profiles

#### Cost
    - Development
    - Maintenance
    - Operation

#### Performance
    - Load Balancing
    - Caching
    - Asynchronous Processing
    - Lazy Loading
    - Eager Loading

#### Maintainability/Alterability
    - Decision Records
        - ADR (Architectural Decision Record)
        - DDR (Design Decision Record)

    - Documentation
        - OpenAPI
            - Swagger

#### Scalability
    - XYZ Axis Scaling
    - Auto Scaling
    - Service Discovery

#### Testability
    - Unit Test
    - Integration Test
    - End-to-End Test
        - Consumer Driven Contract Test   
        - Chaos Test
        - Penetration Test
        - Fuzz Test
        - Soak Test
        - Stress Test
        - Spike Test
        - Smoke Test
        - Regression Test
    - Static Code Analysis
    - Fitness Functions

#### Security
    - Authentication
    - Authorization
    - Validation
    - Hack Prevention
        - Against Malware
        - Against Reverse Engineering
        - Against Social Engineering
        - Against Injections
        - Against CSRF

#### Observability
    - Monitoring
        - Collect Data
            - Traces
            - Metrics
            - Logs  
            - Push Model
            - Pull Model
        - Store Data
        - Use Data
            - Forecasting
            - Visualization
            - Alerting

#### Resiliency
    - Auto Healing
    - Circuit Breaker
    - Bulkhead
    - Retry
    - Timeout

#### Portability
    - Containerization
        - Docker
        - Kubernetes
        - OpenShift
    - VM
    - Serverless
---
## <span style="color:green;">Anti-patterns
    - Distributed Monolith
    - Distributed Transaction
    - No Clear Boundaries
    - No Clear Ownership of Data
    - Shared Database
    - Shared Code
    - Chatty Communication
    - No Versioning