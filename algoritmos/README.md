## Projetos Algoritmos e Pensamento Computacional - C

### Calculadora científica

* **Funções matemáticas:**
    * **Básicas:** Soma, Subtração, Multiplicação e Divisão.
    * **Potências e Raízes:** Potência ($x^y$), Raiz Quadrada ($\sqrt{x}$) e Raiz Cúbica ($\sqrt[3]{x}$).
    * **Trigonometria:** Seno, Cosseno, Tangente (em graus), e suas versões Hiperbólicas.
    * **Matrizes:** Soma e Multiplicação de matrizes $2\times2$.
* **Outros recursos:**
    * **Histórico de Operações:** Utiliza uma struct para inserir a operação realizada no histórico e a função exibir_historico para mostrar as últimas operações.
    * **Tratamento de Erros:** Inclui verificações para divisão por zero, raiz quadrada de números negativos, logaritmos de valores $\le 0$, e valores inválidos para o cálculo de Fatorial.
    * **Arquitetura:** Foco no uso de funções que são chamadas na função principal: `main()`.

---

### Gerenciamento de alunos com struct

* **Estrutura de Dados:** Utiliza structs para organizar as informações.
* **Funcionalidade Principal:** Calcula a média e verifica se o aluno foi aprovado ou reprovado.
* **Manipulação de String:** Emprega `fgets` e `strcspn` para leitura segura do nome, incluindo espaços em branco.

---

### Insertion Sort

* **Conceito:** Algoritmo de ordenação que percorre as posições do array, onde cada nova posição precisa ser realocada no lugar correto à esquerda da posição maior. A ideia é semelhante a organizar cartas de baralho na mão.
* **Recursos Utilizados:** Desenvolvido com C, utilizando a biblioteca `<string.h>` e a função `strlen` para verificar o tamanho da string.
* **Implementação:** Utiliza laços **`for`** e **`while`** para percorrer o vetor e testar as condições de ordenação. A função `insertion_sort` é usada para ordenar os dígitos do RGM em formato crescente.

