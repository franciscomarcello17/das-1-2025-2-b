# Aula 18 (09/10/2025) - Circuit Breaker Pattern
## Resumo do Padrão Circuit Breaker

Este padrão é crucial para sistemas distribuídos, atuando como um proxy que monitora falhas em chamadas a serviços externos. Quando o número de falhas excede um limite pré-definido, o circuit breaker "abre", interrompendo temporariamente as chamadas para evitar sobrecarga e permitir a recuperação do serviço.

O circuit breaker opera em três estados:
- **Fechado**: Operação normal, com monitoramento de falhas
- **Aberto**: Chamadas são bloqueadas imediatamente, retornando erro sem consumir recursos
- **Meio-Aberto**: Permite tentativas limitadas para verificar se o serviço se recuperou

A implementação desse padrão aumenta significativamente a resiliência do sistema, prevenindo falhas em cascata e melhorando a experiência do usuário final ao evitar longos tempos de espera por serviços indisponíveis.
