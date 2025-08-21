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
- Facilidade de entendimento - Fica mais facil entender o sistema isolando as informações

### Getters e Setters

## Aula 3 - Coesão, Acoplamento e SOLID

### Coesão

Trata-se de um codigo minimo para eu fazer uma tarefa bem feita. Toda classe deve implementar uma única funcionalidade ou serviço e todos os metodos e atributos de uma classe devem estar voltados para a implementação do mesmo serviço.

#### Coesão tem as seguintes vantagens:

- Facilita a implementação de uma classe, bem como o seu entendimento e manutenção.
- Facilita a alocação de um único responsável por manter uma classe.
- Facilita o reúso e teste de uma classe, pois é mais simples reusar e testar uma classe coesa do que uma classe com várias responsabilidades.

#### Separação de interesses: é uma propriedade desejável parecida com a coesão, ela defende que uma classe deve implementar apenas um interesse.

### Acoplamento

Acoplamento é o grau de dependência entre classes e pode ser aceitável ou ruim. É aceitável quando ocorre por meio de interfaces estáveis e uso de métodos públicos. Já o acoplamento ruim surge quando há dependência de implementações instáveis, como arquivos compartilhados ou variáveis globais. Existe o acoplamento estrutural (explícito no código) e o evolutivo (efeito de mudanças se propagarem). Minimizar o acoplamento e maximizar a coesão melhora a manutenção e a estabilidade do sistema.

### SOLID

É programar orientado a objetos 

Trata-se de um acrônimo:

**S**ingle Resposability Principle | Responsabilidade Única   |
**O**pen/Closed Principle          | Aberto/Fechado           |
**L**iskov Substitution Principle  | Substituição de Liskov   |
**I**nterface Segregation Principle| Segregação de Interfaces |
**D**ependency Inversion Principle | Inversão de Dependências |
