# Aula 14 (15/09/2025) - Implementação do Publisher/Subscriber
## Tema: Padrão Observer com Azure Service Bus

- Estudo prático do **padrão Observer** aplicado em sistemas distribuídos.  
- Uso do **Azure Service Bus** para implementar comunicação assíncrona baseada em tópicos.  
- Estrutura geral:
  - **Publisher**: envia mensagens (eventos) para o tópico.  
  - **Subscriber**: consome mensagens publicadas, reagindo de forma independente.  
- Implementação realizada em **Java**, utilizando SDK do Azure.  

### Conceitos-chave
- **Desacoplamento**: publishers não precisam conhecer os subscribers.  
- **Escalabilidade**: múltiplos subscribers podem ser adicionados sem alterar o publisher.  
- **Confiabilidade**: Azure Service Bus garante entrega e persistência de mensagens.
