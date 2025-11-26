# Aula 15 (18/09/2025) - Implementação do Publisher/Subscriber
## Tema: Continuação - Observer no Azure Service Bus com Java

- Consolidação da implementação iniciada na aula anterior.  
- Configuração detalhada de **tópicos e assinaturas** no Azure Service Bus.  
- Exemplos práticos em **Java**:
  - Criação de um **publisher** enviando mensagens para um tópico.  
  - Criação de múltiplos **subscribers**, cada um consumindo a mensagem do tópico.  
- Demonstração da **extensibilidade**: novos serviços podem se inscrever no tópico sem modificar o publisher.  

### Reflexão
- O padrão Observer via Service Bus reforça conceitos de **arquitetura orientada a eventos**.  
- Mostra na prática os trade-offs estudados:  
  - **Vantagem**: facilidade de expansão e desacoplamento.  
  - **Desvantagem**: necessidade de atenção à segurança, contratos de dados e monitoramento.  
