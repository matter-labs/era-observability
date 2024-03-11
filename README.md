# Era Observability

This repository contains json sources for Grafana dashboards that are used to observe `zkSync Era` as well as can be 
used for any other Hyperchain / External Node deployment. The dashboards are regularly updated.   

## How to use

The easiest way to try out the dashboards in a development environment is via `--run-observability` flag
that can be specified for `zk init` and `zk stack init` commands 
([docs](https://github.com/matter-labs/zksync-era/blob/main/docs/guides/launch.md#run-observability-stack)). 

Alternatively the dashboards can be imported as-is via the Grafana JSON importer. 

> Note: some panels might be empty, depending on whether you are running a full Hyperchain or External Node.   

## Dashboards

* **General** - one pager high level overview of L1/L2 blockchains and L2 APIs;
* **Sequencer** - detailed sequencer-related metrics.