# 02-kubernetes — Arquitetura e Recursos Nativos do Kubernetes

Gerenciamento declarativo de workloads, redes, armazenamento, segurança e controle de acesso.

## 📂 Subáreas
- [`pods-deployments/`](./pods-deployments) — **Stack:** `Pod, Deployment, ReplicaSet, DaemonSet, StatefulSet` — Ciclo de vida de workloads, escalonamento e estratégias de execução em nós do cluster.
- [`services-ingress/`](./services-ingress) — **Stack:** `ClusterIP, NodePort, LoadBalancer, Ingress NGINX` — Comunicação interna entre serviços e roteamento de borda HTTP/HTTPS externo.
- [`configmaps-secrets/`](./configmaps-secrets) — **Stack:** `ConfigMap, Secret, montagem como volume ou env` — Injeção de configurações e senhas desacopladas do código da aplicação.
- [`storage/`](./storage) — **Stack:** `PersistentVolume (PV), PVC, StorageClass` — Provedores dinâmicos de storage (CSI), persistência de dados e políticas de retenção.
- [`rbac/`](./rbac) — **Stack:** `Role, ClusterRole, RoleBinding, ServiceAccount` — Controle de acesso granular baseado em funções para usuários e automações.
- [`network-policies/`](./network-policies) — **Stack:** `NetworkPolicy, egress/ingress isolation, podSelector` — Firewall interno do cluster limitando o tráfego de rede entre namespaces.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
