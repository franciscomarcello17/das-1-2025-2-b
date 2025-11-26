# Aula 20 (20/10/2025) - Arquitetura em Camadas
## Resumo da Arquitetura em Camadas (n-tier)

A arquitetura em camadas organiza o sistema em níveis horizontais especializados, sendo o estilo mais comum pela sua simplicidade e baixo custo. As camadas típicas incluem:
- **Apresentação**: Interface com o usuário
- **Negócio**: Regras e lógica da aplicação
- **Persistência**: Acesso a dados
- **Banco de Dados**: Armazenamento físico

Esta arquitetura promove separação de concerns através de camadas fechadas, onde cada nível só se comunica com seus adjacentes. Embora excelente para aplicações pequenas e médias, apresenta limitações em escalabilidade e pode sofrer com alto acoplamento se mal implementada.
