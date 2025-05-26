## Five-Stage AI Incident Response Maturity Model

1. Detection – ML model flags anomaly (e.g., CPU spike)
2. Correlation – Ties alerts across services (e.g., 5xx and latency)
3. Recommendation – Suggests action (e.g., pod restart)
4. Execution – Rollback triggered via ArgoCD or Lambda
5. Feedback – Model updates thresholding based on postmortem

This framework supports phased automation with human control.
