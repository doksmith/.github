# Doksmith (`@doksmith`)

Production-ready, multi-architecture (`linux/amd64`, `linux/arm64`) Docker container images maintained by the [Doksmith](https://github.com/doksmith) open-source volunteer community.

---

## 🌟 Core Standards & Features

- **Multi-Architecture**: Built natively for `linux/amd64` and `linux/arm64` via Docker Buildx & QEMU.
- **Fast Builds (Zero Compilation Overhead)**: Leveraging Alpine Linux native pre-compiled binaries to ensure multi-arch builds finish in under 1 minute.
- **CVE Mitigated**: Strict adherence to security patches, eliminating end-of-life runtimes and critical vulnerabilities.
- **Security-First**: Minimal base images, non-root execution where applicable, and automated scanning.
- **Independent Repositories**: Follows the modular `docker-<app>` structure (inspired by LinuxServer.io).

---

## 📦 Container Images Catalog

| Image | Repository | Registry | Supported Tags | Status |
|---|---|---|---|---|
| **Flarum** | [doksmith/docker-flarum](https://github.com/doksmith/docker-flarum) | `ghcr.io/doksmith/flarum` | `latest`, `2.0`, `1.8` | [![CI](https://github.com/doksmith/docker-flarum/actions/workflows/ci.yml/badge.svg)](https://github.com/doksmith/docker-flarum/actions) |

---

## 🤝 Contributing

We welcome community contributions! To add a new container image:
1. Use our official blueprint template at [doksmith/doksmith](https://github.com/doksmith/doksmith).
2. Follow our modular `docker-<app>` naming convention.
3. Open an issue or join the discussion in the repository.
