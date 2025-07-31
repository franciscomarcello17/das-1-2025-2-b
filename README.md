# das-1-2025-2-b
Repositório para anexação das atividades de Design e Arquitetura de Software

## Aula 1 - Apresentação da Disciplina e Introdução a DAS-I

Os principais padrões de arquitetura incluem MVC, programação orientada a serviços, monolito, etc. Esses padrões visam melhorar a organização, manutenibilidade e escalabilidade do código.


## Aula 2 - Arquitetura de Código (Falando sobre livro de Eng de Software Moderna)

### Abstração:

Uma boa estrategia para combater a complexidade de um software é a criação de abstrações (entender o mundo real e criar uma solução em código)

```bash
Entidade -> Abstração de elementos do mundo real
Repositório -> Abstração de elementos do banco de dados
Serviço -> Abstração da lógica de negócios
Controlador -> Abstração de funcionalidades do backend
```
### Complexidade

Complexidade em software trata-se da dificuldade de entender, modificar e manter um sistema devido à quantidade de elementos, suas interações e a falta de clareza em sua estrutura.

### Conjunto de boas praticas para Desenvolvimento Orientado a Objetos

- Aderir ao padrão de nomenclatura daquela linguagem específica(camelCase, PascalCase, etc)
- Utilização de Frameworks para padronização de métodos
- Utilização de estrutura de dados correta

### Estradas pavimentadas

Ao desenvolver verificar se existe algo que ja foi testado, por vezes sobre o gasto de milhões de reais/dólares, acaba se tornando uma boa prática, pois, além da economia de dinheiro, obtém-se economia de tempo, utilizando-se de estratégias e conhecimentos que já foram lapidados.

### Ocultamento de Informação

A classe faz a ocultação de informacões por meio do encapsulamento, o que traz as seguintes vantagens para o sistema:

- Desenvolvimento em paralelo - Ao ocultar informações torna-se mais facil o desenvolvimento em paralelo por conta da proteção aos metodos, classes e etc.
- Flexibilidade a mudanças - Ao ocultar informações, consegue-se modificar objetos que conversam entre si, porém que não se "conhecem" sem danificar o código.

