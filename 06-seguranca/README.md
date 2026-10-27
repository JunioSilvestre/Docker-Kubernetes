# 06-seguranca — Segurança e Governança de Clusters

Políticas de admissão, escaneamento contínuo de vulnerabilidades e endurecimento do cluster.

## 📂 Subáreas
- [`hardening/`](./hardening) — **Stack:** `PodSecurityStandards, securityContext, readOnlyRootFilesystem` — Restrição de capacidades Linux, drop de privilégios e sistemas de arquivos somente-leitura.
- [`scanning/`](./scanning) — **Stack:** `Trivy, Grype, varredura estática de manifests e imagens` — Bloqueio de deploy de imagens com vulnerabilidades críticas no pipeline.
- [`admission-policies/`](./admission-policies) — **Stack:** `OPA Gatekeeper, Kyverno, validação de regras em runtime` — Enforcement automático de políticas declarativas antes da criação dos recursos.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
