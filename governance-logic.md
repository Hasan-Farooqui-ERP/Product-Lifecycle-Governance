```mermaid
graph TD
    A[Customer Change Request] --> B{Impact Assessment}
    B -- "< 8 Hours" --> C[Absorb in Current Sprint]
    B -- "8-80 Hours" --> D[Last Sprint / Cost Addition]
    B -- "> 80 Hours" --> E[New Project Phase]
    
    subgraph "Engineering Guardrail"
    E --- F[Protects Team Velocity & System Stability]
    end

    style E fill:#f96,stroke:#333
    style C fill:#9f9,stroke:#333```
