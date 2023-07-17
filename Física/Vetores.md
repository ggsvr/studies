# Definição
Objeto matemático representado por um segmento de reta orientado, ou magnitude e direção.

## Magnitude / Módulo
É o escalar que indica o comprimento da seta e é sempre positivo.
Ex: $1, 2.5, 8$

## Direção
Determinada pela reta suporta do segmento de reta.
Ex: horizontal, vertical, diagonal.

## Sentido
Orientação do segmento de reta, ou pra onde aponta.
Ex: para baixo, para a direita, para cima.

# Propriedades
- Um vetor pode ser deslocado no espaço, desde que mantenha seu módulo, direção e sentido.

- Ao invertermos o sentido de um vetor, invertemos também o seu sinal.

- Dois vetores são _equipolentes_ quando têm o **mesmo módulo, mesma direção e o mesmo sentido**.

- Se os vetores tiverem a **mesma direção e o mesmo módulo, mas sentidos opostos**, os vetores são _simétricos_ ou _opostos_.

- Quando tiverem **somente a mesma direção** (mesma reta ou em retas paralelas), os vetores são chamados _colineares_.

- Se tiverem as **direções diferentes**, são chamados de _concorrentes_.

# Operações

## Soma
Visualmente, corresponde a colocar o começo de um vetor na ponta do outro.

### Regra do paralelogramo
Juntando as origens dos dois vetores, trace uma reta paralela a cada vetor. O vetor resultante terá a mesma origem dos vetores e sua ponta será o cruzamento das linhas paralelas.

Sendo $\theta$ o ângulo formado entre os vetores, calculamos o módulo do vetor soma através da expressão:
$\|\vec{V_R}\| = \sqrt{\|\vec{V_1}\|^2 + \|\vec{V_2}\|^2 + 2 \times \|\vec{V_1}\| \times \|\vec{V_2}\| \times \cos{\theta}}$

![[regra do paralelogramo.png]]

### Casos especiais
#### $\theta = 0\degree$
Se o ângulo $\theta$, entre os vetores, mede $0\degree$, os vetores possuem a mesma direção e sentido. Nesse caso, o vetor resultante é dado pela soma dos módulos dos vetores $\vec{V_1}$ e $\vec{V_2}$.
$\|\vec{V_R}\| = \|\vec{V_1}\| + \|\vec{V_2}\|$

#### $\theta = 90\degree$
Nesse caso, os vetores são perpendiculares entre si. O módulo do vetor resultante é obtido através da aplicação do teorema de Pitágoras.
$\|\vec{V_R}\| = \sqrt{\|\vec{V_1}\|^2 + \|\vec{V_2}\|^2}$

#### $\theta = 180\degree$
Os vetores possuem a mesma direção, mas sentidos contrários. Nesse caso, o módulo do vetor soma é dado pelo módulo da diferença entre os módulos dos vetores $\vec{V_1}$ e $\vec{V_2}$.
$\|\vec{V_R}\| = |\,\|\vec{V_1}\| - \|\vec{V_2}\|\,|$

## Subtração
Na subtração vetorial, é feita uma soma, mas invertendo um dos vetores.

## Multiplicação por escalar
Seja $\alpha$ um número real não nulo e $\vec{V}$ um vetor também não nulo, o produto $\alpha\vec{V}$ tem como resultado um vetor $\vec{u}$, sempre com a mesma direção de $\vec{V}$ e módulo $u = |\alpha| \|\vec{V}\|$. O sentido do vetor $\vec{u}$ é determinado pelo sinal de $\alpha$.

![[multiplicacao vetor.png]]

## Decomposição vetorial
Um vetor pode ser escrito como a soma de dois ou mais vetores quaisquer. Em algumas situações, podemos decompor um vetor em seus componentes $x$ e $y$, traçando retas imaginárias paralelas aos eixos. Podemos calcular o valor de $V_x$ e $V_y$ usando trigonometria básica.
$V_x = \|\vec{V}\| \cos \theta$
$V_y = \|\vec{V}\| \sin \theta$

![[Decomposicao vetorial.png]]

## Produto Escalar
É uma operação que representa o quanto dois vetores apontam na mesma direção. Leva em conta a magnitude dos vetores e o ângulo entre eles.
$\vec{a} \cdot \vec{b} = \|\vec{a}\| \|\vec{b}\| \cos \theta$
Também é possível calcular o produto escalar a partir dos componentes dos vetores.
$\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y$
