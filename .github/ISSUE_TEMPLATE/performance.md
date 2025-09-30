---
name: Performance Issue
about: Report performance problems or optimization needs
title: '[PERFORMANCE] '
labels: ['performance', 'needs-triage']
assignees: ''
---

## ⚡ Performance Issue Description
A clear and concise description of the performance problem you're experiencing.

## 📊 Performance Metrics
Please provide specific metrics about the performance issue:

### Current Performance
- **Processing time**: [e.g. 30 seconds for 10K records]
- **Memory usage**: [e.g. 2GB RAM usage]
- **CPU usage**: [e.g. 80% CPU utilization]
- **Throughput**: [e.g. 100 records/second]

### Expected Performance
- **Expected processing time**: [e.g. <5 seconds for 10K records]
- **Expected memory usage**: [e.g. <500MB RAM]
- **Expected throughput**: [e.g. 1000 records/second]

## 📋 Configuration Details
Please provide your current configuration that's experiencing performance issues:

```json
{
  // Your configuration here - focus on performance-related settings
}
```

## 📈 Data Characteristics
Help us understand your data load:
- **Data volume**: [e.g. 1M records/hour, 500GB/day]
- **Record size**: [e.g. Average 2KB per record]
- **Data complexity**: [e.g. Nested JSON with 50+ fields]
- **Processing complexity**: [e.g. Multiple transformations, aggregations]

## 🔄 Steps to Reproduce
Steps to reproduce the performance issue:
1. Configure the platform with '...'
2. Load data from '....'
3. Process with settings '....'
4. Observe performance metrics

## 🌍 Environment
- **Platform version**: [e.g. v1.2.3]
- **Operating System**: [e.g. Ubuntu 20.04, Windows 10, macOS 12]
- **Hardware specs**: 
  - CPU: [e.g. 8-core Intel i7]
  - RAM: [e.g. 16GB]
  - Storage: [e.g. SSD, 500GB]
- **Deployment**: [e.g. Docker, Native, Cloud instance type]
- **Network**: [e.g. Local, 1Gbps, Cloud]

## 📊 Profiling Data
If you have profiling or monitoring data, please include it:
- CPU profiling results
- Memory profiling results
- Network utilization
- Disk I/O metrics

```
[Paste profiling data here]
```

## 🔍 Investigation Done
What have you already tried to investigate or improve performance?
- [ ] Checked system resources (CPU, Memory, Disk)
- [ ] Reviewed configuration for optimization opportunities
- [ ] Tested with smaller data sets
- [ ] Profiled the application
- [ ] Checked network connectivity
- [ ] Other: ___________

## 💡 Potential Causes
Do you suspect any particular cause for the performance issue?
- [ ] Large data volume
- [ ] Complex transformations
- [ ] Network latency
- [ ] Disk I/O bottleneck
- [ ] Memory limitations
- [ ] Configuration inefficiency
- [ ] Not sure

## 📋 Additional Context
Add any other context about the performance issue:
- When did you first notice this issue?
- Has performance degraded over time?
- Does it affect all operations or specific ones?

## ✔️ Checklist
- [ ] I have provided specific performance metrics
- [ ] I have included my configuration
- [ ] I have described my data characteristics
- [ ] I have specified my environment details
- [ ] I have indicated what investigation I've already done