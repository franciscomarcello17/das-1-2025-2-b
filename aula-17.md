# Aula 17 (06/10/2025) - Definição das Características da Arquitetura
## Resumo do capítulo 4 do livro: Fundamentos da arquitetura de software: uma abordagem de engenharia

Este capítulo introduz o conceito de características da arquitetura, que são aspectos críticos do sistema que vão além dos requisitos funcionais de negócio. Elas especificam critérios operacionais e de design essenciais para o sucesso do software, como desempenho, segurança e confiabilidade, influenciando diretamente as decisões estruturais da aplicação.

As características da arquitetura atendem a três critérios fundamentais:
- **Especificam considerações de design fora do domínio**: Definem "como" o sistema deve operar em vez de "o que" ele deve fazer
- **Influenciam aspectos estruturais de design**: Requerem decisões arquiteturais específicas para seu sucesso
- **São essenciais para o sucesso da aplicação**: Impactam diretamente a eficácia da solução

### Classificação das Características
- **Operacionais**: Disponibilidade, continuidade, desempenho, segurança, recuperabilidade, robustez e escalabilidade
- **Estruturais**: Configuração, extensão, instalação, aproveitamento, localização, manutenção, portabilidade e suporte
- **Transversais**: Acessibilidade, armazenamento, autenticação, autorização, legalidade, privacidade, segurança e usabilidade

### Trade-offs Arquiteturais
Não existe uma lista definitiva de características, pois cada projeto tem necessidades únicas. Os arquitetos frequentemente enfrentam conflitos entre características - melhorar uma (ex: segurança) pode prejudicar outra (ex: desempenho). Por isso, busca-se a "arquitetura menos pior" em vez da solução perfeita, priorizando características essenciais e evitando complexidade excessiva através de abordagens iterativas e adaptáveis.