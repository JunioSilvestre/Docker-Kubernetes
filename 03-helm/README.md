# 03-helm — Helm & Gerenciamento de Pacotes no Kubernetes

Criação de Helm Charts reutilizáveis, versionamento semântico, templates Go e gestão de values.

## 📂 Subáreas
- [`charts/`](./charts) — **Stack:** `Chart.yaml, Chart dependencies, umbrella charts` — Estruturação de pacotes de aplicações distribuídas no Kubernetes.
- [`templates/`](./templates) — **Stack:** `Go templates, helpers (_helpers.tpl), condicionais` — Parametrização dinâmica de manifests YAML de deployments e services.
- [`values-versionamento/`](./values-versionamento) — **Stack:** `values.yaml, values por ambiente (dev, prod)` — Sobrescrita controlada de configurações sem alterar os templates base.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
