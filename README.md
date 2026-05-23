## Aws Ec2 Observability

MIse en place d'un système de surveillance des performances d'instances EC2 en utilisant Amazon CloudWatch pour la collecte des métriques et des logs, et Grafana pour la visualisation via des dashboards interactifs.

---

## Objectif
Mettre en place une plateforme d’observabilité permettant de surveiller en temps réel les performances d’instances cloud.

Le système collecte les métriques des instances, les centralise dans Amazon CloudWatch, puis les visualise via Grafana (ou Amazon Managed Grafana).

---


## Architecture


---

## Flux simplifié
EC2 → CloudWatch Agent → CloudWatch Metrics → Grafana Dashboard

---

## Documentation Détaillée
→ [doc](docs/architecture.md)


---

## Compétence développées
- Monitoring avec Amazon CloudWatch
- Logging avec CloudWatch Logs
- Observabilité avec Grafana
- Gestion des métriques EC2
- Alerting avec CloudWatch Alarms
- Optimisation des coûts cloud