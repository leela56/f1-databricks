# Formula 1 Data Engineering Pipeline

End-to-end data engineering project that ingests, transforms, and analyzes Formula 1 race data using Databricks and PySpark.

## What It Covers

- Ingests raw F1 race data (circuits, drivers, lap times, results, pit stops) from the Ergast API
- - Applies Bronze to Silver to Gold transformations using the Databricks Medallion Architecture
  - - Stores processed data in Delta Lake tables for reliable, versioned access
    - - Produces race analytics: driver standings, constructor rankings, lap performance
     
      - ## Tech Stack
     
      - - Platform: Databricks
        - - Processing: PySpark, Spark SQL
          - - Storage: Delta Lake
            - - Language: Python
              - - Source: Ergast F1 Developer API
               
                - ## Setup
               
                - 1. Import notebooks into Databricks workspace
                  2. 2. Attach to a cluster (Databricks Runtime 10.4+)
                     3. 3. Run ingestion, then transformation, then analysis notebooks
