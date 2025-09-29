# Aula 12 (08/09/2025) - Análise de Trade-offs

- Pensar como arquiteto é enxergar **vantagens e desvantagens** (trade-offs) em cada decisão técnica.  
- Em arquitetura, a resposta quase sempre é **“depende”**, pois não existe solução universal.  
- Arquitetura é definida pelo **contexto**: ambiente, orçamento, cultura da empresa, prazos e habilidades da equipe.  
- Não há respostas certas ou erradas, apenas **escolhas entre trade-offs**.  

### Exemplo prático: Sistema de Leilão
- Serviço “Quem dá o lance” envia lances para os serviços: Capturar, Rastrear e Analisar.  
- Opções de mensageria:
  - **Tópico (publish/subscribe)** → extensível e desacoplado.  
  - **Fila (point-to-point)** → cada consumidor recebe sua própria fila.  

### Reflexão
- Arquitetos precisam compreender **os benefícios e também os riscos** de cada solução.  
- A análise não termina na escolha inicial — é necessário avaliar **impactos de segurança, acoplamento, contratos e escalabilidade**.
