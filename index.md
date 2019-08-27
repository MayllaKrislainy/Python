# Linguagem Python

Python é uma lingagem de progamação de altíssimo nível, possui comandos mais próximos da linguagem humana, é uma linguagem livre e multiplataforma, é uma linguagem que foi criada para produzir código bom e fácil de manter de maneira rápida, é uma linguagem orientada a objeto e altamene modular.

## Vantagens de aprender Python

  **1. Simples e fácil de aprender**
  
  No Python, você não precisa lidar com a sintaxe complexa.
  
  **2. Portátil e Extensivel**
  
  O Python é suportado pela maioria das plataformas presentes no mercado atual.
  
  **3. Desenvolvimento Web**
  
  O Python tem uma matriz de frameworks para desenvolvimento de websites.

  **4. Biblioteca Padrão**
  
  A biblioteca padrão do Python é imensa, nela contém classes, métodos e funções para realizar essencialmente qualquer tarefa, desde acesso a bancos de dados a interfaces gráficas com o usuário.
 
  **5. Scripting e Automação**
  
   O Python também pode ser usado como linguagem de script.
   
  **6. Big Data**
  
   O Python é amplamente usado para Big Data, pois você pode processá-lo facilmente.
   
## Desvantagens

**1. Existem problemas de desempenho no Python.**

**2. Algumas versões do Python são incompatíveis entre si, como a versão 2 e a 3.**

**3. Pode ser que o Python não possua uma documentação tão boa quanto outras linguagens, como o Java**

## Como Instalar

   **•WINDOWS**
  
   Acesse o site [Python Software Fundation](https://www.python.org/downloads/).
  
   [PDF Tutorial](http://www.filosofiacienciaarte.org/attachments/article/1026/instalarPython.pdf).
  
   [Video Tutorial](https://youtu.be/X2C3HG_ynGM).
  
   **•LINUX**
   
  Algumas versões do Linux já vem com o Python instalado, para verrificar se seu linux já tem o Python instalado, digite em um terminal:
  
   ``$ which python``
   
   ou
   
   ``$ which python3``
   
   que deve retornar algo como ``/usr/bin/python``. Isso significa que o Python está instalado nesse endereço.
   
   Caso contrário, acesse o site [Python Brasil](https://python.org.br/instalacao-linux/).
  
   **OU..**
  
   Caso você não queira instalar o python, você pode optar pelo site [relp.it](https://repl.it/).
   
   Esse site provê um ambiente configurado para as linguagens de progamação, incluindo Python...
   
   
   
   _Após instalarmos o Python, vamos instalar a IDE. Você pode trabalhar com sua IDE favorita_
   
   
## Melhores IDEs e Editores de Texto para Python
 
   Alguns editores de texto recomendados são:
  
   **•Sublime Text**
  
   **•Vim**
  
   **•Emacs**
  
   **•TextMate**
  
   Entretanto, se você já tem o hábito de usar IDE e tem certeza de que não quer experimentar um estilo mais simples de programar, tente    as opções a seguir e escolha a que for mais confortável para você:
 
   **•PyCharm**
 
   **•WingIDE**
 
   **•Atom**
 
   **•Visual Studio**
 
   Para mais informações sobre IDEs e Editores de texto acesse: [Qual a melhor IDE para Python](http://rodrigoamaral.net/2012/11/11/qual-a-melhor-ide-para-python/).
   
   
## Os primeiros comandos do Python
 
 **•COMANDOS BASICOS**
 
 _Entrada de Dados:_ input();
 
    dados informados pelo usuario.
 
 _Saida de Dados:_ print();
       
    responsavel pela impressão na tela do conteúdo que lhe é informado.
 
 **•VARIAVEIS**
 
  Assim como em outras linguagens, o Python pode manipular variáveis básicas como strings (palavras ou cadeias de caracteres), inteiros   e reais (float). Para criá-las, basta utilizar um comando de atribuição, que define seu tipo e seu valor.
  
  _Tipos:_
  
  • int (inteiro);
  • float (reais);
  • string / char (caracteres);
  • boolean (True/False);
  
  **•OPERADORES**
  
   Operadores são símbolos que representam operações matemáticas. Os principais são: +, -, *, / e ** , que representam, respectivamente,    adição, subtração, multiplicação, divisão e exponenciação. 
   
   Existem também operadores relacionais ou comparativos, que são: >, <, ==, >=, <=, eles representam maior que, menor que, igual, maior    ou igual que, menor ou igual que.
   
## Estruturas Condicionais
 
  **•if:**
 
   É usado para avaliar uma expressão e se o resultado for satisfatorio executa uma determinada ação.
  
   **•else:**
  
   Caso a condição _if_ não seja satisfeita, outra ação no caso _else_, é executada.
 
   **•elif:**
 
   Avalia mais de uma condição, ou seja, expressões intermediarias. 
  
   **EXEMPLOS:**
  
  ```markdown
  a = 2
  `if` a < 1:
     `print`("a eh menor que 1")
  `elif` a == 1:
      `print`("a eh igual a 1")
  `else`:
      `print`("a eh maior que 1")
  ```
  
## Laços de Repetição
  
   **•while:**
  
   O comando _while_ faz com que um conjunto de instruções seja executado enquanto uma condição é atendida.
   
   **•for:**
   
   É uma estrutura que geralmente analisa os elementos de uma lista e então executa determinada ação.
   
   **EXEMPLOS:**
   
   _Codigo que mostra numeros de 0 ate 10:_
  ```markdown
  cont = 0
  `while` cont < 10:
      `print`(cont)
      cont += 1
   ```
  _Codigo que mostra numeros pares entre 1 e 10:_
  ```markdown    
  `for` x `in` [1,2,3,4,5,6,7,8,9,10]:
     `if` x%2 == 0:
         `print`(x)
  ```
  
## Listas, Tuplas, Filas e Pilhas
  
  **•lista:**
  
  É uma estrutura de dados compposta por itens organizados de forma linear na qual cada uma pode ser acessada a partir de indice que representa sua posição na coleção (iniciando em 0).
  
  ![Image](https://uploaddeimagens.com.br/images/002/298/724/full/listaphyton.jpg?1566934771)
  
  **•tuplas:**
  
  
  **•filas e pilhas:**
  
  
  
  
## Exercícios Recomendados

 
## Livros e Cursos
 
  _Livros:_
  
  • Learn Python the Hard Way - Zed Shaw
  
  • Treading on Python: Beginning Python Programming
  
  • Think Python: How to Think Like a Computer Scientist
  
  _Cursos:_
  
  • [Introdução à Ciência da Computação com Python Parte 1 (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos)
  
  • [Python Básico](https://solyd.com.br/treinamentos/python-basico)
  
  • [Python para Zumbis](https://www.youtube.com/playlist%E2%80%A6)
  
  • [Curso python 3 by Guanabara](https://www.youtube.com/watch%E2%80%A6)
 
 
## Referencias e Recomendações
 
   • [O que é python?](https://www.devmedia.com.br/aprendendo-a-programar-em-python-introducao/17093)
   
   • [Por que Python?](http://pyscience-brasil.wikidot.com/python:python-oq-e-pq)
   
   • [Motivos pra aprender Python](https://www.hostgator.com.br/blog/10-motivos-para-voce-aprender-python/)
   
   • [Primeiros passos com o Python](https://www.devmedia.com.br/primeiros-passos-com-o-python/37003)
   
   • [PDF - Inrodução a Python](http://www.filosofiacienciaarte.org/attachments/article/1026/pythonbasicoUNESP.pdf)
   
   • [Slide sobre Python: variaveis, operadores e etc](http://www.filosofiacienciaarte.org/attachments/article/1026/Modulo%20II%20-%20ProCom.pdf)
   
