# MontuDB — downloads

Binários oficiais do **MontuDB 6.0**, um fork do PostgreSQL com o conjunto
de otimizadores Montu (RealCost, OLAP/MRRV, Condense, V4 Compose, V5 BloomHash
e o operador de junção nativo **V6 MBBM**).

O MontuDB 6.0 é publicado sobre **quatro bases do PostgreSQL, em paralelo** — nenhuma
substitui a outra. As quatro instalam lado a lado na mesma máquina: prefixo, serviço
systemd, data dir e pacote são distintos em cada linha.

| linha | base | pacote | prefixo | release |
|---|---|---|---|---|
| MontuDB 6.0 | PostgreSQL 17.2 | `montudb` | `/opt/montudb/6.0` | [`v6.0`](https://github.com/MontuDB/download/releases/tag/v6.0) |
| MontuDB 6.0 | PostgreSQL 17.9 | `montudb-pg17.9` | `/opt/montudb/6.0-pg17.9` | [`v6.0-pg17.9`](https://github.com/MontuDB/download/releases/tag/v6.0-pg17.9) |
| MontuDB 6.0 | PostgreSQL 17.10 | `montudb-pg17.10` | `/opt/montudb/6.0-pg17.10` | [`v6.0-pg17.10`](https://github.com/MontuDB/download/releases/tag/v6.0-pg17.10) |
| MontuDB 6.0 | PostgreSQL 18.4 | `montudb-pg18.4` | `/opt/montudb/6.0-pg18.4` | [`v6.0-pg18.4`](https://github.com/MontuDB/download/releases/tag/v6.0-pg18.4) |

Todos os binários reportam a marca `MontuDB 6.0`; o que distingue as linhas é a
versão do PostgreSQL impressa ao lado e o `server_version_num`.

---

## PostgreSQL 17.2 — release [`v6.0`](https://github.com/MontuDB/download/releases/tag/v6.0)

`PostgreSQL 17.2 (MontuDB 6.0)` · `server_version_num` = `170002`

| arquivo | arch | formato | tamanho |
|---|---|---|---|
| [`montudb_6.0-1_amd64.deb`](https://github.com/MontuDB/download/releases/download/v6.0/montudb_6.0-1_amd64.deb) | `amd64` | deb | 5.1 MB |
| [`montudb_6.0-1_arm64.deb`](https://github.com/MontuDB/download/releases/download/v6.0/montudb_6.0-1_arm64.deb) | `arm64` | deb | 4.6 MB |
| [`montudb-6.0-1.x86_64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-1.x86_64.rpm) | `x86_64` | rpm | 5.4 MB |
| [`montudb-6.0-1.aarch64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-1.aarch64.rpm) | `aarch64` | rpm | 5.3 MB |
| [`montudb-6.0-pg17.2-linux-amd64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-pg17.2-linux-amd64.tar.gz) | `amd64` | tarball | 7.8 MB |
| [`montudb-6.0-pg17.2-linux-arm64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-pg17.2-linux-arm64.tar.gz) | `arm64` | tarball | 7.6 MB |
| [`montudb-6.0-docker-amd64.tar`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-docker-amd64.tar) | `amd64` | docker | 49.8 MB |
| [`montudb-6.0-docker-arm64.tar`](https://github.com/MontuDB/download/releases/download/v6.0/montudb-6.0-docker-arm64.tar) | `arm64` | docker | 49.5 MB |

Checksums: [`pg172-montudb-v6/SHA256SUMS`](pg172-montudb-v6/SHA256SUMS) · manifesto: [`pg172-montudb-v6/release-manifest.json`](pg172-montudb-v6/release-manifest.json)

## PostgreSQL 17.9 — release [`v6.0-pg17.9`](https://github.com/MontuDB/download/releases/tag/v6.0-pg17.9)

`PostgreSQL 17.9 (MontuDB 6.0)` · `server_version_num` = `170009`

| arquivo | arch | formato | tamanho |
|---|---|---|---|
| [`montudb-pg17.9_6.0-1_amd64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-pg17.9_6.0-1_amd64.deb) | `amd64` | deb | 5.0 MB |
| [`montudb-pg17.9_6.0-1_arm64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-pg17.9_6.0-1_arm64.deb) | `arm64` | deb | 4.5 MB |
| [`montudb-pg17.9-6.0-1.x86_64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-pg17.9-6.0-1.x86_64.rpm) | `x86_64` | rpm | 5.4 MB |
| [`montudb-pg17.9-6.0-1.aarch64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-pg17.9-6.0-1.aarch64.rpm) | `aarch64` | rpm | 5.3 MB |
| [`montudb-6.0-pg17.9-linux-amd64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-6.0-pg17.9-linux-amd64.tar.gz) | `amd64` | tarball | 7.8 MB |
| [`montudb-6.0-pg17.9-linux-arm64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-6.0-pg17.9-linux-arm64.tar.gz) | `arm64` | tarball | 7.6 MB |
| [`montudb-6.0-pg17.9-docker-amd64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-6.0-pg17.9-docker-amd64.tar) | `amd64` | docker | 49.9 MB |
| [`montudb-6.0-pg17.9-docker-arm64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.9/montudb-6.0-pg17.9-docker-arm64.tar) | `arm64` | docker | 49.6 MB |

Checksums: [`pg179-montudb-v6/SHA256SUMS`](pg179-montudb-v6/SHA256SUMS) · manifesto: [`pg179-montudb-v6/release-manifest.json`](pg179-montudb-v6/release-manifest.json)

## PostgreSQL 17.10 — release [`v6.0-pg17.10`](https://github.com/MontuDB/download/releases/tag/v6.0-pg17.10)

`PostgreSQL 17.10 (MontuDB 6.0)` · `server_version_num` = `170010`

| arquivo | arch | formato | tamanho |
|---|---|---|---|
| [`montudb-pg17.10_6.0-1_amd64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-pg17.10_6.0-1_amd64.deb) | `amd64` | deb | 5.0 MB |
| [`montudb-pg17.10_6.0-1_arm64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-pg17.10_6.0-1_arm64.deb) | `arm64` | deb | 4.6 MB |
| [`montudb-pg17.10-6.0-1.x86_64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-pg17.10-6.0-1.x86_64.rpm) | `x86_64` | rpm | 5.4 MB |
| [`montudb-pg17.10-6.0-1.aarch64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-pg17.10-6.0-1.aarch64.rpm) | `aarch64` | rpm | 5.3 MB |
| [`montudb-6.0-pg17.10-linux-amd64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-6.0-pg17.10-linux-amd64.tar.gz) | `amd64` | tarball | 7.9 MB |
| [`montudb-6.0-pg17.10-linux-arm64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-6.0-pg17.10-linux-arm64.tar.gz) | `arm64` | tarball | 7.7 MB |
| [`montudb-6.0-pg17.10-docker-amd64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-6.0-pg17.10-docker-amd64.tar) | `amd64` | docker | 50.0 MB |
| [`montudb-6.0-pg17.10-docker-arm64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg17.10/montudb-6.0-pg17.10-docker-arm64.tar) | `arm64` | docker | 49.6 MB |

Checksums: [`pg1710-montudb-v6/SHA256SUMS`](pg1710-montudb-v6/SHA256SUMS) · manifesto: [`pg1710-montudb-v6/release-manifest.json`](pg1710-montudb-v6/release-manifest.json)

## PostgreSQL 18.4 — release [`v6.0-pg18.4`](https://github.com/MontuDB/download/releases/tag/v6.0-pg18.4)

`PostgreSQL 18.4 (MontuDB 6.0)` · `server_version_num` = `180004`

| arquivo | arch | formato | tamanho |
|---|---|---|---|
| [`montudb-pg18.4_6.0-1_amd64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-pg18.4_6.0-1_amd64.deb) | `amd64` | deb | 5.2 MB |
| [`montudb-pg18.4_6.0-1_arm64.deb`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-pg18.4_6.0-1_arm64.deb) | `arm64` | deb | 4.7 MB |
| [`montudb-pg18.4-6.0-1.x86_64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-pg18.4-6.0-1.x86_64.rpm) | `x86_64` | rpm | 5.5 MB |
| [`montudb-pg18.4-6.0-1.aarch64.rpm`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-pg18.4-6.0-1.aarch64.rpm) | `aarch64` | rpm | 5.4 MB |
| [`montudb-6.0-pg18.4-linux-amd64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-6.0-pg18.4-linux-amd64.tar.gz) | `amd64` | tarball | 8.1 MB |
| [`montudb-6.0-pg18.4-linux-arm64.tar.gz`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-6.0-pg18.4-linux-arm64.tar.gz) | `arm64` | tarball | 7.9 MB |
| [`montudb-6.0-pg18.4-docker-amd64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-6.0-pg18.4-docker-amd64.tar) | `amd64` | docker | 50.2 MB |
| [`montudb-6.0-pg18.4-docker-arm64.tar`](https://github.com/MontuDB/download/releases/download/v6.0-pg18.4/montudb-6.0-pg18.4-docker-arm64.tar) | `arm64` | docker | 49.8 MB |

Checksums: [`pg184-montudb-v6/SHA256SUMS`](pg184-montudb-v6/SHA256SUMS) · manifesto: [`pg184-montudb-v6/release-manifest.json`](pg184-montudb-v6/release-manifest.json)

---

## Verificar a integridade

```bash
sha256sum -c SHA256SUMS
```

## Sobre os pacotes

Contêm **apenas binários compilados** — nenhum código-fonte, cabeçalho de
desenvolvimento, biblioteca estática ou PGXS. Os arquivos `.sql`/`.bki` em
`share/postgresql/` são dados de catálogo que o `initdb` exige em runtime, os
mesmos que qualquer PostgreSQL de estoque distribui.

Distribuído sob a PostgreSQL License (veja `COPYRIGHT` / `LICENSE` dentro de cada pacote).
