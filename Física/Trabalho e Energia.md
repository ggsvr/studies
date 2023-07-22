
# Trabalho
### Símbolo: $\tau$
### [[Unidades#Joule|Unidade]]: $J$
É a grandeza relacionada à transferência de energia devido a atuação de uma força. Trabalho é realizado quando uma força é aplicada em um corpo e esse sofre um deslocamento.

## Trabalho De Uma Força

### Força Constante
Quando uma [[Dinâmica#Força|força]] constante atua em um corpo, produzindo deslocamento, o trabalho é calculado a partir da seguinte fórmula:

#### $\tau = F \times \Delta S \times \cos \alpha$
$F =$ módulo de uma força
$\Delta S =$ [[Cinemática#Deslocamento|deslocamento]]
$\alpha =$ ângulo entre a direção da força e do deslocamento

- Trabalho positivo: $0\degree \leq \alpha < 90\degree \implies$ força **motora**
- Trabalho nulo: $90\degree$
- Trabalho negativo: $90\degree < \alpha \leq 180\degree \implies$ força **resistente**

### Força Variável
Quando a força não é constante, é possível calculá-la através da área do gráfico $F(\Delta S)$:
![[grafico-forca-deslocamento.png]]

### Força Peso
A força peso é calculada por $P = m \times \vec{g}$. Desta forma, podemos calcular o trabalho da força peso:
### $\tau = m \times g \times h$
$m =$ massa do corpo
$g =$ aceleração da gravidade
$h =$ altura do deslocamento

O trabalho da força peso é **independente da trajetória**.


# Potência
### Símbolo: $Pot$
### [[Unidades#Watt|Unidade]]: $W$
Potência é a medida do quão rápido uma tarefa é realizada. Relaciona a quantidade de energia que é consumida/fornecida e o tempo utilizado.

## Potência média
Definimos potência média relacionando o trabalho com o tempo gasto para realizá-lo:
### $Pot_{média} = \dfrac{\tau}{\Delta t}$
Também podemos definir a potência como uma função da velocidade:
### $Pot_{média} = F \times V_{média} \times \cos \alpha$


# Energia
### Símbolo: $E$
### [[Unidades#Joule|Unidade]]: $J$
É a capacidade de produzir trabalho. Um corpo so é capaz de realizar um trabalho se possuir energia.

## Energia Cinética
### Símbolo: $E_c$
Energia cinética é um tipo de energia que está relacionada com o **movimento dos corpos**. É calculada a partir da seguinte fórmula:
"move meio quadrado"
### $E_c = \dfrac{mv^2}{2}$

## Energia Potencial
É o tipo de energia que fica acumulada no corpo, esperando para ser utilizada.

### Energia Potencial Gravitacional
#### Símbolo: $E_{pg}$
Energia Potencial gerada por um campo gravitacional. é proporcional à massa, aceleração gravitacional e altura em relação à um nível de referência.
#### $E_{pg} = m \times g \times h$
$m =$ massa
$g =$ campo gravitacional
$h =$ altura

### Energia Potencial Elástica
#### Símbolo: $E_{pel}$
Energia potencial armazenada como resultado da força aplicada para deformar um objeto elástico. A energia é armazenada até que a força seja removida e o objeto volte ao seu estado original. Pode envolver compressão, tensão ou torção.
#### $E_{pel} = \dfrac{k \times \Delta S^2}{2}$
$k =$ constante elástica
$\Delta S =$ deslocamento

$k = 20$
$\Delta S^2 = 0.25$
$E_{pel} = 2.5J$

## Energia Mecânica
### Símbolo: $E_m$
Energia mecânica é aquela que acontece devido ao movimento dos corpos ou armazenada nos sistemas físicos. É a **soma da energia cinética e energia potencial**.
### $E_m = E_c + E_{pg} + E_{pel}$

### Princípio da Conservação da Energia Mecânica
Em um sistema isolado constituído por corpos que interagem apenas com forças conservativas, a **energia mecânica total permanece constante**.
#### $E_{m_0} = E_{m_F}$


$\dfrac{mv^2}{2} = 20 - 7.5$
$v = 5m/s$

# Impulso e Quantidade de Movimento
### Símbolo do impulso: $\vec{I}$
### Símbolo da quantidade de movimento: $\vec{Q}$

## Impulso de uma Força Constante
### $\vec{I} = \vec{F} \times \Delta t$

## Quantidade de Movimento de uma Partícula
![[impulso-quantidade-movimento.png]]

## Teorema do Impulso
O impulso da força resultante que age em um corpo num dado intervalo de tempo é igual a variação da quantidade de movimento desse corpo no intervalo de tempo considerado.
### $\vec{I} = \Delta\vec{Q} \implies m\vec{V} - m\vec{V}_0$


## Teorema da Conservação da Quantidade de Movimento
Se a resultante das forças externas que atuam no sistema for nula, a quantidade de movimento é conservada. Ou seja, em um sistema isolado, a quantidade de movimento é constante.
### $\vec{Q}_0 = \vec{Q}_F$

## Choques Mecânicos
Quando dois corpos colidem um contra o outro, pode acontecer deles "quicarem". Esse fenômeno depende do **coeficiente de restituição $e$**.
### $e = \frac{\text{velocidade relativa de afastamento}}{\text{velocidade relativa de aproximação}}$

|Choque|Energia Cinética|Qtd. Movimento|Coef. de Restituição|
|------|----------------|--------------|--------------------|
|Perfeitamente Elástico|$E_{c_0} = E_{c_F}$|$\vec{Q}_0=\vec{Q}_F$|$e=1$|
|Parcialmente Elástico|$E_{c_0} > E_{c_F}$|$\vec{Q}_0=\vec{Q}_F$|$0 < e < 1$|
|Perfeitamente Inelástico|$E_{c_0} > E_{c_F}$|$\vec{Q}_0=\vec{Q}_F$|$e=0$|
