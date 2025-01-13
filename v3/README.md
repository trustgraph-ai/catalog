
# TrustGraph knowledge cores

The 'v3' standard was introduced with TrustGraph 0.19, and reflects the
following changes:

- Graph embeddings extraction had a major refactor which greatly improved
  the resolution of the graph embeddings in search and GraphRAG pipelines.
- The structure of graph embeddings messages changed, allowing multiple
  graph embeddings to be used in a message as a performance improvement.
  This is not compatible with TG 0.18 or earlier.
  
Note!  Cores are compressed with gzip.  You should uncompress before
loading.
  
## Knowledge cores

- `nasa-challenger-report1.core.gz`: NASA's Challenger report volume 1.
- `etsi-ts-303-645.core.gz`: ETSI TS 303 645, standard for IoT consumer
  device security

