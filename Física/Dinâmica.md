
# Força
### [[Unidades#Newton|Unidade]]: $N$
Agente capaz de deformar ou alterar estado de movimento de um corpo. Surge com a interação entre 2 corpos.

## Classificação

### Forças de Contato
São forças que surgem no contato de dois corpos.
Ex: Quando puxamos/empurramos um corpo.
### Forças de Campo
São forças que atuam à distância, dispensando o contato.
Ex: Um ímã e um metal, satélite e Terra.

# Força Resultante
### Símbolo: $\vec{F_R}$
[[Vetores#Soma|Soma vetorial]] de todas as forças aplicadas sobre um corpo.
$\vec{F_R} = \vec{F_1} + \vec{F_2} + \vec{F_3} + \dots$

# Massa
### [[Unidades#Quilograma|Unidade]]: $Kg$
Medida da inércia de um corpo.


# Leis de Newton

## Primeira Lei de Newton: Inércia
Propriedade dos corpos de resistirem a mudança em sua velocidade. Tendência natural de um corpo a manter um [[Cinemática#Movimento Retilíneo Uniforme (MRU)|MRU]] ou repouso.

## Segunda Lei de Newton: Princípio Fundamental
A força resultante que atua em um corpo é igual ao produto de sua massa por sua aceleração.
"força má"
### $\vec{F_R} = m \times \vec{a}$

- A aceleração de um corpo é diretamente proporcional à força resultante que sobre ele atua.
- A aceleração de um objeto é inversamente proporcional à sua massa.

$\vec{F_R} = 0 \implies \vec{a} = 0 \implies V$ constante $\implies$ Repouso ou [[Cinemática#Movimento Retilíneo Uniforme (MRU)|MRU]]
$\vec{F_R} \neq 0 \implies \vec{a} \neq 0 \implies V$ varia $\implies$ [[Cinemática#Movimento Retilíneo Uniformemente Variado (MRUV)|MRUV]] ou [[Cinemática#Movimento Circular Uniforme (MCU)|MCU]]

## Terceira Lei de Newton: Ação e Reação
- Força é uma interação simultânea entre 2 corpos.
- Força = par ação e reação
- A ação **nunca** anula a reação, pois estão em corpos diferentes.
- As forças de ação e reação possuem mesmo módulo, mesma direção e sentidos opostos.
- O par aparece instantaneamente, então qualquer uma das forças pode ser ação ou reação.

# Forças Importantes

## Peso
### Símbolo: $\vec{P}$
Força de atração gravitacional aplicada em um corpo.
### $\vec{P} = m \times \vec{g}$

## Força Normal
### Símbolo: $\vec{N}$
Força de reação que uma superfície exerce sobre qualquer corpo que lhe aplica uma força. Também pode ser considerada a força de compressão entre dois objetos. É sempre perpendicular ao plano de contato entre os corpos.

## Força de Atrito
Força que se opõe ao movimento relativo entre duas superfícies ou sua tendência. É proporcional à **força normal**.
É chamada de **força de atrito estático** quando **ainda não há movimento** e **força de atrito dinâmico/cinético** quando **há movimento**. Todo material possui um **coeficiente de atrito estático** $\micro_e$ e **coeficiente de atrito dinâmico/cinético** $\micro_c$.

### Força de Atrito Estático
Força máxima de atrito estático. Quando for vencida, o objeto entrará em movimento.
$\vec{F}_{at(max)} = \micro_e \times \vec{N}$

### Força de Atrito Cinético 
$\vec{F}_{at_d} = \micro_c \times \vec{N}$

![[iminencia-movimento.png]]

## Força de Tração
### Símbolo: $\vec{T}$
É a força que é aplicada pelos fios (cordas, tirantes, cabos etc.) para puxar algum corpo.
Um fio transmissor de força é considerado **ideal** quando ele é **inextensível, flexível e de massa desprezível**.
$\vec{T} = \vec{F}_R \implies \vec{T} = m \times \vec{a}$

### Com Atrito
$\vec{T} - \vec{F}_{at} = \vec{F}_R$
$$\text{se } \vec{T} - \vec{F}_{at} = 0 \to
\begin{cases}
\text{atrito estático} \to \vec{T} - \micro_e N = 0 \\
\text{atrito dinâmico} \to \vec{T} - \micro_c N = 0 \\
\end{cases}
$$
$$\text{se } \vec{T} - \vec{F}_{at} \neq 0 \to
\begin{cases}
\text{atrito dinâmico} \to \vec{T} - \micro_c N = m \times \vec{a} \\
\end{cases}
$$

### Sistemas de Corpos
![[sistema-tracao.png]]
$\vec{T} = (m_1+m_2) \times \vec{a}$
$\vec{T}_{1,2}=\vec{T}_{2,1}$
bloco 1: $\vec{T}_{2,1} = m_1 \times \vec{a}$
bloco 2: $\vec{T} - \vec{T}_{1,2} = m_2 \times \vec{a}$

### Plano Inclinado
![[tracao-inclinado.png]]
$P_x = \sin \theta$, $P_y = \cos \theta$
$N$ e $P_y$ se anulam
$\vec{F}_R = T - P_x$


## Força Elástica
### Símbolo: $F_{el}$
Força com a qual uma mola reage a uma força externa que a comprime ou a distende.
$F_{el} = k \times \Delta x$
$k =$ coeficiente de elasticidade
$\Delta x =$ Distância da deformação em metros

## Força Centrípeta
### Símbolo: $F_c$
Força resultante responsável por manter um corpo em uma trajetória circular. "Causa" da aceleração centrípeta.

## Força de Resistência do Ar
Depende do formato e velocidade do corpo.
$R_{ar} = k \times -\vec{V}^2$
$k =$ constante que depende do corpo, da área de sua maior seção transversal ao movimento e da densidade do ar.