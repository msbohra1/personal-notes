# SQL

**Summary**: Notes on SQL engines, spatial SQL, and query optimization techniques for geospatial and data work.
**Last updated**: 2026-10-03

---

- [Optimizing DuckDB Spatial Queries](https://www.geomermaids.com/cookbook/duckdb-spatial/): Compares DuckDB's spatial join architecture to PostGIS — `RTREE_INDEX_SCAN` for single constants vs. the non-spilling `SPATIAL_JOIN` operator for joins, metric reprojection for accurate distances, and inlining bounding boxes to enable [[Data]] row-group pruning on Parquet. Keywords: DuckDB, spatial SQL, PostGIS, R-tree index, spatial join, Parquet
