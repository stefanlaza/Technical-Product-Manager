# Stefan Laza — Technical Delivery Lead

Interactive portfolio showcasing cloud architecture, DevOps engineering, and technical project delivery.

**Live site:** [stefanlaza.github.io/DEVOPS](https://stefanlaza.github.io/DEVOPS)

## What's Inside

### Architecture Diagrams (Interactive)
Click any node to trace its connections through the system.

| Diagram | Stack |
|---------|-------|
| AWS 3-Tier | CloudFront, ALB, EC2, RDS Multi-AZ, ElastiCache, S3 |
| Cisco Network | Core/Distribution/Access layers, ASA firewalls, VLANs |
| ETL Pipeline | S3 ingestion, AWS Glue, PySpark, Redshift |
| Batch Processing | EventBridge, Step Functions, Fargate, DLQ |
| Microservices on K8s | Jenkins, ECR, EKS, Istio, Helm |
| Monolith on EC2 | Jenkins, Tomcat, EC2, ALB, RDS |

### Case Studies
Real-world project outcomes with before/after metrics:
- **CI/CD Overhaul** — 2hr deploys → 8min (92% faster)
- **AWS Cost Optimization** — $44K/mo → $26K/mo (41% reduction)
- **Incident Response** — MTTR reduced from 2hr to 23min

### Monitoring Dashboard
Grafana-style mockup with live-updating stats and SVG charts for latency, error rate, CPU, and throughput.

### Architecture Decision Records (ADRs)
Documented trade-off analysis for key infrastructure decisions:
- ECS Fargate vs EKS
- Terraform vs CloudFormation
- Blue-Green vs Canary deployments
- PostgreSQL vs DynamoDB

### Project Delivery (PMP)
- **Project Timeline** — Interactive Gantt chart showing a full cloud migration from initiation to close
- **Risk Register** — Probability × Impact matrix with mitigation strategies
- **Delivery Metrics** — On-time rate, velocity, budget variance, scope tracking
- **Team Topology** — Cross-functional team structure (Platform, Stream-Aligned, Enabling)
- **Retrospective Insights** — Key takeaways and action items from sprint retros
- **Escalation Framework** — Visual decision flowchart for blocker resolution

### Tutorials
Step-by-step deployment walkthroughs in `/tutorials/`:
- AWS 3-Tier Architecture
- Cisco Campus Network
- ETL Pipeline
- Batch Processing
- Microservices on Kubernetes
- Java Monolith to EC2

## Tech Stack
- Pure HTML/CSS/SVG — no frameworks, no build step
- GitHub Pages for hosting
- Scroll-reveal animations
- Interactive SVG diagrams with click-to-highlight

## Local Development
```bash
# Clone and open
git clone https://github.com/stefanlaza/DEVOPS.git
cd DEVOPS
open index.html
```

No dependencies. No build. Just open the HTML file.

## License
MIT
