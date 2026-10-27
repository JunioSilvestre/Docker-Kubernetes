# 05-registry — Registries de Imagens & Ciclo de Vida de Artefatos

Build, tagueamento semântico, autenticação e push de imagens em registries públicos e privados.

## 📂 Subáreas
- [`build-push/`](./build-push) — **Stack:** `Docker Hub, GitHub Container Registry (ghcr.io), AWS ECR` — Autenticação via token/credentials e envio automatizado de imagens.
- [`versionamento/`](./versionamento) — **Stack:** `Tags semânticas (v1.0.0), sha256 digest immutability` — Evitando a tag mutable 'latest' em ambientes de produção.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Docker-Kubernetes.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
