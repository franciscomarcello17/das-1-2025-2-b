# Aula 20 (16/10/2025) - Retry Pattern e Arquiteturas Distribuídas
## Resumo do Retry Pattern e Falácias da Computação Distribuída

O Retry Pattern gerencia falhas transitórias através de tentativas automáticas de reconexão, utilizando estratégias como:
- **Repetição Imediata**: Para falhas raras e aleatórias
- **Repetição com Atraso**: Para problemas de congestionamento
- **Cancelamento**: Quando a falha é permanente

As oito falácias da computação distribuída alertam sobre pressupostos perigosos:
1. A rede é confiável
2. A latência é zero
3. A largura de banda é infinita
4. A rede é segura
5. A topologia não muda
6. Há apenas um administrador
7. O custo de transporte é zero
8. A rede é homogênea

Reconhecer estas falácias é essencial para projetar sistemas distribuídos resilientes.
