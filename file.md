
# Full-Text Search

**Full-text search is meant to search large amounts of text. For example, a search engine will use a full-text search to look for keywords in all the web pages that it indexed. The key to this technique is indexing.**

There are three types of search engines  
    **<em>1.Elastic Search  
    2. Solr  
    3.Lucene<em>**

## Elastic search
    Elasticsearch is a distributed search and analytics engine built on Apache Lucene. Since its release in 2010, Elasticsearch has quickly become the most popular search engine and is commonly used for log analytics, full-text search, security intelligence, business analytics, and operational intelligence use cases.

    Elasticsearch allows you to store, search, and analyze huge volumes of data quickly and in near real-time and give back answers in milliseconds. It's able to achieve fast search responses because instead of searching the text directly, it searches an index.

    Overview. Full-text search queries and performs linguistic searches against documents. It includes single or multiple words or phrases and returns documents that match search conditions. ElasticSearch is a search engine based on Apache Lucene, a free and open-source information retrieval software library.
    
    Both MySQL and Elasticsearch provide a powerful capability of full-text search. If your system is using MySQL as the data store, the feature of full-text search can be quickly enabled by creating full-text indexes for the target data fields.

### Benefits 
- lots of search options
- High performance
- Easily Scalable  

### Current users
- Linkedin
- Facebook
- eBay
- Wikipedia
- StackOverflow
- Quora

***
## Solr

    Solr is an open-source search platform that is used to build search applications. It was built on top of Lucene (a full-text search engine). Solr is enterprise-ready, fast, and highly scalable. The applications built using Solr are sophisticated and deliver high performance.   

    Apache Solr stores the data it indexes in the local filesystem by default. HDFS (Hadoop Distributed File System) provides several benefits, such as a large scale and distributed storage with redundancy and failover capabilities. Apache Solr supports storing data in HDFS.

    Solr runs as a standalone full-text search server.

### Benefits 
- Advanced Full-Text Search Capabilities. 
- Optimized for High Volume Traffic. 
- Standards Based Open Interfaces - XML, JSON, and HTTP.

### Current users
 - NASA
 - MTV networks
 - Flipkart
 - Billingmed (Germany)
 - Redfin
 - Netflix
 - Instagram

***

## Lucene
    Apache Lucene is a free and open-source search engine software library, originally written in Java by Doug Cutting. It is supported by the Apache Software Foundation and is released under the Apache Software License. Lucene is widely used as a standard foundation for non-research search applications.

### Benefits 
- Speed and high-performance indexing    
- Efficient and accurate search algorithms
- Open source and cross Platform

### Current users
- twitter
- slack
- Noukri.com

**INDEXING**  
Because Elasticsearch is schemaless, it is easy to index unstructured data and dynamic fields without defining the schema of the index in advance. Earlier Solr versions required a defined schema before indexing data. However, Solr now supports a schemaless mode.

# SUMMARY
According to DB-Engines, database management systems, and search engines according to their popularity, **Elasticsearch is ranked number one**, and **Solr is ranked number three**.
Both Solr and Elasticsearch write indexes in Lucene. But, since differences exist in sharding and replication, there are also differences in their files and architectures. Additionally, Elasticsearch has native DSL support while Solr has a robust Standard Query Parser that aligns to Lucene syntax.  
Solr uses request handlers to ingest data from XML files, CSV files, databases, Microsoft Word documents, and PDFs. With native support for the Apache Tika library.  
Elasticsearch, on the other hand, is completely JSON-based. It supports data ingestion from multiple sources using the Beats family and Logstash.  
**Solr is more suited for search applications that use massive amounts of static data.**  
**Elasticsearch is more suited to modern web applications where data is carried in and out in JSON format.**  

##CONCLUSION
Both of these technologies are quite easy to begin working with.**Solr offers great functionalities in the field of information retrieval, but Elasticsearch is much easier to take into production and scale.**  
**Lucene is widely used as a standard foundation for non-research search applications.**
we have to choose our tool as per our requirement.




### links  
- https://logz.io/blog/solr-vs-elasticsearch/

- [benifits of elastic search](https://www.google.com/search?q=benefits+of+elasticsearch&sxsrf=ALiCzsapkV58G5Pkd3nlZr9zrX4_y3T6IQ%3A1664214959984&ei=r-cxY5PbO7yx4-EPne2qsAI&oq=benifits&gs_lcp=Cgdnd3Mtd2l6EAMYADIFCAAQkQIyBQgAEJECMgUIABCRAjIFCAAQkQIyBQgAEJECMgcIABCxAxAKMggIABCxAxCDATIHCAAQsQMQCjIECAAQCjIKCAAQsQMQgwEQCjoHCCMQ6gIQJzoECCMQJzoLCAAQgAQQsQMQgwE6EQguEIAEELEDEIMBEMcBENEDOgsILhCABBCxAxCDAToECAAQQzoICAAQgAQQsQM6CwguEIAEELEDENQCOg4ILhCxAxCDARDHARDRAzoOCC4QgAQQsQMQxwEQ0QM6BQgAEIAEOgUILhCABDoICC4QgAQQsQM6DgguEIAEELEDEIMBENQCOgcIABCABBAKSgQIQRgASgQIRhgAUNsIWKcXYNAoaAFwAHgAgAHEAYgBhwqSAQMwLjiYAQCgAQGwAQrAAQE&sclient=gws-wiz)
- https://www.brainvire.com/solr-search-usage-benefits/
- [about apache lucene](https://www.goodworklabs.com/three-important-benefits-of-apache-lucene-in-search-engine-technology-goodworklabs/)
- https://www.youtube.com/watch?v=MMWBdSdbu5k
- https://www.youtube.com/watch?v=S1Md3LDJPLs


