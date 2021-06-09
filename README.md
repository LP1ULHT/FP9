**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Linguagens de Programação I - 2019/2020*

# Ficha de Exercícios - 9: Listas ligadas

Na resolução destes exercícios deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:

- O código apresentado deve ser bem indentado. 
- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:
- `gcc -Wall -Wextra -Wpedantic -std=c99 -g exercicio1.c -o exercicio1`
- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.
- Evite o uso de constantes mágicas. 
- Evite duplicação de código. 
- Considere a implementação de funções para melhorar a legibilidade, evitar a duplicação e criar soluções mais genéricas.

1.	Implemente um programa que dado um número (`n`) (lido do Teclado) aloque dinamicamente um vetor de (`n`) inteiros, usando o comando `malloc`. Peça ao utilizador os `n` números e calcule a média aritmética.

2.	Implemente um programa que solicita ao utilizador as notas dos alunos e aloque-as dinamicamente. No final devolva a nota maior e a menor. O utilizador terá de introduzir -1 para terminar de inserir notas.

3.	Implemente a função `myStrdup` que cria uma nova string exatamente igual à que lhe foi passada por parâmetro.

4.	Implemente uma estrutura clássica denominada Fila de Espera. Uma fila caracteriza-se por manter a regra “O primeiro a entrar é o primeiro a sair”, obedecendo assim a uma estratégia FIFO (First In- First Out).

     a.	A estrutura terá a idade e o nome de uma pessoa;
  
     b.	As primitivas a implementar são:
    
         i. Inic – Inicializa a fila;
        
         ii. Inserir – Coloca um novo elemento na fila;
        
         iii. Apagar – Retira da fila o primeiro elemento;
        
         iv. Listar – Mostra a fila.
    
     c.	Escreva um pequeno programa que teste a implementação da fila.

5. Crie um programa que pede o nome e idade de um numero indefinido de pessoas, os insere de forma ordenada numa lista ligada, e no final imprime a informação, libertando gradualmente a memoria alocada. Passos:
    * Deverá definir um tipo adequado para guardar, numa lista ligada, a informação de cada pessoa.
    * O programa deverá pedir ao utilizador para inserir o nome. Se inserir fim, termina a inserção. Senão, pede a idade, insere-o na lista, e volta a pedir um nome.
    * Cada nova pessoa deverá ser inserida de forma ordenada na lista, crescentemente de acordo com a idade.
    * Quando for inserida a palavra 'fim', deverá finalizar a inserção de elementos na lista.
    * De seguida deverá imprimir na consola a informação da lista, percorrendo-a do inicio ao fim, libertando gradualmente a memória alocada.
