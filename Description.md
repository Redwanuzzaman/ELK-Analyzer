## What is logging?

Let’s say you are developing a software product. It works remotely, interacts with different devices, collects data from sensors and provides a service to the user. 
One day, something goes wrong and the system is not working as expected. 
It might not be identifying the devices or not receiving any data from the sensors, or might have just gotten a runtime error due to a bug in the code. 
How can you know for sure?

Now, imagine if there are checkpoints in the system code where, if the system returns an unexpected result, it simply flags it and notifies the developer. 
This is the concept of logging.

Logging enables the developers to understand what the code is actually doing and how the work-flow is. 
A large part of software developers’ lives is monitoring, troubleshooting and debugging. 
Logging makes this a much easier and smoother process.


## ELK stack
E — Elasticsearch, L — Logstash, K — Kibana

Let me give a brief introduction to it. 
The ELK stack is a collection of three open source softwares that helps in providing realtime insights about data that can be either structured or unstructured. 
One can search and analyse data using its tools with extreme ease and efficiently.

Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. 
As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected. 
Elasticsearch lets you perform and combine many types of searches — structured, unstructured, geo, metric etc. 
It is built on Java programming language, which enables Elasticsearch to run on different platforms. 
It enables users to explore very large amount of data at very high speed.

Logstash is an open source, server-side data processing pipeline 
that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favourite “stash” (like Elasticsearch). 
Data is often scattered or siloed across many systems in many formats. 
Logstash supports a variety of inputs that pull in events from a multitude of common sources, all at the same time. 
Easily ingest from your logs, metrics, web applications, data stores, and various AWS services, all in continuous, streaming fashion. 
Logstash has a pluggable framework featuring over 200 plugins. Mix, match, and orchestrate different inputs, filters, and outputs to work in pipeline harmony.

Kibana is an open source analytics and visualisation platform designed to work with Elasticsearch. 
You use Kibana to search, view, and interact with data stored in Elasticsearch indices. 
You can easily perform advanced data analysis and visualise your data in a variety of charts, tables, and maps. 
Kibana makes it easy to understand large volumes of data. 
Its simple, browser-based interface enables you to quickly create and share dynamic dashboards that display changes to Elasticsearch queries in real time.
