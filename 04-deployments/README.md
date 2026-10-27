# 04-deployments — Estratégias de Implantação e Ciclo de Vida

Estratégias de deploy sem downtime, verificações de saúde (probes) e recuperação de falhas.

## 📂 Subáreas
- [`rolling-updates/`](./rolling-updates) — **Stack:** `maxSurge, maxUnavailable, zero-downtime updates` — Atualização gradual de pods garantindo que a aplicação permaneça online.
- [`rollback/`](./rollback) — **Stack:** `kubectl rollout undo, histórico de revisões` — Reversão imediata para a versão funcional anterior em caso de erro no deploy.
- [`health-checks/`](./health-checks) — **Stack:** `startupProbe, livenessProbe, readinessProbe` — Garantia de que tráfego só é enviado a pods prontos e reinício de pods travados.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
