# Wazuh writeups

Разборы алертов на домашнем стенде: Wazuh в Docker, агент на Ubuntu VPS.

## Стенд

- **Wazuh 4.14.9**: manager, indexer, dashboard (Docker Compose)
- **Агент** на Ubuntu 20.04 VPS: `auth.log`, SCA (CIS Benchmark), инвентаризация
- Цепочка: агент → manager (1514/tcp) → indexer → dashboard

## Разборы

- [5710 — вход под несуществующим пользователем](5710-invalid-user.md)
