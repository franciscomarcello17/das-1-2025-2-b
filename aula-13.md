# Aula 13 (11/09/2025) - Trade-offs em Tópicos vs Filas

### Vantagens do uso de tópicos (publish/subscribe)
- **Extensibilidade arquitetural**: fácil adicionar novos serviços sem alterar o produtor.  
- **Desacoplamento**: o produtor não precisa conhecer os consumidores.  

### Desvantagens do uso de tópicos
- **Segurança**: dados mais expostos, qualquer consumidor pode escutar.  
- **Contrato único**: todos os serviços precisam consumir a mesma estrutura de dados.  
- **Monitoramento limitado**: mais difícil aplicar autoescalabilidade.  

### Vantagens do uso de filas (point-to-point)
- **Segurança**: cada fila é consumida por um destinatário específico.  
- **Contratos heterogêneos**: cada serviço pode ter seu próprio formato de dados.  
- **Escalabilidade programática**: filas podem ser monitoradas individualmente.  

### Conclusão
- Não existe escolha definitiva entre filas e tópicos.  
- A decisão depende do **que é mais importante no contexto**:  
  - **Extensão e desacoplamento** (tópicos)  
  - **Segurança, flexibilidade de contrato e monitoramento** (filas).  
