```mermaid
flowchart TD
    A[Pandas DataFrame\n(Read from Source)] --> B[Insert into Snowflake Table]

    B --> C[Batch Job 1:\nIdentify Items for Improvement]
    C -->|Adds 'needs_improvement' column| D[Snowflake Table\n(With Improvement Flags)]

    D --> E[Batch Job 2:\nEnrich Data Based on Flags]
    E --> F[Snowflake Table\n(Final Enriched Version)]

    F --> G[Return Enriched Results\n(Back to Application or Export)]
    
    style A fill:#f9f,stroke:#333,stroke-width:1px
    style B fill:#bbf,stroke:#333,stroke-width:1px
    style C fill:#ccf,stroke:#333,stroke-width:1px
    style D fill:#bbf,stroke:#333,stroke-width:1px
    style E fill:#ccf,stroke:#333,stroke-width:1px
    style F fill:#bbf,stroke:#333,stroke-width:1px
    style G fill:#afa,stroke:#333,stroke-width:1px
```
