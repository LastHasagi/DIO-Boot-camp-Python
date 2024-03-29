_Pt 1 --> *Tipos de dados em Python*_

O que são tipos? 
- Definem as caracteristicas e comportamentos de um valor (objeto) para o interpretador. São eles quem delimitam a área de atuação do interpretador. 

Quais são os tipos de dados?
-Int: Inteiro, armazena numeros inteiros positivos ou negativos (sem casa decimal). Ex.: 10, -5.
-Float: Real/Flutuante, armazena numeros reais com casa decimal. Ex.: 3.14, -2.718.
-Complex: Numero complexo, armazena numeros complexos (com parte real e imaginaria)  . Ex.: 3+2j, -1-1j.
-Bool: Booleano, armazena valores verdadeiros(True) ou falsos(False) . Ex.: True, False.
-String: Texto, armazena uma sequencia de caracteres. Ex.: "Python", 'Python', '''
-Bytes: Armazena uma sequencia de bytes (0 a 255). Usado principalmente para trabalhar com arquivos. 
-Bytearray: Similar ao Bytes mas pode ser alterada. Usado para trabalhar com dados binarios. 
-List: Lista, contem varios elementos de diferentes tipos. Podem ser alteradas.  [1,2,'teste'].
-Tuple: Tupla, contem varios elementos de diferentes tipos. Nao podem ser alteradas depois de criada.  (1,2,'teste')
-Set: Conjunto, nao mantem ordem e nao permite repeticao. Mantem apenas unico elemento.  {1,2,3}.
-Dictionary: Dicionario, armazena pares chave/valor. A chave deve ser do mesmo tipo que o valor.  {'nome':'Pedro','idade':3}
-NoneType: Representa o valor nulo.  Significa ausencia de valor. 

_Pt 2 -->  *Modo interativo*_

O que é o modo interativo?
- Modo onde o DEV pode  digitar codigo direto no interpretador do Python e ver o resultado na hora. 

Como acessar o modo interativo? 
- No terminal basta digitar Python ou executando o scritp com a flag "python -i <nome do arquivo>". 

_Pt 3 --> *Variáveis & Constantes*_

O que é uma variável?
- Uma variavel é um espaço na memoria RAM dedicado a armazenamento de informações que podem mudar durante a execução do programa (receber outro valor).

O  que é uma constante?
- Uma constante é um nome definido para um valor que não vai mudar durante a execução do programa.

*Exemplos no arquivo var_const.py*
nome, idade e altura, são valores que podem mudar de acordo com o contexto do que está sendo executado. Nem todas as pessoas tem o mesmo nome, idade e altura. Agora pi é sempre 3.14 e a semana tem sempre 7 dias.

PORÉM...
NÃO EXISTEM CONSTANTE EM PYTHON!!!!!
Ainda assim, usamos a palavra reservada **global** para indicarmos que uma variável é global. Mas ela ainda pode ser alterada pelo script.
A única coisa perto disso é usar letras maiúsculas para indicar que algo é constante, porém isso é usado como convenção. 

Boas práticas:
- Snake case
- Nomes sugestivos
- Nome de constante sempre em maiusculo

_Pt 4 --> *Conversão de tipo*_

Para converter um tipo de dado para outro utilize as funções int(), float() e str(). 
Exemplo no arquivo converter_tipos.py.

_Pt 5 --> *Funções de entrada e  saída*_

A função input() pede um texto e retorna o usuario como string. 
A função print() serve para imprimir algo na tela.

Exemplos no código entrada_saida.py
