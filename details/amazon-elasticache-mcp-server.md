# Amazon ElastiCache MCP Server

## Overview
Amazon ElastiCache MCP Server is an official Model Context Protocol (MCP) server for interacting with the AWS ElastiCache control plane. It provides tools to create, manage, and monitor ElastiCache serverless caches, replication groups, and cache clusters, as well as related CloudWatch, CloudWatch Logs, and Firehose resources.

## Features

### Serverless Cache Operations
- **create-serverless-cache** – Create a new ElastiCache serverless cache.
- **delete-serverless-cache** – Delete an existing serverless cache.
- **describe-serverless-caches** – Retrieve information and status for one or more serverless caches.
- **modify-serverless-cache** – Update configuration and settings of a serverless cache.
- **connect-jump-host-serverless-cache** – Configure an existing EC2 instance as a jump host for accessing a serverless cache.
- **create-jump-host-serverless-cache** – Provision an EC2 jump host to access a serverless cache via SSH tunnel.
- **get-ssh-tunnel-command-serverless-cache** – Generate the SSH tunnel command needed to connect to a serverless cache through a jump host.

### Replication Group Operations
- **create-replication-group** – Create an ElastiCache replication group with specified configuration.
- **delete-replication-group** – Remove a replication group, with the option to create a final snapshot.
- **describe-replication-groups** – Get detailed information about one or more replication groups.
- **modify-replication-group** – Change configuration and settings of an existing replication group.
- **modify-replication-group-shard-configuration** – Adjust the shard configuration (e.g., shard count or key distribution) of a replication group.
- **test-migration** – Test migrating from a Redis instance to an ElastiCache replication group.
- **start-migration** – Initiate migration from a Redis instance to an ElastiCache replication group.
- **complete-migration** – Finalize a migration from a Redis instance to an ElastiCache replication group.
- **connect-jump-host-replication-group** – Configure an EC2 instance as a jump host for replication group access.
- **create-jump-host-replication-group** – Create an EC2 jump host to access a replication group via SSH tunnel.
- **get-ssh-tunnel-command-replication-group** – Generate the SSH tunnel command for replication group access.

### Cache Cluster Operations
- **create-cache-cluster** – Create a new ElastiCache cache cluster.
- **delete-cache-cluster** – Delete a cache cluster, optionally creating a final snapshot.
- **describe-cache-clusters** – Retrieve detailed information about one or more cache clusters.
- **modify-cache-cluster** – Update configuration and settings of an existing cache cluster.
- **connect-jump-host-cache-cluster** – Configure an EC2 instance as a jump host for cache cluster access.
- **create-jump-host-cache-cluster** – Create an EC2 jump host to access a cache cluster via SSH tunnel.
- **get-ssh-tunnel-command-cache-cluster** – Generate the SSH tunnel command for cache cluster access.

### CloudWatch Operations
- **get-metric-statistics** – Retrieve CloudWatch metric statistics for ElastiCache resources with customizable time ranges, metrics, and dimensions.

### CloudWatch Logs Operations
- **describe-log-groups** – List and describe CloudWatch Logs log groups.
- **create-log-group** – Create a new CloudWatch Logs log group.
- **describe-log-streams** – List and describe log streams within a log group.
- **filter-log-events** – Search and filter log events across multiple log streams.
- **get-log-events** – Retrieve log events from a specific log stream.

### Firehose Operations
- **list-delivery-streams** – List available Kinesis Data Firehose delivery streams (partial information; full details may be on the source page).

### Related MCP Servers
- For direct data operations against ElastiCache-compatible engines:
  - **Valkey MCP Server** – For Valkey-backed caches.
  - **Memcached MCP Server** – For Memcached-backed caches.

## Category
- Database & Messaging MCP Servers

## Tags
- aws
- cache
- resource-management

## Pricing
Pricing information is not provided in the available content. Use standard AWS ElastiCache and related AWS service pricing as applicable in your AWS account.