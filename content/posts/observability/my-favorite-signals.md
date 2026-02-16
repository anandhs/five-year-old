---
title: "My Favorite Reliability Signals"
date: 2026-02-13
draft: false
tags: ["observability", "sre", "metrics"]
categories: ["engineering"]
series: ["reliability-basics"]
---

## What it is

Reliability signals are metrics that help teams understand system health in production.

A common and useful set is:

- latency
- traffic
- errors
- saturation

## Why

These signals help teams detect and fix incidents faster.

They answer practical questions:

- Is the system slow?
- Is demand changing?
- Are requests failing?
- Are resources near capacity?

Together, they provide a strong baseline for operational decisions.

## How does it work

Teams collect and monitor these metrics over time.

- Latency tracks response-time behavior.
- Traffic tracks workload volume.
- Errors track failed operations.
- Saturation tracks resource pressure (CPU, memory, queue depth, connections).

By correlating all four, teams can separate demand issues from code defects, dependency failures, or capacity limits.

## More details (and references)

- [Google SRE Book: Monitoring Distributed Systems](https://sre.google/sre-book/monitoring-distributed-systems/)
- [The USE Method](https://www.brendangregg.com/usemethod.html)
- [OpenTelemetry Documentation](https://opentelemetry.io/docs/)
