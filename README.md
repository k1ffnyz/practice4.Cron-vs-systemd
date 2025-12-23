# practice5.sops-demo

Практическая работа по управлению секретами с использованием **SOPS + Age**.

## Описание
В репозитории показан безопасный workflow хранения секретов:
- секреты хранятся только в зашифрованном виде
- приватные ключи не коммитятся в Git
- используется Age как криптографический backend для SOPS

## Используемые инструменты
- age
- sops
- git
- GitHub

## Структура проекта
practice5.sops-demo

├── .gitignore

├── .sops.yaml

├── README.md

└── secrets

└── database

└── postgres.enc.yaml