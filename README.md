## Hi there! Here's a few highlights from my Portfolio

### Apps

Created [Techmaps.fyi](http://techmaps.fyi/)

---

### Open Source Contributions

- **Bug Fixes**
  - Created a fix for a bug in a REST endpoint to ensure accurate error handling when force-deleting an already deleted ml model in Elasticsearch: [elastic/elasticsearch#107188](https://github.com/elastic/elasticsearch/pull/107188) (Language: Java)
  - Investigated JVM memory pressure related to outstanding bulk indexing requests in OpenSearch, and contributed a preparatory refactor by removing `ClusterState` references from `ConcreteIndices` to simplify object lifetimes and support further root-cause analysis:  
    [opensearch-project/OpenSearch#20454](https://github.com/opensearch-project/OpenSearch/pull/20454) (Java)
  - Fixed `TypeError` in `reify` when folding sparse arrays in Dask Bags: [dask/dask#12103](https://github.com/dask/dask/pull/12103) (Language: Python)
  - Modified Docker compose up command to respect `COMPOSE_REMOVE_ORPHANS` environment variable: [docker/compose#11462](https://github.com/docker/compose/issues/11462) (Language: Go)

- **Documentation**
  - Added instructions for resetting specific unstaged changes on Git: [git-flight-rules#160](https://github.com/k88hudson/git-flight-rules/issues/160)
