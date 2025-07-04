# Usage Guide

This document provides usage instructions for all executables in this project.

## 1. `sync_all.sh`

Automates deployment of OreyeonAI on all Jetsons.

```bash
./deploy.sh
```
---

## 2. `rollback.sh`

Reverts the last deployment.

```bash
./rollback.sh [options]
```

**Options:**
- `-n, --number <count>`: Number of deployments to roll back.
- `-h, --help`: Show help message.

---

## 3. `status.sh`

Displays the current deployment status.

```bash
./status.sh
```

No options required.

---

## 4. `logs.sh`

Shows recent deployment logs.

```bash
./logs.sh [options]
```

**Options:**
- `-t, --tail <lines>`: Number of log lines to display.
- `-h, --help`: Show help message.

---

## Getting Help

For any executable, use the `-h` or `--help` flag to see detailed usage instructions.

---

**Note:** Ensure all scripts have execute permissions:
```bash
chmod +x <script_name>
```
