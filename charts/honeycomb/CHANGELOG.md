# Honeycomb Kubernetes Agent Helm Chart Changelog

## Honeycomb Kubernetes Agent v1.3.1

- Bump honeycomb agent from 2.3.1 to [2.3.2](https://github.com/honeycombio/honeycomb-kubernetes-agent/releases/tag/v2.3.2) (#113)
  - maintenance release updating libhoney-go
- docs: how to ingress local refinery chart (#112)

## Honeycomb Kubernetes Agent v1.3.0

- bump agent version to 2.3.1 (#98)
- add nodes resource to honeycomb/templates/cluster-role (#96)
- add pod labels to honeycomb kubernetes agent chart (#91)

## Honeycomb Kubernetes Agent v1.2.0

- Adds node metadata to metrics events
- Fixes intermittent exception in metrics processor

## Honeycomb Kubernetes Agent v1.1.1

- Fixes selectors for container metadata and logs

## Honeycomb Kubernetes Agent v1.1.0

- Adds support for multiple architectures (amd64 + arm64) #64

## Honeycomb Kubernetes Agent v1.0.4

- Adds support for priorityClassName to agent daemonset (#58)

## Honeycomb Kubernetes Agent v1.0.3

- Adds a NODE_IP configuration option for metics collection #28
