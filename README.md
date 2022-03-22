<h1>Chute um número</h1>


Write a program that when starting generates a random value from 1 to 10 and allows the user to kick a number until the random value generated at the beginning of the program is kicked correctly.

The program must inform whether the kick was above, below or equal to the random value generated at the beginning of the program.

# # # 5Q ́s method to mount an algorithm:

Critically analyze the problem and find out:
(Try to explain this problem to yourself aloud and ask for more information/investigate further until you fully understand the problem.)

1. What is the required input data?
- Random value from 1 to 10
- User kick
2. What should I do with this data?
- I must compare the user's kick with the random value that was generated at the beginning of the program and tell if the kick was higher, less than or equal to the value that was generated at the beginning of the program.
3. What are the restrictions of this problem?
- A random value from 1 to 10
4. What is the expected result?
- The expected result is that the program should inform if the kick was above, below or equal to the random value generated at the beginning of the program.
5. What is the sequence of steps to be made to reach the expected result?
input valor_aleatorio
kick input
if kick > valor_aleatorio:
  print'Chute was greater than the value generated'
if kick < valor_aleatorio:
  print'Chute was less than the generated value'
if kick = valor_aleatorio:
  print'You got it right!'


<h2>Traduzido em português</h2>

Escreva um programa que, ao iniciar gera um valor aleatório de 1 a 10 e permite que o usuário chute um número até que o valor aleatório gerado no ínicio do programa seja chutado corretamente.

O programa deve informar se o chute foi acima, abaixo ou igual ao valor aleatório gerado no ínicio do programa.

# # Método 5Q´s para montar um algorítimo:

Analise críticamente o problema e descubra:
(tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você compreender completamente o problema.)

1. Quais são os dados de entrada necessários?
- Valor aleatório de 1 a 10
- Chute do usuário
2. O que devo fazer com estes dados?
- Eu devo comparar o chute do usuário com o valor aleatório que foi gerado no ínicio do programa e dizer se o chute foi maior, menor ou igual ao valor que foi gerado no ínicio do programa.
3. Quais são as restrições deste problema?
- Um valor aleatório de 1 a 10
4. Qual é o resultado esperado?
- O resultado esperado é que o programa deve informar se o chute foi acima, abaixo ou igual ao valor aleatório gerado no ínicio do programa.
5. Qual é a sequencia de passos a ser feitas para chegar ao resultado esperado?
input valor_aleatorio
input chute
if chute > valor_aleatorio:
  print'Chute foi maior que o valor gerado'
if chute < valor_aleatorio:
  print'Chute foi menor que o valor gerado'
if chute = valor_aleatorio:
  print'Você acertou!'
