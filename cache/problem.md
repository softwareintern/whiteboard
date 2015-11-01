# cache
Imagine a web server for a simplified search engine. This system has 100 machines to respond to search queries, which may then call out using processSearch(string query) to another cluster of machines to actually get the result. The machine which will always respond to the same request. The method processSearch is very expensive. Design a caching mechanism fer the most recent queries. Be sure to explain how you would update the cache when data changes.

## sources
  - CTCI 9.4 pg. 145
