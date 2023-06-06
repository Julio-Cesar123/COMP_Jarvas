# **Jarvas**

Igor Masson Calille

Julio Cesar Barboza Filho

Lucas Costa Pessoa Graziano

Luis Felipe Almeida Beserra Matos

Pedro Alcantara Krivochein

---

# **Introdução:**

Jarvas é uma linguagem de programação baseada em Java que busca facilitar seu uso. O primeiro objetivo é simplificar a sintaxe da linguagem Java ainda mantendo o idioma em inglês. Além disso, a sintaxe do Jarvas foi aprimorada para torná-la mais fácil de ler e escrever, reduzindo a quantidade de código necessário para realizar tarefas comuns. A proposta da criação da linguagem de programação vem do projeto proposto pelo professor Italo Santiago Vega, do quinto semestre de Ciência da Computação. O trabalho em questão se trata da projeção de uma linguagem de programação que forneça um código fonte equivalente em WebAssembly.

# **Tutorial da Linguagem**
Para uma melhor compreensão da nossa linguagem Jarvas, decidimos iniciar com um tutorial abrangente. Nesse tutorial, abordaremos os conceitos básicos da linguagem, como sintaxe, convenções lógicas e operações aritméticas.

Acreditamos que começar com esses tópicos é fundamental para que seja possível compreender a lógica por trás da nossa linguagem e, assim, utilizá-la de forma mais eficiente.

## **Hello World**
A melhor forma de apresentar a funcionalidade do código jarvas é mostrar a sintaxe através da escrita de algoritmos. Por conta disso, um exemplo introdutório clássico de qualquer linguagem de programação é imprimir "Hello World. Na linguagem de programação Jarvas, a forma mais simples para imprimir "Hello World" é:

```
print("Hello world!");
```
É possível executar o código diretamente no nível do módulo, sem a necessidade explícita de uma função main. Ao contrário de algumas linguagens de programação, como C ou Java, onde um programa começa sua execução a partir de uma função main, em Python, o código no nível superior do módulo é executado conforme é encontrado.

Quando você executa um arquivo em Jarvas, o interpretador começa a executar o código a partir do topo do arquivo e progride linha por linha. Isso significa que qualquer código que estiver fora de funções ou classes será executado imediatamente.

## **Exemplo de operação aritmética**
Como o projeto prioriza as operações aritméticas, optamos por fornecer um exemplo simples que demonstre o uso dessas operações na linguagem Jarvas, visando facilitar a compreensão. A seguir, apresentamos um exemplo de uma operação aritmética básica realizada na linguagem Jarvas:
```
int a = 1;
int b = 2; 

int c = a + b;

print(c);
```
A saída desse código será:

```
3
```

## **Sintaxe:**
A imagens abaixo apresenta como a linguagem de programação Jarvas irá se comportar através de algumas instruções básicas de qualquer linguagem de programação.

![Figura 1: Sintaxe](https://raw.githubusercontent.com/Julio-Cesar123/COMP_Jarvas/screenshots/Sintaxe1.jpg)

É possível notar que existe muitas similaridades e algumas misturas relacionadas com a linguagem jarvas em relação as linguagens de programação Python e Java.

# **Manual de referência da linguagem**

O manual de referência da linguagem foi inspirado no ***The GNU C Reference Manual*** e no apêndice A do livro ***Apêndice A do livro The C Programming Language***

## **Convenções Léxicas**
Na programação de computadores, as convenções lexicais são as regras que definem como os caracteres são agrupados em tokens em uma linguagem de programação. Tokens são os blocos básicos de construção de um programa e são usados para representar palavras-chave, variáveis, constantes, operadores e outros elementos da linguagem. Na imagem abaixo, é possível ver as convenções léxicas da linguagem de programação Jarvas.

![Figura2: Convenções Lexicas](https://raw.githubusercontent.com/Julio-Cesar123/COMP_Jarvas/screenshots/Convencoeslexicas.jpg)

## **Tokens**
Tokens são valores de identificação atribuídos a lexemas. Na linguagem Jarvas, existem sete tipos diferentes de classes de tokens: palavras chave, delimitadores, identificadores e literais, atribuição, operadores, condicionais, e de final do arquivo. Espaços em branco são desconsiderados pelo compilador.

Abaixo estão listados todos os tokens da linguagem Jarvas:

| | | | | | |
|----------------|--------------|--------------|--------------|--------------|--------------|
| IF             | ELIF         | ELSE         | WHILE        | FOR          | DO           |
| RETURN         | BREAK        |              |              |              |              |
| PAREN_L        | PAREN_R      | BRACE_L      | BRACE_R      | BRACKET_L    | BRACKET_R    |
| SEMICOLON      | COMMA        | DOT          | DOUBLE_DOT   |              |              |
| IDENTIFIER     | INTEGER      | FLOAT        | STRING       | CHAR         | BOOLEAN      |
| EQUAL          |              |              |              |              |              |
| PLUS           | MINUS        | TIMES        | DIVIDE       |              |              |
| EQUALS         | NOT_EQUAL    | GREATER_THAN | LESS_THAN    | GREATER_EQUAL| LESS_EQUAL   |
| EOF            |              |              |              |              |              |

## **Comentários**
?

## **Regex:**
Expressões regulares (regex) são uma ferramenta extremamente poderosa e versátil para pesquisar, extrair e manipular texto de maneira eficiente. Elas oferecem uma ampla gama de recursos e funcionalidades que permitem realizar tarefas complexas de processamento de texto com facilidade.

Na imagem abaixo, apresentamos alguns exemplos ilustrativos de como nosso regex foi desenvolvido para realizar essas operações textuais.

![Figura 3: Tabela de Regex](https://raw.githubusercontent.com/Julio-Cesar123/COMP_Jarvas/screenshots/Regex1.jpg)
![Figura 4: Tabela de Regex (2)](https://raw.githubusercontent.com/Julio-Cesar123/COMP_Jarvas/screenshots/Regex2.jpg)
![Figura 5: Tabela de Regex(3)](https://raw.githubusercontent.com/Julio-Cesar123/COMP_Jarvas/screenshots/Regex3.jpg)

## **Identificadores**
Um identificador é uma sequência de símbolos validos usados para identificar um elemento, seja ele uma função ou variável. O primeiro caractere pode ser uma letra maiúscula, minúscula, underscore ou dollar sign ($). Subsequente a essa primeira parte, é possível definir o mesmo padrão: uma ou mais letras maiúsculas, letras minúsculas, underscores ou dollar signs ($) ou dígitos.

## **Palavras chave**
São palavras que são usadas com um propósito específico na linguagem Jarvas e que não podem ser usadas em outro lugar.

| | |
|--------------|---------------|
| `if`         | `do`          |
| `elif`       | `return`      |
| `else`       | `break`       |
| `while`      | `fun`         |
| `for`        |               |

## **Constantes**
Uma constante é um valor fixo. Na linguagem Jarvas as constantes são:

constant
: INTEGER
| FLOAT
| STRING
| CHAR
| BOOLEAN

Uma constante de inteiro é formada por um ou mais dígitos podendos ser precedida ou não por um sinal de menos ou mais.
Exemplo: +1, -1, 129

Uma constante de float é formada por um ou mais dígitos, com um ponto marcando o início do número em decimal formado por um ou mais dígitos. Podendo ser precedida ou não por um sinal de menos ou mais.
Exemplo: +1.3, -1.0, 129.333

Uma string é formada por uma sequência de caracteres delimitada por aspas duplas.
Exemplo: "Hello, world"

Um caractere é formado por um único caractere entre apóstrofos simples.
Exemplo: 'O'

Um boolean é formado ou pelo símbolo ***true*** ou pelo símbolo ***false***

## **Operadores de soma**
São respectivamente + e -

sumOperator
: PLUS
| MINUS

## **Operadores de multiplicação**
São respectivamente * e /

multiplifierOperator
: TIMES
| DIVIDE

## **Operadores relacionais**
São respectivamente ==, !=, >, <, >=, <=:

relationalOperator
: EQUALS
| NOT_EQUAL
| GREATER_THAN
| LESS_THAN
| GREATER_EQUAL
| LESS_EQUAL

## **Expressão inteira**

integerExpression
: INTEGER multiplifierOperator integerExpression
| INTEGER sumOperator integerExpression
| '('integerExpression')' 
| INTEGER

## **Expressão de float**

floatExpression
: FLOAT multiplifierOperator floatExpression
| FLOAT sumOperator floatExpression
| '('floatExpression')' 
| FLOAT

## **Expressão booleana**

booleanExpression
: BOOLEAN relationalOperator booleanExpression
| '('BOOLEAN')' 
| BOOLEAN

## **Expressão de char**

charExpression
| '('charExpression')' 
| CHAR

## **Expressão de string**

stringExpression
| '('stringExpression')' 
| STRING

## **Expressões**
Uma expressão é uma combinação de valores, variáveis, operadores e funções que são avaliados para produzir um resultado. 

expression
: constant
| integerExpression
| floatExpression
| charExpression
| stringExpression
| booleanExpression

## **Atribuição**

O conceito de atribuição refere-se à ação de atribuir ou associar um valor a uma variável em um programa de computador. É por meio das operações de atribuição que os valores são armazenados em variáveis para posterior uso e manipulação.

variableAssignment : 
| IDENTIFIER EQUAL expression
| 'var' IDENTIFIER EQUAL expression

## **Declaração de variável**

Uma declaração de variável é uma instrução em um programa de computador que reserva um espaço de memória para armazenar um valor e associa um nome a esse espaço de memória.

variableDeclaration : 'var' variableAssignment

## **Statements de seleção**

Statements condicionais, também conhecidos como estruturas de controle condicional, são construções de programação que permitem ao programa tomar decisões com base em condições específicas.

ifStatement
: IF '('condition')' '{' block '}'

ifElseStatement
: ifStatement ELSE '{' block '}'

ifElifStatement
: ifStatement ELIF '('condition')' '{' block '}'

ifElifElseStatement
: ifElifStatement ELSE '{' block '}'

# **Plano do projeto**
! (FAZER UM CRONOGRAMA DO GRUPO)

Como plano de projeto da linguagem, utilizamos do cronograma fornecido e os requisitos transcritos pelo professor para realizarmos uma base de construção do projeto. Com o intuito de melhor organizar o desenvolvimento, realizamos uma separação do grupo de acordo os seguintes papéis:

* Gerente de projetos: Julio Cesar Barboza Filho 

* Integrador de sistemas: Luis Felipe Almeida Beserra Matos

* Arquiteto de sistemas: Igor Masson Calille

* Testador: Lucas Costa Pessoa Filho

* Guru da linguagem: Pedro Alcantara Krivochein

Ao decorrer da criação da linguagem, encontramos questões e dificuldades que fizeram com que os papeis não fossem rigorosamente seguidos. Dessa forma, cada integrante do grupo se ajudou com o intuito de evitar o sobrecarregamento de um determinado papel.

Além disso, para abordar cada fase da modelagem de implementação de uma forma precisa, utilizamos dos fundamentos essenciais pré-determinados pelo professor a qual uma linguagem baseada no documento da linguagem Java deve oferecer suporte, sendo estes:

1. Definição de variáveis e tipos de dados
2. Definição de procedimentos com parâmetro
3. Expressões aritméticas, relacionais e lógicas
4. Escopos global e local
5. Geração de código para WebAssembly



# **Evolução da linguagem**


Ao longo do desenvolvimento do Jarvas, aprendemos a importância de tomar decisões embasadas na documentação da linguagem Java e estar abertos ao feedback do professor. À medida que refinamos a sintaxe, a semântica e as funcionalidades da linguagem, buscamos equilibrar aspectos estéticos, didáticos e de usabilidade. Nosso objetivo é criar uma linguagem que seja intuitiva e capaz de atender às necessidades dos programadores que a utilizarem. 

Conforme avançávamos no desenvolvimento do compilador, recebemos um comentário do professor em relação a estruturação da sintaxe das instruções, para tornar o código mais intuitivo e lógico, decidimos trocar a delimitação das expressão que antes era representadas como no exemplo a seguir:

``` 
if:  expressão  {  instrução  }
``` 
E que foram substituídas para:

``` 
if ( expressão ) { instrução }
``` 
Ou seja, escolhemos delimitar as expressões com a utilização de parênteses como em Java

A evolução desse projeto nos mostra como a criação de uma linguagem de programação é um processo iterativo e desafiador. 

Nos baseamos no procedimento de compilação que foi ensinado durante a disciplina de compiladores, por isso, tratamos da análise léxica inicialmente, depois a análise sintática e a análise semântica. Após isso tratamos da questão da geração do código objeto e do código executável.

Após a primeira apresentação tivemos que realizar correções como a citada acima que foi passada pelo professor e seguimos com o projeto sem encontrar problemas que parassem completamente toda a equipe.

! (COMPLETAR COM MAIS INFORMAÇÕES ESPECIFICAS DO PROJETO E CORREÇÕES DA SEGUNDA APRESENTAÇÃO)

# **Arquitetura do compilador**
!(FAZER UML)

# **Ambiente de desenvolvimento**
Durante o desenvolvimento do projeto, utilizamos o Visual Studio Code, um editor de código-fonte que oferece suporte a linguagem de programação Java e a documentação em Markdown, que também foi utilizado para realizar testes do compilador.

Como complemento, utilizamos o Live Share, uma extensão do Visual Studio Code que permitiu a colaboração em tempo real entre os integrantes do grupo

# **Plano de testes**
- Funções básicas da linguagem

Nessa etapa, foi feito testes relacionados com atribuição de valores, execução de impressão de valores na tela de saída.

- Operações de lógica

Nessa etapa, foi feito a validação dos operadores lógicos, isso inclui o AND, OR e NOT.controle de fluxo, testes com tipos de dados e afins.

- Operações aritméticas

Nessa etapa, foi realizada uma validação abrangente dos operadores matemáticos existentes na linguagem, a fim de assegurar sua correta implementação e funcionamento. Para isso, foram conduzidos testes rigorosos para garantir que as operações de soma, subtração, divisão e multiplicação estejam sendo executadas de acordo com as regras matemáticas estabelecidas.

- Geração de códigos
 
 Realizando testes finais para garantir que os códigos estejam sendo gerados de maneira correta, seguindo uma arquitetura adequada e eficiente.

# **Conclusões contendo lições aprendidas**
Uma das principais conclusões obtidas por meio deste projeto é a consolidação e aprofundamento dos conceitos fundamentais das linguagens de programação, bem como a experiência de construir uma linguagem do zero. Para nós, essa empreitada se mostrou desafiadora, uma vez que exigiu a aplicação simultânea dos conceitos apresentados nas aulas de compiladores ministradas pelo professor Italo, juntamente com o desenvolvimento da própria linguagem.

Com esse projeto, nós pudemos expandir nosso conhecimento sobre análise léxica, análise sintática, arquitetura de software e outros conceitos relacionados.

Encontramos diversas dificuldades durante o projeto, e tivemos que nos reunir para resolvê-las da melhor forma possível, os problemas encontrados fortaleceram nossa base conceitual e aumentaram nossa sensibilidade para projetos de maior complexidade.

Outro ponto interessante na confecção do projeto está na questão da documentação, ela é refinada e traz um formato interessante para o grupo trabalhar, com diversos elementos no relatório final, é possível explicar bem o projeto como um todo por esse motivo.

# **Apêndice contendo a listagem completa do código-fonte do compilador**
# **Referências**
ALFRED, Aho. Compilers: Principles, Techniques, and Tools. Boston, EUA: Pearson Education, 1986. ISBN 0-321-48681-1. 

The GNU C Reference Manual. https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html#Expressions. Acesso em 04 junho 2023

KERNIGHAN, Brian W.; Ritchie, Dennis M (1978). The C Programming Language (em inglês). Upper Saddle River, New Jersey: Prentice hall. 228 páginas

