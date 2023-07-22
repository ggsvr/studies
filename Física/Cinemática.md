# Conceitos

## Referencial
Estrutura idealizada na qual é possível realizar a observação de fenômenos físicos, bem como descrevê-los e formular suas leis, podendo esta estrutura ser descrita por um sistema de coordenadas.

![[referencial.png]]

## Posição
### Símbolo: $S$
Ponto do espaço onde se localiza o objeto a ser estudado. O valor da posição depende do referencial adotado.

## Deslocamento
### Símbolo: $\vec{\Delta S}$
É a mudança de posição no decorrer do tempo em relação a um dado referencial. Variação de posição. Grandeza vetorial.
$\vec{\Delta S} = S_F - S_0$

![[movimento.png]]

## Trajetória
Conjunto de [[#Posição|posições]] sucessivas ocupadas por um móvel no decorrer do tempo.

### Tipos de trajetória
- Reta
- Circular
- Elíptica
- Parabólica

### Distância Percorrida
#### Símbolo: $\Delta S$
#### [[Unidades#Metro|Unidade]]: $m$
Corresponde ao tamanho da [[#Trajetória]], ou percurso total efetuado pelo móvel.
$\Delta S = S_f - S_0$
![[distancia percorrida.png]]

### A trajetória de um corpo depende de seu referencial?
Para o avião, a trajetória do corpo é retilínea. Já para você, ela é curvilínea.

![[trajetoria relativa.png]]


## Velocidade
### Símbolo: $V$
### [[Unidades#m/s|Unidade]]: $m/s$

### Velocidade escalar média (rapidez média)
Razão entre a [[#Distância Percorrida]] e o tempo gasto.
$V_m = \dfrac{\Delta S}{\Delta t}$

### Velocidade vetorial média
Razão entre **deslocamento** realizado e o tempo gasto. Apresenta módulo, direção e sentido.
$\vec{V_m} = \frac{\vec{\Delta S}}{\Delta t}$

### Velocidade instantânea
Mede a velocidade em um instante específico.

### Velocidade resultante
É a [[Vetores#Soma|Soma]] das diversas velocidades que um corpo possui.
$\vec{V_R} = \vec{V_1} + \vec{V_2} + \vec{V_3} +\dots$ 

### IMPORTANTE
Considerar o tempo total do movimento, inclusive tempo em repouso.

### Exemplo
Uma rodovia é percorrida por um automóvel que passa pelo km 35, às $8h$, e pelo km 195, às $10h$. Sabe-se que, no km 120, o automóvel fica parado durante 10 minutos. Determine a **velocidade escalar média** desenvolvida no intervalo de tempo das $8h$ às $10h$.
$$
\begin{split}
\Delta S &= 195km - 35km \\
\Delta S &= 160km \\ \\
\Delta t &= 10h - 8h \\
\Delta t &= 2h \\ \\

V_m &= {160km \over 2h} \\
V_m &= 80km/h \\
\end{split}
$$

## Aceleração
### Símbolo: $\vec{a}$ / $\Delta V$
### [[Unidades#Aceleração|Unidade]]: $m/s^2$

### Aceleração Média
A aceleração média de um corpo é uma grandeza que reflete a variação de velocidade do corpo por intervalo de tempo. Sempre que houver variação no módulo, direção ou sentido do vetor velocidade, haverá aceleração no corpo.
### $a_m = \dfrac{\Delta V}{\Delta t} = \dfrac{V_F - V_0}{t_F - t_0}$

### Casos
#### $\vec{a} = 0$
A velocidade é constante em módulo, direção e sentido. O móvel percorre distâncias **iguais** em tempos iguais.

#### $\vec{a} > 0$
A velocidade aumenta, mas mantém constantes a direção e sentido. O móvel percorre distâncias que **aumentam** ao longo do tempo.

#### $\vec{a} < 0$
A velocidade diminui, mas mantém constantes a direção e sentido. O móvel percorre distâncias que **diminuem** ao longo do tempo.





# Movimento Retilíneo Uniforme (MRU)
O **Movimento Retilíneo Uniforme** é um movimento cuja [[#Velocidade]] permanece constante. Como consequência, o móvel percorre distâncias iguais em tempos iguais. No MRU a aceleração é nula.

## Função horária
"sorvete"
### $S_t = S_0 + V.t$
$S_t =$ posição no tempo $t$
$S_0 =$ posição inicial
$V =$ velocidade
$t =$ tempo

## Trajetória
A cada trajetória é associado um sentido positivo de percurso. O movimento efetuado nesse sentido se chama **progressivo** e tem sua velocidade **positiva**.

![[movimento-progressivo.png]]

O movimento no sentido contrário se chama **retrógrado** e tem sua velocidade **negativa**.

![[movimento-retrogrado.png]]

## Velocidade Relativa
É a velocidade que um móvel possui em relação a outro móvel usado como referencial.
$V_{rel} = V_a - V_b$

### Regra Prática
#### Móveis em sentidos opostos
$V_{rel} = |V_a| + |V_b|$
#### Móveis em sentidos iguais 
$V_{rel} = |V_a| - |V_b|$

### Movimento Uniforme Relativo
#### $V_{rel} = \dfrac{\Delta S_{rel}}{\Delta t}$

## Corpos Extensos
Quando as dimensões de um móvel não podem ser desprezadas, elas devem ser levadas em conta na distância a ser percorrida.

# Movimento Retilíneo Uniformemente Variado (MRUV)
É o movimento cuja velocidade do móvel varia de forma uniforme. Consequentemente, o móvel possui [[#Aceleração]] **não nula** e **constante**, percorrendo distâncias que aumentam ou diminuem ao longo do tempo.

## Propriedades
- Trajetória retilínea
- Velocidade varia de maneira constante
- Aceleração constante $\neq 0$
- Força resultante constante $\neq 0$
- A aceleração mede como a velocidade varia em cada instante de tempo.

## Função Horária da Velocidade
"vovoat"
### $V = V_0 + a.t$
$V =$ Velocidade final ou velocidade instantânea
$V_0 =$ Velocidade inicial
$a =$ Aceleração
$t =$ tempo

## Função Horária da Posição
"só votar meio quadrado"
### $S = S_0 + V_0\cdot t + \dfrac{at^2}{2}$
$S =$ Posição final
$S_0 =$ Posição inicial 
$V_0 =$ Velocidade inicial
$a =$ Aceleração
$t =$ tempo

## Equação de Torricelli
Usado quando não se tem a informação do tempo.
### $V^2 = V_0^2 + 2.a.\Delta S$

## Movimento de Queda Livre
É um movimento retilíneo uniformemente variado com [[#Aceleração]] = $g$. (na Terra, $g = 10m/s^2$)
- Na queda livre não existe resistência do ar. Todos os corpos caem da mesma forma e com a mesma aceleração.
- No movimento de queda livre, o tempo de subida é igual ao tempo de descida.
- Quando um corpo é lançado na vertical na superfície da Terra, para cima, sua [[#Velocidade]] vai diminuindo de $10m/s$ em $10m/s$, até alcançar o valor zero no ponto mais alto da trajetória.
- No ponto mais alto da trajetória, a aceleração é a da gravidade $g$.
- Mesmas funções do MRUV.

## Lançamento De Projéteis Em Um Campo Gravitacional

### Lançamento Horizontal
Quando um corpo é lançado horizontalmente no vácuo, ele descreve, em relação à terra, um arco de parábola. Esse movimento pode ser decomposto em dois movimentos mais simples: um na vertical ([[#Movimento Retilíneo Uniformemente Variado (MRUV)|MRUV]]) e outro na horizontal ([[#Movimento Retilíneo Uniforme (MRU)|MRU]]).

A [[#Velocidade]] total é a soma dos vetores velocidades dos movimentos horizontal e vertical.
$\vec{V} = \vec{V_x} + \vec{V_y}$, logo, $V^2 = V_x^2 + V_y^2$

#### Observações
- No lançamento **horizontal**, o alcance horizontal é proporcional à velocidade horizontal $V_x$, ou seja, quanto maior a velocidade horizontal, maior o alcance.
- O tempo de queda depende da altura $h$, mas **não** depende da velocidade horizontal $V_x$.

### Lançamento Oblíquo
Um lançamento oblíquo, é um movimento com um ângulo acima da horizontal, com uma trajetória parabólica. Sem considerar a resistência do ar, esse movimento pode ser decomposto em dois movimentos distintos: vertical (MRUV) e horizontal (MRU).

#### Decomposição Da Velocidade
$V_x = V.\cos \theta$
$V_{y0} = V.\sin \theta$

#### Observações
- Se corpo voltar ao mesmo nível de lançamento o tempo de subida será igual ao tempo de descida.
- Se o corpo voltar ao mesmo nível de lançamento o módulo da velocidade de lançamento será o mesmo que o módulo de chegada ($V_0 = V_F$).
- No ponto de altura máxima existe apenas velocidade na horizontal ($V_x$).
- O ângulo que apresenta maior alcance é o de $45\degree$.

## Movimento Circular
O movimento circular é aquele em que o corpo se desloca em uma trajetória circular. Uma força centrípeta muda a direção e o sentido do vetor velocidade, sendo continuamente aplicada para o centro do círculo.
A velocidade é tangente à trajetória e tem sua direção e sentido continuamente modificados.
O ângulo entre a velocidade tangencial e a aceleração centrípeta é $90\degree$.

### Aceleração Centrípeta
A aceleração centrípeta é responsável por medir a taxa de variação do vetor velocidade tangencial (em direção e sentido). Sempre aponta para o centro da circunferência.

#### Função
$a_c = {V^2 \over r}$
$a_c =$ Aceleração centrípeta
$V =$ Velocidade tangencial
$r =$ Raio da circunferência

### Aceleração Tangencial
A aceleração tangencial é tangente ao vetor velocidade tangencial. Mede a taxa de variação do módulo da velocidade tangencial ou linear.

#### Sentidos iguais
A velocidade **aumenta** em módulo mantendo direção e sentido constantes.

#### Sentidos opostos
A velocidade **diminui** em módulo mantendo direção e sentido constantes.

### Aceleração Resultante
É a soma das acelerações centrípeta e tangencial.
$\|\vec{a_r}\| = \sqrt{\|\vec{a_t}\|^2 + \|\vec{a_c}\|^2}$

## Movimento Circular Uniforme (MCU)
O Movimento Circular Uniforme é caracterizado por ser um movimento com trajetória circular onde o módulo da velocidade é constante, mas a direção e o sentido variam, portanto **o MCU é um movimento com aceleração.**

### Período
#### Símbolo: $T$
#### [[Unidades#Segundo|Unidade]]: $s$
O período é o tempo gasto em uma volta completa.

#### Exemplos
- O período de rotação da Terra é de aproximadamente $24h$.
- O período de translação da Terra é de aproximadamente $365$ dias.

### Frequência
#### Símbolo: $f$
#### [[Unidades#Hertz|Unidade]]: $Hz$
Número de voltas por unidade de tempo. Medido em ${n \over s}$. Comumente representada em [[Unidades#Frequência#$RPM$|RPM]] (rotações por minuto).

### Relação Entre Período e Frequência
O período e frequência são **inversamente proporcionais**.
$T = \dfrac{1}{f}$ e $f = \dfrac{1}{T}$

### Velocidade Tangencial/Linear
Quanto maior o raio do disco, maior a será a velocidade linear.
**Velocidade e raio são diretamente proporcionais.**
$V = \dfrac{\Delta S}{\Delta t} = \dfrac{2\pi.R}{T} = 2\pi.R.f$

### Velocidade Angular (rad/s)
#### Símbolo: $\omega$
$\omega = \dfrac{\Delta \theta}{\Delta t}$
$\omega$ depende diretamente da frequência, mas não depende do raio.

### Outras Relações
$\Delta S = \theta.R$
$V = \omega.R$
$a_c = \dfrac{V^2}{R} = \omega^2.R$
$\omega = 2\pi.f$

### Acoplamentos de Eixo Separados
Rodas conectadas por eixos diferentes possuem velocidades angulares ($\omega$) distintas, mas velocidades lineares iguais. Ex: engrenagens, correia.

$V_1 = V_2$
$2\pi R_1 f_1 = 2\pi R_2 f_2$
$R_1 f_1 = R_2 f_2$ ou $\dfrac{R_1}{T_1} = \dfrac{R_2}{T_2}$

outra relação:

$V_1 = V_2$
$\omega_1.R_1 = \omega_2.R_2$

### Acoplamentos de Mesmo Eixo
Rodas conectadas no mesmo eixo possuem a mesma velocidade angular ($\omega$) e mesma frequência ($f$) mas velocidades lineares diferentes.