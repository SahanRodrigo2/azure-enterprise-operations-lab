# Monitoring Implementation

## Components

* Azure Monitor
* Log Analytics Workspace (LAW-Enterprise)

## Connected Resources

* WIN-AD01
* LINUX-WEB01

## Data Collected

* Heartbeat
* CPU Metrics
* Event Logs
* Syslogs

## Sample KQL Queries

Heartbeat Check

Heartbeat
| summarize LastHeartbeat=max(TimeGenerated) by Computer

CPU Monitoring

Perf
| where CounterName == "% Processor Time"

## Benefits

* Real-time visibility
* Performance monitoring
* Incident detection
