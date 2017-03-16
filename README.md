DistributedAuction
==================

A distributed system application to conduct auctions in real-time for determining prices of services (like car rental, hotel rental etc) or products.

System Architecture: <br/>
    1.Independent clusters for each type of service<br/>
    2.RESTful communication pattern between each component<br/>
    3.MongoDB for persistent storage of nested document data model.<br/>
    4.Zookeeper for load balancing of failure tolerance duties.<br/>
    5.Web interface for both buyer and seller functionality using Primefaces/JSF 2.0