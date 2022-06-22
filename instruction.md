Exercise: Graph Memory Usage
Add a graph for memory usage to your Prometheus server.

Instructions:
Browse to your Prometheus dashboard on port 9090.
Go to the "Graph tab".
Take a look at all the options in the dropdown labeled "insert metric at cursor".
Create a few graphs to see what kind of information you can get. You can find some examples here.
https://prometheus.io/docs/prometheus/latest/querying/examples/

Create a graph that shows available memory for your EC2 instances with node_exporter running.


Way to Go!
On the practical side, the metrics gathered from Prometheus don't mean a whole lot in their raw form. We need visualizations to help understand what we're looking at. You know how they say a picture is worth a thousand words? That might be more like a million words when it comes to monitoring data visualization.

Something really cool about monitoring data: When you understand the metrics and how they relate to server or application health, you can start predicting issues before they arise instead of just reacting to them!