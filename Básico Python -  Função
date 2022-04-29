# Dicas-de-Python
Dicas de programação


	FUNÇÕES
-Introdução as funções
	Esta seção consistira em explicar o que é uma função em python e como criar uma. As funções serão um dos nossos principais blocos de construção quando construímos quantidades maiores e menores de código para resolver problemas.
	Então, o que é uma função?
	Formalmente, uma função é um dispositivo útil que agrupa um conjunto de instruções para que elas possam ser executadas mais de uma vez. Elas também podem permitir especificar parâmetros que possam servir como entradas para funções.
	Em um nível fundamental, as funções nos permitem não ter que repetidamente escrever o mesmo código repetidas vezes. Se você lembrar das lições em strings e listas, lembre-se de que usamos uma função len() para obter o comprimento de uma string. Uma vez que verificar o comprimento de uma sequencia é uma tarefa comum, você provavelmente vai querer escrever uma função que pode fazer isso rapidamente.
	As funções serão um dos níveis mais básicos de códigos de reutilização em python, e também nos permitirá começar a pensar no design do programa.







-DEF
	Vamos ver como construir a sintaxe de uma função em python. Ela tem a seguinte forma:
Def name_of_function(arg1,arg2):
‘’’
A documentação da função ficará aqui
 ‘’’
# faça coisas aqui
Return # retorne o resultado desejado aqui

	Começamos com def, seguido do nome da função. Tente manter os nomes relevantes , por exemplo len() é um bom nome para uma função lenght. Também tenha  cuidado com os nomes , você não gostaria de chamar uma função do mesmo nome que uma função interna em python (como len).
	Em seguida, vem um par de parênteses com vários argumentos separados por uma vírgula. Esses argumentos são as entradas para sua função. Você poderá usar essas entradas em sua função e fazer referencia a elas. Depois disso, você coloca dois pontos.
	Agora, aqui é o passo importante, você deve identar para começar o código dentro de sua função corretamente . python faz uso de espaço em branco para organizar o código. Muitas outras linguagens de programação não fazem isso, então tenha isso em mente.
	Em seguida, você verá o doc-string, é aqui que você escreve uma descrição básica da função. Documentações não são necessárias para funções simples, mas é uma boa prática colocá-las para que você ou outras pessoas possam facilmente entender o código que você escreve.
	Depois de tudo isso, você começa a escrever o código que deseja executar.
	A melhor maneira de aprender funções é através  de exemplos. Então, vamos tentar passar por exemplos que se relacionam com os vários objetos e estruturas de dados que aprendemos antes.

Def say_hello():
	Print(‘hello’)

Chame a função

Say_hello()
# na tela ira imprimir hello

	Vamos escrever uma função que cumprimenta pessoas com seu nome.

Def greeting(name):
	Print(‘hello, %s ‘ %nome)
Greeting (‘rodrigo’)
#na tela ira imprimir = hello, rodrigo

 - USANDO RETURN
	Vamos ver um exemplo que usa uma declaração de retorno. A instrução return permite que uma função retorne um resultado que pode ser armazenado em uma variável por exemplo, ou usado de qualquer outra maneira.
Def add_num(num1,num2):
	Return nun1 + nun2
add_num(4,5)

result = add_num(4,5)
	print(result) # ira imprimir 9

	O que acontece se inserirmos duas strings?

Print(add_num(‘one’,’two’))

	Note, porque não declaramos tipos de variáveis em python, esta função pode ser usada para adicionar números ou sequencias em conjunto.
	Finalmente, vamos passar por um exemplo complexo de criar uma função para verificar se um número é primo.
	Nós sabemos que um número é primo se esse número é apenas divisível em 1 e em si mesmo. Vamos escrever a nossa primeira versão da função para verificar todos os números de 1 a N e executar verificações de módulos.

def is_prime(num):
‘’’
   Método para checar se é primo
‘’’
 for n in range(2,num):
       if num % n == 0 :
              print(‘não é primo’)
              break
        else: # se o modulo nunca for zero, é primo
              print(‘primo’)
is_prime(16)
#na tela ira imprimir = não é primo

	Observe como quebramos o código após a declaração de impressão !! na verdade, podemos melhorar isso ao verificar somente a raiz quadrada do numero-alvo, também podemos ignorar todos os números pares depois de verificar 2. Também mudaremos para retornar um valor booleano para obter um exemplo de usar declarações de retorno:
Import math
def is_prime(num):
‘’’
   Melhor método para checar primos
‘’’
If num % 2 == 0 and num > 2:
    Return false
for i in range (3, int(math.sqrt(num)) + 1, 2):
     if num % i == 0:
        return false
return true
is_prime(11)
	ótimo!! Você deve agora ter uma compreensão básica sobre como criar suas próprias funções para salvar-se de escrever repetidamente o código !!

exercícios 
1 – crie uma função que retire o domínio de um email. Por exemplo, passando como parâmetro “user@domain.com” retornaria: “domain.com”.
#exemplo:
Print(obterDominio(‘myemail@mydomain.com’))

2 – escreva uma função que calcula o volume de uma esfera dado seu raio. A fórmula é V=4/3πr^3 
Obs: sinta a vontade para usar pi como 3,1416. Porem se você quiser mais precisão, importe a biblioteca math, e use pi como math.pi
Import math
Math.pi
3,141592653589793
#exemplo:
Volume(2)
33.510321638291124
