# Risk Assessment and Mitigation

## Data Privacy (HIPAA-like)
- Risk: Handling PHI without proper safeguards leads to breaches, fines, loss of trust.
- Mitigation: Use anonymized/synthetic data for development; implement encryption at rest/transit; audit logs for access.

## ML Model Drift
- Risk: Quality models degrade over time, reducing accuracy.
- Mitigation: Implement basic drift detection (e.g., monitor prediction distributions); plan for periodic retraining with feedback data.

## Scaling Bottlenecks
- Risk: Single points of failure or stateful components limit throughput.
- Mitigation: Design stateless services; use Kubernetes for orchestration; load test early.