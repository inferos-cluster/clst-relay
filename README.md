# CLST-RELAY

The cluster's external boundary - manages Runners and bridges the cluster to the internet and other cluster Relays.

- **Type**: Port
- **Code**: CLST-RELAY

## Overview

The Relay is the only point where the cluster touches the outside world. It contains and manages Runners, providing them with a controlled bridge to external networks. A Runner from one cluster can only interact with a Relay of another cluster, never with its Gate or internal modules.
