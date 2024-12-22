# Awesome Object Storage Infrastructure

An opinionated list of awesome projects, frameworks, databases, and resources built atop object storage systems. Whether it’s about implementing modern data platforms, logs, event-driven architectures, or large-scale analytics, these projects harness object-based backends to power scalable and resilient infrastructures.

## Event Streaming
Solutions and frameworks that leverage object storage for large-scale data lake implementations, analytics processing, and more.

[Warpstream](https://docs.warpstream.com/) - High-performance streaming analytics engine built atop object storage.
[Responsive](https://www.responsive.dev/) - Responsive is an object storage based Kafka Streams implementation.

## Databases

[SlateDB](https://slatedb.io/) - Rust based embedded database built on object storage. RocksDB alternative.

## Conference Talks/Presentations

[Object Storage is All You Need | (Justin Cormack, Docker)](https://www.youtube.com/watch?v=ei0wwTy6_G4) - When Jeff Bezos commissioned Amazon S3 he called it "malloc for the web"; since then many people have considered cloud object storage to be a weird kind of non Posix filesystem, but also a great backing store for websites or storing lots of data. Recently more and more applications are being built with object storage as the entire persistence layer. This started with analytics databases such as Snowflake and Databricks, and the open source Delta Lake and Apache Iceberg projects. More recently the use is spreading to even more applications, from observability to streaming data and more. In this talk we look at why it is becoming so popular, the benefits, downsides and performance characteristics, and how and when to use it effectively.
