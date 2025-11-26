# Aula 22 (03/11/2025) - Arquitetura Microkernel
## Resumo da Arquitetura Microkernel

Também conhecida como arquitetura plugin, este estilo divide a aplicação em:
- **Sistema Central**: Funcionalidades essenciais e mínimas
- **Componentes de Plug-in**: Funcionalidades especializadas e independentes

O sistema central funciona como um orquestrador que gerencia os plug-ins através de um registro central. Cada plug-in é autônomo, podendo ser desenvolvido, testado e implantado separadamente.

Esta arquitetura é amplamente utilizada em aplicações como IDEs (Eclipse), ferramentas de desenvolvimento (Jenkins) e navegadores, onde a extensibilidade é um requisito fundamental.
