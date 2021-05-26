# SystemDesign
 a) DNS
                b) CDN [Push vs Pull]
                c) Load Balancers [Active-Passive, Active-Active, Layer 4, Layer 7]
                d) Reverse Proxy
                e) Application layer scaling [Microservices, Service Discovery]
                f) DB [RDBMS, NoSQL]
                        > RDBMS 
                            >> Master-slave, Master-master, Federation, Sharding, Denormalization, SQL Tuning
                        > NoSQL
                            >> Key-Value, Wide-Column, Graph, Document
                                Fast-lookups:
                                -------------
                                    >>> RAM  [Bounded size] => Redis, Memcached
                                    >>> AP [Unbounded size] => Cassandra, RIAK, Voldemort
                                    >>> CP [Unbounded size] => HBase, MongoDB, Couchbase, DynamoDB
                g) Caches
                        > Client caching, CDN caching, Webserver caching, Database caching, Application caching, Cache @Query level, Cache @Object level
                        > Eviction policies:
                                >> Cache aside
                                >> Write through
                                >> Write behind
                                >> Refresh ahead
                h) Asynchronism
                        > Message queues
                        > Task queues
                        > Back pressure
                i) Communication
                        > TCP
                        > UDP
                        > REST
                        > RPC
