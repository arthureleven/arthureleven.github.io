---
title: "Fundamentos da Matemática em Português"
pubDate: "May 24 2025"
---

![](/blog/book.png)

Desde os primeiros tempos, a Matemática tem sido uma ferramenta importante para entender o mundo como um todo. Com ela, conseguimos criar modelos, entender padrões da natureza e até dos grupos sociais. A Matemática funciona como uma linguagem formal que traduz a realidade em estruturas lógicas, ajudando a descrever desde pequenas mudanças em objetos até grandes conjuntos de dados complexos.

No entanto, é comum pensar que a Matemática é apenas a "ciência dos números". Embora ela use números, seu foco principal está nas relações entre estruturas abstratas. Pensar a Matemática só como estudo dos números é um erro, porque o que realmente importa são as formas como essas estruturas se organizam e se relacionam, não os números em si.

Euler, um grande matemático, já tinha essa ideia ao dizer:

> WHATEVER is capable of increase or diminution, is called magnitude, or quantity.  
> [...] Mathematics, in general, is the science of quantity; or, the science which investigates the means of measuring quantity.[^1]

Essa visão está intrinsecamente relacionada à ideia de que o significado dos números emana do contexto estrutural no qual estão inseridos. Em outras palavras, é a estrutura que confere sentido ao número - e não o contrário.

$$
\LARGE \text{O que é um número?}
$$
Euler aplicava sua concepção de número ao expor os fundamentos da Matemática de forma clara e filosófica:

> [...] This proportion is always expressed by numbers; so that a number is nothing but the proportion of one magnitude to another arbitrarily assumed as the unit.[^1]

Um número pode ser compreendido como tudo aquilo que quantifica uma grandeza-alvo. Ou seja, qualquer entidade que possa ser submetida a uma medida - seja ela discreta, contínua, racional, ou mesmo imaginária - pode ser representada numericamente. Em contrapartida, entidades como o infinito não se qualificam como números, uma vez que não se prestam à quantificação convencional. O infinito pertence ao domínio das ideias-limite, e não ao conjunto de entidades numericamente manipuláveis.

No universo matemático, os números são organizados em conjuntos estruturados, cada qual dotado de propriedades e axiomas próprios, que permitem classificá-los conforme suas naturezas e operações internas.

$$
\Large \text{Conjunto Natural}\ \mathbb{N}
$$
O conjunto dos números naturais é composto por todos os inteiros não-negativos, isto é:
$$
\mathbb{N} = \{0, 1, 2, 3, 4, \dots\}
$$

O comportamento estrutural de $\mathbb{N}$ é descrito pelos Axiomas de Peano, que estabelecem as bases formais para a construção dos naturais:
1. Existe um número natural denominado zero.
2. Todo número natural $n$ possui um sucessor $S(n) \in \mathbb{N}$, definido por $S(n) = n + 1$.
3. Se $S(a) = S(b)$, então $a = b$ (a função sucessor é injetiva).
4. Não existe nenhum $n \in \mathbb{N}$ tal que $S(n) = 0$; isto é, o zero não é sucessor de nenhum número natural.
	- A operação inversa do sucessor é o antecessor, definida por $A(n) = n - 1$. Entretanto, $A(0) = 0 - 1 = -1, -1 \notin \mathbb{N}$, violando o domínio do conjunto.
5. Se um subconjunto de $\mathbb{N}$ contém o elemento 0 e é fechado sob a operação de sucessão, então ele contém necessariamente todos os números naturais.

$$
\Large \text{Conjunto Inteiro}\ \mathbb{Z}
$$
O conjunto $\mathbb{Z}$ consiste em todos os números inteiros positivos, negativos e o zero:
$$
\mathbb{Z} = \{-2, -1, 0, 1, 2, \dots\}
$$

Trata-se de uma extensão de $\mathbb{N}$ que incorpora a operação de subtração. Estruturalmente, $\mathbb{Z}$ forma um anel comutativo unitário, obedecendo aos seguintes axiomas:
1. Sejam $a, b \in \mathbb{Z}$, então $a + b \in \mathbb{Z}$ e $a \cdot b \in \mathbb{Z}$.
2. Distributividade: $a \cdot (b + c) = a \cdot b + a \cdot c$.
3. Comutatividade: $a \cdot b = b \cdot a, a + b = b + a$.
4. Associatividade: $a + (b + c) = b + (a + c), (a \cdot b) \cdot c = (b \cdot c) \cdot a$.
5. O número 0 é o neutro da adição, e 1 é o neutro da multiplicação: $a + 0 = a, a \cdot 1 = a$.
6. Para todo $a \in \mathbb{Z}$, existe $-a \in \mathbb{Z}$ tal que $a + (-a) = 0$.

$$
\Large  \text{Conjunto Racional}\ \mathbb{Q}
$$

O conjunto dos racionais é composto por todos os números que podem ser expressos como razão entre dois inteiros, com denominador diferente de zero:
$$
\mathbb{Q} = \{\frac{a}{b}\ \mid a \in \mathbb{Z}, b \in \mathbb{Z}, b \neq 0\}
$$

Trata-se de uma ampliação de $\mathbb{Z}$, ao incluir a operação de divisão (exceto por zero). O conjunto $\mathbb{Q}$ forma um corpo comutativo, pois satisfaz todos os axiomas de um anel comutativo e, adicionalmente, admite inverso multiplicativo:
- Para todo $a \in \mathbb{Q}, a \neq 0$, existe um elemento  $a^{-1} \in \mathbb{Q}$ tal que:
$$a \cdot a^{-1} = 1$$
A relação com potências negativas reforça esta propriedade:
$$a^{-1} = \frac{1}{a^{n}} \Rightarrow a \cdot \frac{1}{a} = \frac{a}{a} = 1$$
Esse conjunto é denso na reta real, e nele todo número racional pode ser representado por infinitas frações equivalentes.

$$
\Large \text{Conjunto Irracional}\ \mathbb{I}
$$
O conjunto dos irracionais é formado por todos os números reais que não podem ser escritos como fração de dois inteiros, ou seja, não pertencem ao conjunto dos racionais:  
$$
\mathbb{I} \in \mathbb{R}, \mathbb{I} \notin \mathbb{Q}
$$

Esses números possuem representação decimal infinita e não periódica, o que os diferencia dos racionais, cujas representações decimais são finitas ou periódicas. Um bom exemplo é o número $\pi$ e a raiz $\sqrt{2}$.

Os irracionais não admitem representação exata por fração, embora possam ser aproximados por racionais. Apesar disso, eles também são densos na reta real, assim como os racionais, o que significa que entre dois números reais quaisquer, sempre existe um irracional.

Os conjuntos $\mathbb{Q}$ e $\mathbb{I}$ são disjuntos, mas juntos formam o conjunto dos reais:
$$
\mathbb{R} = \mathbb{Q} \cup \mathbb{I}
$$

$$
\Large \text{Conjunto Real}\ \mathbb{R}
$$
O conjunto dos números reais, representado por $\mathbb{R}$, é formado pela união dos números racionais e irracionais:
$$
\mathbb{R} = \mathbb{Q} \cup \mathbb{I}
$$

Esse conjunto abrange todos os números que podem ser representados em uma reta contínua, sem lacunas, o que justifica o nome "reta real". Ele é a base para grande parte da matemática, especialmente na análise, geometria e aplicações em ciências naturais e engenharias.

---

$$
\LARGE \text{Operações entre Conjuntos}
$$
As operações entre conjuntos formam a base da linguagem da Teoria dos Conjuntos, permitindo descrever como coleções de elementos se relacionam e se combinam. Assim como as operações aritméticas lidam com números, as operações entre conjuntos lidam com elementos e pertencimento. Elas envolvem ações como unir elementos, identificar o que há em comum, remover elementos de um conjunto em relação a outro, e observar o que está fora de um conjunto dentro de um universo maior. Essas operações são essenciais para organizar informações, resolver problemas lógicos e construir estruturas mais complexas na matemática, como funções, relações e probabilidades.

Levaremos em conta as variáveis $A = \{1, 2, 3\}, B = \{3, 4, 5, 6\}$ para os exemplos.

$$
\Large \text{União}
$$
A união de dois conjuntos A e B é o conjunto que contém todos os elementos que estão em A, em B, ou em ambos:

$$
A \cup B = \{1, 2, 3, 4, 5, 6\}
$$

$$
\Large \text{Interseção}
$$
A interseção de dois conjuntos A e B é o conjunto de elementos que estão tanto em A quanto em B:

$$
A \cap B = \{3\}
$$

$$
\Large \text{Diferença}
$$
A diferença entre dois conjuntos A e B é o conjunto dos elementos que estão em A, mas não estão em B:

$$
A - B = \{1, 2\}
$$

$$
\Large \text{Complemento}
$$
O complementar de um conjunto A, dentro de um conjunto universo U, é o conjunto de todos os elementos de U que não estão em A:

Se $U = \{1, 2, 3, 4, 5\}$ então:
$$
\bar{A} = \{4, 5\} \ \text{ou} \newline
A^{\complement} = \{4, 5\}
$$

$$
\Large \text{Diferença Simétrica}
$$
A diferença simétrica entre A e B é o conjunto dos elementos que estão em A ou em B, mas não em ambos.

$$
A \bigtriangleup B = \{1, 2, 4, 5\}
$$

---

$$
\LARGE \text{Proposições}
$$
A linguagem matemática se baseia em proposições - sentenças que afirmam algo que pode ser verdadeiro ou falso, mas nunca ambos ao mesmo tempo. Elas são a base da lógica matemática, que estuda o raciocínio formal e a validade dos argumentos.

- $\text{"2 é um número par."} \Rightarrow V$
- $\text{"3 é um número par."} \Rightarrow F$
- $\text{"−3 pertence ao conjunto dos inteiros."} \Rightarrow V$

$$
\Large \text{Tipos de Proposições}
$$
As proposições podem ser classificadas em:

1. Proposições simples: expressam uma única sentença com valor lógico definido.  
    - $\text{"7 é ímpar."}$
2. Proposições compostas: formadas por duas ou mais proposições simples conectadas por conectivos lógicos. 
    - $\text{"7 é ímpar e maior que 5."}$

$$
\Large \text{Conectivos Lógicos}
$$

|Conectivo|Símbolo|Leitura|Exemplo
|---|---|---|---|
|Negação|$\neg$|"não"|$\neg{P}$: "Não é verdade que P"|
|Conjunção|$\wedge$|"e"|$P \wedge Q$: "P e Q"|
|Disjunção|$\vee$|"ou"|$P \vee Q$: "P ou Q"|
|Condicional|$\rightarrow$|"se... então..."|$P \rightarrow Q$: "Se P, então Q"|
|Bicondicional|$\leftrightarrow$|"se e somente se"|$P \leftrightarrow Q$: "P se e somente se Q"|

$$
\Large \text{Classificação das Proposições}
$$

1. Tautologia: proposição sempre verdadeira, independentemente dos valores lógicos das sentenças envolvidas.
    - $P \vee \neg{P}$
2. Contradição: proposição sempre falsa.  
    - $P \wedge \neg{P}$
3. Contingência: proposição que pode ser verdadeira ou falsa, dependendo dos valores lógicos das proposições que a compõem. 
	- $P \rightarrow Q$

$$
\Large \text{Regras Lógicas}
$$
As proposições compostas podem ser formadas por diferentes conectivos lógicos, como conjunção, disjunção, condicional e bicondicional. Entender como negar essas proposições é fundamental na lógica proposicional, e as Leis de Morgan desempenham papel essencial nesse processo, especialmente para negação de conjunções e disjunções.

$$
\large \text{Negando a conjunção}
$$
Ao afirmar "P é X e Q é Y", estamos dizendo que ambos os eventos ocorreram ao mesmo tempo. Isso é uma conjunção – ela só é verdadeira quando as duas partes são verdadeiras. Ao negar essa proposição, dizemos que pelo menos um dos dois eventos não aconteceu. A forma lógica da negação é:

$$
\neg{(P \wedge Q)} = (\neg{P}) \vee (\neg{Q})
$$

Por exemplo: "Ana fez a lição de matemática e arrumou o quarto.". Isso quer dizer que ela fez as duas coisas, mas ao negarmos: "Ana não fez a lição de matemática ou não arrumou o quarto.", aqui, a negação indica que pelo menos uma dessas tarefas não foi feita - talvez ela não tenha feito nenhuma, ou apenas uma delas.

|$P$|$Q$|$P \wedge Q$|$\neg (P \wedge Q)$|
|---|---|---|---|
|V|V|V|F|
|V|F|F|V|
|F|V|F|V|
|F|F|F|V|

$$
\large \text{Negando a disjunção}
$$
Ao afirmar "P ou Q", estamos dizendo que pelo menos uma das duas possibilidades pode acontecer. Isso é chamado de disjunção inclusiva - basta que uma delas seja verdadeira para a frase toda ser verdadeira. Quando negamos essa afirmação, estamos dizendo que nenhuma das duas possibilidades pode ocorrer. Ou seja, tanto P quanto Q são falsos. A negação é representada por:

$$
\neg{(P \vee Q)} = \neg{P} \wedge \neg{Q}
$$

Por exemplo: "Ana vai comer sorvete ou vai comer bolo.", ao negarmos: "Ana não vai comer sorvete e não vai comer bolo.". Ou seja, a negação diz que nenhuma das opções será escolhida - Ana não vai comer nem sorvete nem bolo.

|$P$|$Q$|$P \vee Q$|$\neg{(P \vee Q)}$|
|---|---|---|---|
|V|V|V|F|
|V|F|V|F|
|F|V|V|F|
|F|F|F|V|

$$
\large \text{Negando a condicional}
$$
A condicional $P \rightarrow Q$ significa "Se P, então Q". A negação dessa proposição não segue as Leis de Morgan, mas tem sua própria regra:

$$
\neg{(P \rightarrow Q)} = A \wedge \neg{B}
$$

É comum pensar que a negação de uma condicional seja $\neg{(P \rightarrow Q)} = \neg{P} \rightarrow \neg{Q}$ mas isso, na verdade, representa a contrapositiva, que é logicamente equivalente à própria condicional. Ou seja: $\neg{P} \rightarrow \neg{Q} = P \rightarrow Q$ é logicamente equivalente a $P \rightarrow Q$, e não à sua negação.

Negar uma proposição condicional do tipo "Se P, então Q" significa afirmar que a condição P aconteceu, mas a consequência Q não se realizou. Isso ocorre porque a condicional só é considerada falsa quando a primeira parte (P) é verdadeira e a segunda (Q) é falsa. Em todos os outros casos (quando P é falsa ou Q é verdadeira), a condicional continua sendo verdadeira. Portanto, ao negar uma condicional, estamos identificando exatamente o único caso em que ela não é válida: quando P de fato ocorre, mas Q não acontece. Assim, a negação de $P \rightarrow Q$ é $P \wedge Q$. Por exemplo: "Se estiver chovendo, então levarei um guarda-chuva.", ao negarmos: "Está chovendo e eu não levei um guarda-chuva.".

|$P$|$Q$|$P \rightarrow Q$|$\neg{(P \rightarrow Q)}$|
|---|---|---|---|
|V|V|V|F|
|V|F|F|V|
|F|V|V|F|
|F|F|V|F|

$$
\large \text{Negando a bicondicional}
$$
A bicondicional $P \leftrightarrow Q$ afirma que P e Q são logicamente equivalentes (ambos verdadeiros ou ambos falsos). Agora, quando negamos a bicondicional, queremos exatamente o oposto: queremos afirmar que P e Q têm valores diferentes. A negação:

$$
\neg{(P \leftrightarrow Q)} = (P \wedge \neg{Q}) \vee (\neg{P} \wedge Q)
$$

diz que ou P é verdadeiro e Q é falso, ou P é falso e Q é verdadeiro. Ou seja, a negação da bicondicional afirma que os valores lógicos de P e Q não coincidem - um é verdadeiro e o outro é falso. Por exemplo: "A lâmpada está acesa se e somente se o interruptor está ligado.", ao negarmos: "Ou a lâmpada está acesa e o interruptor não está ligado, ou a lâmpada está apagada e o interruptor está ligado.".

|$P$|$Q$|$P \leftrightarrow Q$|$\neg{(P \leftrightarrow Q)}$|
|---|---|---|---|
|V|V|V|F|
|V|F|F|V|
|F|V|F|V|
|F|F|V|F|

Essa estrutura representa o "ou exclusivo", também conhecido como XOR, e pode ser escrita como:

$$
\neg{(P \leftrightarrow Q)} = P \oplus Q
$$

|$P$|$Q$|$P \vee Q$|$P \oplus Q$|
|---|---|---|---|
|V|V|V|F|
|V|F|V|V|
|F|V|V|V|
|F|F|F|F|

---

$$
\LARGE \text{Funções}
$$
[TODO]

$$
\LARGE \text{Álgebra}
$$
[TODO]

$$
\LARGE \text{Inequações}
$$
[TODO]

$$
\LARGE \text{Introdução à Geometria}
$$
[TODO]

$$
\LARGE \text{Introdução à Trigonometria}
$$
[TODO]

$$
\LARGE \text{Introdução à Estatística}
$$
[TODO]

[^1]: Euler, Leonhard. *Elements of Algebra*. Translated by Rev. John Hewlett, B.D. F.A.S. With an Introduction by C. Truesdell, 1840. Chapter I.