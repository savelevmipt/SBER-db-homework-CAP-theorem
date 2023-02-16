https://dragonflydb.io/
Simple Vertical Scaling
Dragonfly is architected to scale vertically on a single machine, saving teams the cost and complexity of managing a multi-node cluster. For in-memory datasets up to 1TB, Dragonfly offers the simplest and most reliable scale on the market. 

CA




https://www.scylladb.com/scylla-vs-cassandra/
ScyllaDB’s LWT has a special commitlog mode that automatically balances between the transaction durability flush requirement and fast, non-transactional operations

https://lp.scylladb.com/cassandra-falls-short-wp-offer?siteplacement=whitepapers
ScyllaDB is the Monstrously Fast + Scalable NoSQL Database
https://youtu.be/vnXXFpySYVE?t=439

https://www.scylladb.com/glossary/acid-database/

ScyllaDB offers BASE guarantees:
* Basic Availability: Data is available most of the time, even during a partial system failure.
* Soft state: Replicas are not always consistent.
* Eventual consistency: Data will become consistent at some uncertain point in time.
https://www.scylladb.com/glossary/eventual-consistency/

ScyllaDB offers tunable consistency, which enables IT to set consistency levels for the cluster overall. It also allows each operation (each read or write) to have its own consistency level, a feature known as tunable consistency.

ScyllaDB cluster offers eventual consistency. With eventual consistency all of the replica nodes will eventually arrive at the same data state; operations may continue updating the database in the meantime.

ScyllaDB supports eventual consistency patterns from very low consistency with a Consistency Level of One or Any, all the way up to a Consistency Level of All. The sweet spot for most high performance applications will be somewhere in the middle, so a quorum where a majority of nodes must be written or read is the default starting point. With NoSQL eventual consistency can be implemented several ways, and ScyllaDB is flexible enough with its multi modes and tunable consistency to achieve anything from an eventually consistent key value datastore all the way to more complex database eventual consistency implementations.

https://www.scylladb.com/glossary/cap-theorem/

ScyllaDB uses  a model of tunable eventual consistency to deliver multi datacenter high availability and fast and efficient write and read operations. In this case, all nodes are equal; this means any node can serve any request, there is no single point of coordination, and all nodes in the system continue to cooperatively provide service, even when nodes become unavailable. Eventual consistency supports modern workloads that are less dependent on strong consistency but rely heavily on availability.

ScyllaDB is a PA/EL highly available, partition tolerant, low latency database system. ScyllaDB was designed to provide consistent low-latencies, not just be highly available, and it also provides tunable consistency. Under any conditions short of a complete system failure, ScyllaDB will remain highly available with predictable low latencies for mission critical applications.
ScyllaDB outperforms a distributed NewSQL database such as CockroachDB by a wide margin. Built for high availability, ScyllaDB still delivers tunable consistency, zero downtime, and high performance.







https://arenadata.tech/products/arenadata-db/

С Arenadata DB вы построите надёжное, масштабируемое корпоративное хранилище данных, которое будет расти вместе с вашими потребностями.

Arenadata DB реализована на кластере из множества (от двух до сотен) серверов и равномерно распределяет нагрузку и данные между ними. 

Полное соответствие принципам строгой изоляции транзакции (принципы ACID). Одни и те же таблицы могут быть использованы для записи и чтения, без страха потерять данные.

Есть ли транзакции?
Есть, это ACID-система, а уровень изоляции транзакций — Serializable.

