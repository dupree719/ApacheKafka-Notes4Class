# ApacheKafka-Notes4Class



Apache Kafka: A distributed messaging system for a vast amounts of data + Event streaming platform

Key Words: (What makes up Kafka)

Producer - An application that sends data (messages) to Kafka (Producers are those client applications that publish (write) events to Kafka)

Consumer - An application that receives data from kafka (Consumers are those that subscribe to (read and process) these events)

Broker - Kafka Server

Cluster - Group of computers

Topic - A name for a Kafka stream

Partitions - Part of a topic (Kafka stream)

Offset - Unique id for a message within a partition

Consumer groups - A group of consumers acting as a simple logical unit

Kakfa is run as a cluster of one or more servers (computers) that can span datacenters or cloud regions. Some of these servers form the storage layer aka the brokers. Other servers run Kafka Connect (used to import/export data as event streams)

Event - An event records the fact that "something happened" in the world or in your business. Ab event has a key, value, timestamp, and optional metadata headers

Use Cases-

Real-time data processing: Kafka is often used to collect and process large streams of data in real-time. This can include things like tracking website visitors, analyzing log files, and processing sensor data.

Streaming data integration: Kafka can be used to integrate data from multiple sources and make it available in real-time to downstream systems. For example, a company might use Kafka to combine data from a variety of source systems (e.g. CRM, ERP, marketing automation) and make it available to a data warehouse or data lake for analysis.

Event-driven architectures: Kafka can be used to build event-driven architectures, where different parts of a system can react to changes in the data stream in real-time. This can include things like triggering a workflow, sending a notification, or updating a database.

LinkedIn: LinkedIn, now owned by Microsoft, uses Kafka as the backbone of its data infrastructure. Kafka is used to handle more than 1 trillion messages per day, and it plays a critical role in LinkedIn's data pipeline, data processing and data integration.

Netflix: Netflix uses Kafka to handle its real-time data streams. The platform uses Kafka to collect data from a variety of sources and make it available to downstream systems for analysis and action.

Uber: Uber uses Kafka as a key component of its data pipeline. The platform uses Kafka to collect data from a variety of sources and make it available to downstream systems for analysis and action.
