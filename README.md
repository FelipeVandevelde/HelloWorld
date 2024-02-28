# HelloWorld

Aprendendo a utilização de **marcação** dentro do _Markdown_.
Assim como o HTML o Markdown é uma linguagem de marcação, criada com o objetivo de simplificar sua leitura, já que a mesma não é baseada em código como o HTML.

Para utilizarmos o **negrito** temos **duas** opções, a primeira é utilizando pares de asterisco(\*) no começo e no final do texto que quer colocar em **negrito**, outro modo de fazer isso é utilizando pares de sublinhas(\_) no começo e no final do texto que deseja ficar em **negrito**.

Para utilizarmos o _italico_ temos _duas_ opções, a primeira é utilizando apenas um asterisco(\*) no começo e um no final do texto que quer colocar em *italico*, outro modo de fazer isso é utilizando uma sublinhas(\_) no começo e no final do texto que deseja ficar em _italico_.

Temos a opção também de ~~riscar~~ o texto, para utilizar essa função se é utilizado pares de til(~) no começo e no final do texto que deseja ficar ~~riscado~~.

Com esse conhecimento previo temos a noção de cada um porém ainda não sabemos se há a possíbilidade de colocar um texto **negrito** em _italico_, a resposta é que sim, podemos _**misturar**_ marcações de forma simples, segue outras opções: _~~**mistura**~~_; ~~**mistura**~~; ~~**mistura**~~

Temos a opção de adicionar separadores, esses são linhas horizontais que podem ser utilizados para uma divisão visual do texto, pode ser feito com três traços(-) ou com três asterisco(\*)

Linha traço:

---

## Cuidado, o texto acima da linha criada por traços se torna um título de nível 2 e a linha fica se parecendo mais com um sublinhado

Linha asterisco:

---

Agora adentrando as marcações de título temos a hashtag(#) para informar que estamos colocar um título, é nescessário que o texto tenha um espaço da hashtag para funcionar:

# Título de nível 1 se utiliza uma hashtag!

## Título de nível 2 se utiliza duas hashtag!

### Título de nível 3 se utiliza três hashtag!

Podemos também criar uma lista numerada, não precisamos colocar as numerações de forma correta pois o próprio códgio consegue fazer a listagem numerica para nós, após colocarmos um número qualquer devemos dar um espaço após o ponto(.), com três espaços normais um tópico da lista numerada se torna um subtópico sendo listado com números romanos, segue lista:

0. Primeiro item
   1. Primeiro sub-item
   1. Segundo sub-item
   1. Terceiro sub-item
0. Segundo item
0. Terceiro item

Outra lista que temos a possibilidade de criar é a lista demarcada, para utilizar ela colocamos um asterisco e um espaço antes do item, para criar um sub-item adicionamos três espaços, segue lista:

* Primeiro item
   * Primeiro sub-item
   * Segundo sub-item
   * Terceiro sub-item
* Segundo item
* Terceiro item

Ou também podemos utlizar uma lista demarcada trocando asterisco por traço:

- Primeiro item
   - Primeiro sub-item
   - Segundo sub-item
   - Terceiro sub-item
- Segundo item
- Terceiro item

Ainda falando sobre listas temos a possibilidade de criar uma lista de tarefas, primeiro devemos colocar um til(~) e dar um espaço, terminando isso vamos abrir e fechar chaves, para as tarefas não concluídas devemos deixar apenas um espaço dentro das chaves, para tarefas concluídas devemos colocar um X, segue um exemplo:

- [X] Estudar git e github
- [X] Criar uma conta
- [X] Criar e modelar um repositório
- [ ] Terminar faculdade
- [ ] Se tornar um programador muito dahora

Para o uso de imagem o recomentado é utilizar imagens pequenas, sendo o ideal imagens com larguras no maximo 400px a 500px, para colocar uma imagem é preciso primeiro colocar exclamação(!), depois abrir e fechar colchete com o nome da imagem e por fim abre e fecha parênteses com o link da imagem.

![Imagem em 512px](https://github.com/FelipeVandevelde/HelloWorld/assets/148922578/0b0387ce-a337-4927-899d-faf35810b261)
Imagem de 512px

![Imagem em 400px](https://github.com/FelipeVandevelde/HelloWorld/assets/148922578/b681a721-df96-48f4-bdf7-5425866ced11)
Imagem de 400px

![Imagem em 200px](https://github.com/FelipeVandevelde/HelloWorld/assets/148922578/387bf453-1562-4185-af7d-96ebe0d4eb71)
Imagem de 200px

![Imagem em 100px](https://github.com/FelipeVandevelde/HelloWorld/assets/148922578/1570e651-47c0-44bd-99b1-536622b3d8a0)
Imagem de 100px

O uso de hyperlink é semelhante ao uso de imagem, sendo sua unica diferença a exclamação no começo.
[Acesse meu perfil no linkedin](https://www.linkedin.com/in/felipe-vandevelde-a54a81266/)

Vamos rever a utilização de tabelas, na linguagem Markdown a marcação das tabelas funciona da seguinte forma:
colunas divididas por uma barra vertical (|), para identificar que a linha 
Coluna1|Coluna2|Coluna3
//----|----|----
Valor1|Valor2|Valor3
Valor1|Valor2|Valor3

