# Architecture Notes

## Current Design
- Web application tier (multiple VMs)
- Database tier (managed service)
- Load balancer for traffic distribution

## Scaling Strategy
Testing horizontal scaling by adding VM instances

## Questions to explore
- What VM sizes offer best price/performance?
- AKS vs EKS cost comparison
- Regional latency differences
