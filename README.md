# [Curso de Python: aplicando a Orientação a Objetos](https://cursos.alura.com.br/course/python-aplicando-orientacao-objetos)
Faça esse curso de Python web e:
- Entenda a importância da Orientação a Objetos com Python
- Descubra a importância de classes e atributos inspirado um projeto real
- Utilize métodos estáticos e encapsulamento
- Entenda como as propriedades como elas podem conter lógica adicional além de simplesmente acessar e atribuir valores
- Compreenda como as classes no Python podem organizar e estruturar seu código de forma eficiente
- Aprenda a usar o construtor para inicializar objetos e definir seus estados iniciais

# 1. Classes: O que aprendemos?
- Exploramos o conceito de classe no desenvolvimento orientado a objetos (OO) e compreendemos que uma classe é uma estrutura que define um tipo específico de objeto.
- Compreendemos a importância das classes no paradigma de programação orientada a objetos, destacando como elas permitem organizar o código de forma mais modular e reutilizável.
- Iniciamos a construção da nossa primeira classe, denominada Restaurante, em que aprendemos a definir atributos específicos da instância de um restaurante, como nome, categoria e ativo.

----

# 2. Construtor e instanciando objetos: O que aprendemos?
- Demonstramos a utilização do construtor `__init__`, o qual é responsável por inicializar os atributos da instância, incluindo a definição padrão de ativo como `False`.
- Exploramos a criação de instâncias da classe Restaurante, destacando como atribuir valores aos atributos da instância durante a criação de um objeto.
- Compreendemos a distinção entre atributos de classe e atributos de instância, e focamos como os atributos específicos da instância são acessados e manipulados dentro da classe.
- Observamos como a classe Restaurante pode ser expandida para incluir outros métodos e comportamentos específicos dos restaurantes em desenvolvimento.

---

# 3. Property e métodos de classe: O que aprendemos?
- Exploramos como criar atributos em classes e utilizando underscore (underline) para indicar que um atributo é protegido.
- Praticamos o uso da função `property` em outros atributos, como `categoria` e `ativo`, proporcionando uma abordagem mais controlada e facilitando o acesso aos valores desses atributos.
- Criamos e utilizamos métodos de classe, que são métodos que agem sobre a classe como um todo, em vez de uma instância específica. No exemplo, criamos o método `listar_restaurantes` para exibir uma lista formatada dos restaurantes.
- Demonstramos o conceito de abstração ao utilizar a propriedade `ativo` para apresentar visualmente o estado ativo ou inativo de um restaurante.

---

# 4. Importando classe e composição: O que aprendemos?
- Aprendemos a importar classes em arquivos Python, utilizando essa habilidade para importar a classe Restaurante para o arquivo principal (main.py), permitindo-nos utilizar suas funcionalidades em nosso programa.
- Exploramos ainda mais os princípios da Programação Orientada a Objetos (OO), criando uma nova classe para reforçar conceitos fundamentais. Entendemos como a criação de classes e instâncias proporciona uma estrutura organizada e modular para o código.
- Avançamos na integração entre classes, especificamente entre as classes Restaurante e Avaliação. Agora, temos uma lista de objetos de avaliação associados a cada restaurante, demonstrando a relação e interdependência entre diferentes entidades em um sistema.
- Utilizamos técnicas de listagem para criar funcionalidades que nos permitem visualizar as avaliações associadas a cada restaurante. Isso consolidou nosso entendimento sobre como gerenciar e apresentar dados de maneira eficiente em nossos programas.

---

# 5. Consolidando os conhecimentos: O que aprendemos?
- Abordamos a importância de criar docstrings no código, que são comentários incorporados diretamente no código-fonte para documentar funções, métodos, módulos ou classes.
- Exploramos o momento adequado para criar docstrings, destacando que elas são especialmente úteis quando se desenvolve aplicações que podem ser compartilhadas com outros desenvolvedores. Documentar o propósito, parâmetros e comportamento de funções facilita a compreensão e colaboração no código.
- Discutimos situações em que pode não ser necessário criar docstrings, como em códigos muito simples e autoexplicativos, onde o propósito das funções é óbvio ou em projetos pessoais de curto prazo.
- Enfatizamos que a prática consistente de documentar o código através de docstrings contribui para a manutenção eficiente do código ao longo do tempo, facilitando a resolução de problemas, a implementação de novos recursos e a colaboração entre membros da equipe.

---

# Referências
### 1. [Documentação oficial do Python (gratuito, português, texto)](https://docs.python.org/pt-br/3/)
`Fonte oficial de informações sobre a linguagem Python. Aqui você encontra informações sobre os conceitos relacionados ao desenvolvimento da linguagem, tutoriais, referências, informações de atualizações, boas práticas e exemplos.`

### 2. [Artigo sobre classes com Python (gratuito, português, texto)](https://www.alura.com.br/artigos/python-poo-engenharia-dados)
`Mais sobre a Programação Orientada a Objetos através de exemplos de código em Python explorando as características desse conceito.`

### 3. [W3S de Python (gratuito, inglês, texto)](https://www.w3schools.com/python/)
`Recurso educacional online que fornece tutoriais, referências e exemplos práticos para aprender Python, uma linguagem de programação de alto nível.`

### 4. [Documentação oficial do Python sobre Classes (gratuito, inglês, texto)](https://docs.python.org/3/tutorial/classes.html)
`Documentação oficial do Python 3, especificamente para a seção do tutorial que aborda o conceito de classes em Python. A documentação oficial do Python é mantida pela Python Software Foundation e é uma fonte autoritativa de informações sobre a linguagem de programação Python.`