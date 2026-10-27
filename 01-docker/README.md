# 01-docker — Docker Engine & Construção de Containers

Dockerfiles multi-stage, volumes persistentes, redes bridge/overlay, Docker Compose e boas práticas de imagem.

## 📂 Subáreas
- [`imagens-containers/`](./imagens-containers) — **Stack:** `Dockerfile, multi-stage builds, non-root users` — Criação de imagens mínimas (Alpine/Distroless), cache de layers e otimização de tamanho.
- [`volumes-redes/`](./volumes-redes) — **Stack:** `named volumes, bind mounts, bridge, macvlan networks` — Persistência de dados desacoplada e isolamento de redes entre containers.
- [`compose/`](./compose) — **Stack:** `docker-compose.yml, environment, dependencies, healthcheck` — Orquestração de múltiplos serviços locais com dependências e variáveis de ambiente.
- [`seguranca/`](./seguranca) — **Stack:** `docker scan, trivy, rootless docker, security options` — Execução sem privilégios de root, escaneamento de vulnerabilidades CVE e cap-drop.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
