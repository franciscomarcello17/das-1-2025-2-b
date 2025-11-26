# Aula 21 (27/10/2025) - Arquitetura em Pipeline
## Resumo da Arquitetura em Pipeline

Inspirada no Unix, esta arquitetura conecta componentes independentes (filtros) através de canais unidirecionais, onde a saída de um filtro é a entrada do próximo. Os tipos de filtros incluem:
- **Produtor**: Origem do fluxo de dados
- **Transformador**: Modifica os dados recebidos
- **Verificador**: Aplica testes e validações
- **Consumidor**: Destino final do processamento

A arquitetura em pipeline é ideal para processamento linear de dados (ETL, processamento de textos) e oferece baixo acoplamento entre componentes, permitindo fácil reconfiguração e manutenção.
