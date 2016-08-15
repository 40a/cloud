### Tarantool Cloud

Tarantool Cloud is a service that allows you to run a self-healing, replicated set of tarantool instances. It is built on top of Consul and is resilient to some of the typical hardware and network problems.

It provides the following key features:

- **REST API**: for programmatic creation and destruction of tarantool instances
- **WEB UI**: to allow human agents create single on-demand instances and get an overview of the system
- **Failover**: to automatically recover from node failures or degraded storage

Read more on the wiki: [Documentation](https://github.com/tarantool/cloud/wiki)

#### Getting Started

To prepare an environment, do:

```sh
docker-compose up
```

Then go to [http://localhost:5061](http://localhost:5061) to access web UI.
