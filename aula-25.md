# Aula 25 (10/11/2025) - Arquitetura de Microsserviços
## Resumo da Arquitetura de Microsserviços

Os microsserviços decompoem o sistema em serviços independentes, cada um executando em seu próprio processo e gerenciando seu banco de dados específico. Características principais:
- **Isolamento de dados**: Cada serviço possui seu modelo de dados
- **Comunicação via API**: Serviços se comunicam através de interfaces bem definidas
- **Independência tecnológica**: Serviços podem usar stacks diferentes
- **Implantação independente**: Cada serviço pode ser atualizado sem afetar os outros

Padrões como Saga gerenciam transações distribuídas, enquanto a camada de API atua como ponto único de entrada, sem conter lógica de negócio.
