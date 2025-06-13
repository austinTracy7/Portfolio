```mermaid
flowchart TD
    A[Pandas DataFrame] -->|Upload| B1[Snowflake Table]

    B1 -->|Identify Columns to Improve| B2[Snowflake Table (With Flags)]
    B2 -->|Enrich the Data| B3[Snowflake Table (Enriched)]

    B3 -->|Return Enriched Results| C[Enriched Table]
    
    style A fill:#f9f,stroke:#333,stroke-width:1px
    style B1 fill:#bbf,stroke:#333,stroke-width:1px
    style B2 fill:#bbf,stroke:#333,stroke-width:1px
    style B3 fill:#bbf,stroke:#333,stroke-width:1px
    style C fill:#afa,stroke:#333,stroke-width:1px
```
