# Welcome to Eden
We are an engineering team dedicated to building modern, lightweight, and high-performance system software for High-Performance Computing (HPC) environments.

Our mission is to provide deep, zero-overhead visibility into cluster resources, bridging the gap between low-level Linux telemetry and high-level job schedulers.

## What We Do
Modern HPC clusters require precise monitoring to ensure optimal resource allocation, prevent bottlenecks, and track hardware usage efficiently. We develop tools that integrate seamlessly with industry standards like Slurm, NVIDIA GPUs, and parallel file systems like Lustre.

## Current Focus
Currently, we are developing our flagship project:

slurm-node-agent

A highly optimized, daemon written in Go. It runs on compute nodes to collect real-time telemetry, correlating hardware metrics with specific Slurm jobs.

Compute & Memory: Tracking CPU and RAM limits/usage natively via cgroups v2.

Accelerators: Deep hardware profiling of NVIDIA GPUs (Tesla T4, etc.) using go-nvml.

Storage I/O: Monitoring job-specific Lustre file system utilization (integrating with Robinhood Policy Engine).

This initiative is developed as an engineering project by students of the Faculty of Mathematics and Information Science (MiNI), Warsaw University of Technology (PW).
