# Era Observability

This repository contains JSON sources for Grafana dashboards that are used to observe `zkSync Era` as well as can be 
used for any other ZK Stack chains / External Node deployment. The dashboards are updated automatically.

## How to use

This repository contains a Docker compose setup that is prepared to work with a local ZKsync deployment.
All the ports are pre-configured to match the default port layout of local ZKsync configuration.

The setup can be launched via:

```
docker compose up -d
```

Alternatively the dashboards can be imported as-is via the Grafana JSON importer. 

> Note: some panels might be empty, depending on whether you are running a full Hyperchain or External Node.   

## Acknowledgments

The `docker-compose` setup and configuration in this repository are based on the awesome [dockprom](https://github.com/stefanprodan/dockprom),
which is licensed under [MIT License](https://github.com/stefanprodan/dockprom/blob/master/LICENSE).

## Dashboards

* **General** - one pager high level overview of L1/L2 blockchains and L2 APIs;
* **Sequencer** - detailed sequencer-related metrics.
* **Prover** - metrics for prover infrastructure

## License

This repository is licensed under MIT license. See [LICENSE](./LICENSE) for more details.
