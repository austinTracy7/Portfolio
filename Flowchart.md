```mermaid
flowchart TD
    A[Pandas DataFrame] -->|Upload| B[Snowflake Table]

    B -->|1st Identify Columns to Improve in Batch 2nd Enrich Accordingly| B[Snowflake Table]
    B -->|Return Enriched Results| C[Enriched Table]
    
    style A fill:#f9f,stroke:#333,stroke-width:1px
    style B fill:#bbf,stroke:#333,stroke-width:1px
    style C fill:#afa,stroke:#333,stroke-width:1px
```
