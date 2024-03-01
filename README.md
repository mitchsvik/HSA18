# HSA18
GOAL!!!

Describe the solution that solves the peak loadings problem for the biggest european football website https://goal.com:


### Pages

The Goal.com contains 3 types of pages:

- live scores with dynamic real-time data
- news - predefined or event-based content
- opinion pages - original content produced by the site


### Live Scores

To manage increased traffic during live events Goal.com can utilize load-balancing techniques. 

Behind the load balancer can be set up horizontally-scalable server infrastructure that can be scaled up or down based on traffic demand.
This helps to maintain consistent performance and prevent downtime during peak traffic periods. 

In case of ongoing events - servers can be scheduled in advance before the real load occurs.

### News

To handle sudden spikes in traffic during  breaking news events, Goal.com can implement efficient caching mechanisms and Content Delivery Networks (CDNs). 

Caching involves storing frequently accessed data in a local cache, reducing the need for repeated requests to the server. 

CDNs distribute content across multiple servers, ensuring that users can access the site from the nearest server to improve overall performance and reduce latency.

Also, server scaling can be set up based on historical schedule: a bigger reserved pool for morning and evening hours or days of scheduled events or breaking news.

### Articles and Opinion Pages

To optimize page loading times and reduce server load, Goal.com can implement dynamic content caching strategies. 

Dynamic content caching involves storing frequently accessed content in a cache, reducing the need for repeated requests to the server. This helps to improve performance and reduce server load.