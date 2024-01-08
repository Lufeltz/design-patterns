# Design Patterns

Repositório criado com o intuito de aprender e exemplificar através da linguagem C# o uso dos 23 principais padrões de design a seguir:

### Creational Patterns (Padrões de Criação)
- Singleton: Garante a existência de apenas uma instância de uma classe e fornece um ponto global de acesso a essa instância.
- Factory Method: Define uma interface para criar um objeto, mas deixa as subclasses alterarem o tipo de objetos que serão criados.
- Abstract Factory: Fornece uma interface para criar famílias de objetos relacionados ou dependentes sem especificar suas classes concretas.
- Builder: Separa a construção de um objeto complexo de sua representação, permitindo a mesma construção criar diferentes representações.
- Prototype: Cria novos objetos a partir da cópia de um objeto existente, promovendo a criação de novos objetos por meio da clonagem.

### Structural Patterns (Padrões Estruturais)
- Adapter: Permite que a interface de uma classe existente seja usada como interface de outra classe.
- Bridge: Desacopla uma abstração de sua implementação, permitindo que ambas variem independentemente.
- Composite: Compartilha a mesma interface entre objetos individuais e composições de objetos.
- Decorator: Adiciona responsabilidades a objetos de forma dinâmica.
- Facade: Fornece uma interface unificada para um conjunto de interfaces em um subsistema.
- Flyweight: Usa o compartilhamento para suportar eficientemente grandes quantidades de objetos de granularidade fina.
- Proxy: Fornece um representante ou substituto para controlar o acesso a um objeto.

### Behavioral Patterns (Padrões Comportamentais)
- Chain of Responsibility: Passa uma solicitação ao longo de uma cadeia de manipuladores.
- Command: Encapsula uma solicitação como um objeto, permitindo parametrização de clientes com diferentes solicitações, fila de solicitações e registro de solicitações.
- Interpreter: Fornece uma maneira de avaliar a linguagem gramatical ou expressão de uma linguagem.
- Iterator: Fornece uma maneira de acessar sequencialmente os elementos de um objeto composto sem expor a representação subjacente.
- Mediator: Define um objeto que encapsula como os objetos interagem, promovendo o acoplamento fraco entre eles.
- Memento: Captura e externaliza um estado interno de um objeto, permitindo que o objeto seja restaurado para este estado mais tarde.
- Observer: Define uma dependência um-para-muitos entre objetos para que, quando um objeto mude de estado, todos os seus dependentes sejam notificados e atualizados automaticamente.
- State: Permite que um objeto altere seu comportamento quando seu estado interno muda.
- Strategy: Define uma família de algoritmos, encapsula cada um deles e os torna intercambiáveis.
- Template Method: Define o esqueleto de um algoritmo na superclasse, permitindo que as subclasses alterem partes desse algoritmo sem mudar sua estrutura.
- Visitor: Representa uma operação a ser executada nos elementos da estrutura de objetos.
