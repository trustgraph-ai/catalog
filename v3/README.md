
# TrustGraph knowledge cores

The 'v3' standard was introduced with TrustGraph 0.19, and reflects the
following changes:

- Graph embeddings extraction had a major refactor which greatly improved
  the resolution of the graph embeddings in search and GraphRAG pipelines.
- The structure of graph embeddings messages changed, allowing multiple
  graph embeddings to be used in a message as a performance improvement.
  This is not compatible with TG 0.18 or earlier.
  
Note!  Cores are compressed.  You should uncompress before
loading.  *.gz files are gzip compressed.  *.7z are 7-Zip compressed.
  
## Knowledge cores

- `nasa-challenger-report1.core.gz`: NASA's Challenger report volume 1.
- `etsi-ts-303-645.core.gz`: ETSI TS 303 645, standard for IoT consumer
  device security
- `uklaw-2024.core.7z` : UK legislation 2024.  From here:
  https://github.com/trustgraph-ai/uk-legislation-demo
- `mil-hdbk-516c.core.gz`: MIL-HDBK-516C, the DoD handbook on
  airworthiness certification criteria.
- `application-arp4754a-flight-critical.core.gz`: NASA document:
  Application of SAE ARP4754A to Flight Critical Systems.
