## Javier Menechian

I'm a Computer Engineering student at FIUBA (Universidad de Buenos Aires), finishing in mid 2027. Most of what I've built is backend work, and the part I enjoy most is distributed systems: making things keep working when a node goes down or the network splits.

I mostly write Rust, Go and Python. I've used PostgreSQL, MongoDB, Docker and GitHub Actions on the projects below.

I'm looking for a junior backend role in Buenos Aires or remote.

### Projects

**[Cassandra-Like-DB](https://github.com/Jmenechian/Cassandra-Like-DB)**
A distributed database inspired by Cassandra, written in Rust with a team of four. There is no master node. Data is spread with consistent hashing, nodes find each other with gossip, and every write goes to three replicas. It has its own CQL parser, and we built a small flight-tracking app on top of it to show it working.

**[distributed-bike-sharing](https://github.com/Jmenechian/distributed-bike-sharing)**
A bike rental system for a city, built in Rust with Actix and Tokio. Stations work as peers without a central server and keep running if they lose connection. Payments go through a group of replicated nodes that elect a leader (Bully) and use two-phase commit.

**[classconnect-backend](https://github.com/Jmenechian/classconnect-backend)**
The backend of an education app. It has two services: courses in Python with FastAPI and PostgreSQL, and users in Go with Gin and MongoDB. They talk through RabbitMQ. Open exam answers are graded with the Gemini API, and both services report to Datadog.

### Contact

[LinkedIn](https://www.linkedin.com/in/javier-menechian-304732439/) or javiergmenechian@gmail.com
