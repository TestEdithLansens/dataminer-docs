---
uid: Configuring_Elasticsearch_Database
---

# Configuring the Elasticsearch database (Linux)

> [!IMPORTANT]
> Elasticsearch is **only supported up to version 6.8**. We therefore recommend using [Storage as a Service](xref:STaaS) instead, or if you do want to continue using self-hosted storage, using [dedicated clustered storage](xref:Dedicated_clustered_storage) with OpenSearch or the Amazon OpenSearch Service on AWS.

To configure a separate Elasticsearch instance (version 6.8) on Linux, you may need to adapt the *Elasticsearch.yml* as well as several other files before you start the Elasticsearch service. For more information about these settings, see [Configuring Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/6.8/settings.html).

The most important of these settings can be found on the page [Important Elasticsearch configuration](https://www.elastic.co/guide/en/elasticsearch/reference/6.8/important-settings.html).

> [!IMPORTANT]
> The JVM Heap Space must be set to a value larger than the default 1 GB on production systems. To configure this, see [Setting the heap size](https://www.elastic.co/guide/en/elasticsearch/reference/6.8/heap-size.html).
