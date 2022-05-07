---
id: wb9m1vj5fzs4xzwwwclutvc
title: Wip
desc: ''
updated: 1651893627866
created: 1651887422132
---
# Compare tax on investment Vietnam vs U.S.


![[notes.reading.tax-investors-vn#key-takeaway,1:#*]]

![[notes.reading.tax-investors-us#notes-from-reading,1:#*]]

- exchange rate on 2022-05-07: $1\ USD = 22,956.50\ VND$
- dividend: $D = D_O + D_Q$
    - ordinary dividend: $D_O$
    - qualified dividend: $D_Q$
- capital gain: $G = V_t-V_0$
    - Investment value at year 0 (initial time): $V_0$
    - Investment value at year t (selling time): $V_t=(1+r)^tV_0$
    - annual return: $r = 12\%$
- US: 
    - Single tax filling, 
    - annual income $90k, 
    - federal income tax rate 24%, 
    - state income tax rate (California) 9.30%, 
    - federal income tax rate for ordinary dividend 24%, 
    - federal income tax rate for qualified dividend 15%

tax vn: 

$$
\begin{align}
T_{VN} &= 5\%D + 0.1\%V_t \\ 
&= 0.05(D_O + D_Q) + 0.001V_t \\
&= 0.001(1+r)^tV_0 + 0.05D_O + 0.05D_Q
\end{align}
$$

tax us:

federal tax: 
$$
\begin{align}
T_F &= T_C + T_{DO} + T_{DQ} \\
&= 20\%G + 24\%D_O + 15\%D_Q \\
\end{align}
$$

where
- long term capital gain tax: $T_C = 20\%G$
- no short term capital gain
- tax for ordinary dividend: $T_{DO} = 24\%D_O$
- tax for qualified dividend: $T_{DQ} = 15\%D_Q$

state tax: 

$$
\begin{align}
T_S &= 9.3\%(G + D_O + D_Q)
\end{align}
$$

So total tax in US
$$
\begin{align} 
T_{US} &= T_F + T_S \\
&= 0.293G + 0.333D_O + 0.243D_Q \\
&= 0.293\Big[(1+r)^t-1\Big]V_0 + 0.333D_O + 0.243D_Q
\end{align}
$$
