deploy_app_v2
=========

Essa role faz o deploy da versão v2 da aplicacao e faz o scale out da versão v1.

- Escala o app-v2 para 10 instâncias.
- Escala o app-v1 para 1 instância.
- Remove o app-v1 após 2 minutos.