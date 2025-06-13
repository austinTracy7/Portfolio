```mermaid
flowchart TD
    A[Pandas DataFrame] -->|Upload| B[Snowflake Table]

    B -->|Identify Columns to Improve| B[Snowflake Table]
    B -->|Enrich the Data| B[Snowflake Table]

    B -->|Return Enriched Results| C[Enriched Table]
    
    style A fill:#f9f,stroke:#333,stroke-width:1px
    style B fill:#bbf,stroke:#333,stroke-width:1px
    style C fill:#afa,stroke:#333,stroke-width:1px
