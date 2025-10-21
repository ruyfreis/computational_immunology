Modelo matemático

A interação entre **bactérias** \(B(t)\) e **neutrófilos** \(N(t)\) é descrita por:

$$
\begin{aligned}
\frac{dB}{dt} &= c_pB - \lambda_{nb}NB,\\
\frac{dN}{dt} &= \gamma_nB(cn_{\max} - N) - \lambda_{bn}N\,B - \mu_nN,
\end{aligned}
$$

em que:
- $c_p$: taxa de crescimento bacteriano;
- $\lambda_{nb}$: taxa de fagocitose (eliminação de bactérias por neutrófilos);
- $\gamma_n$: permeabilidade/recrutamento de neutrófilos induzido por \(B\);
- $cn_{\max}$: capacidade máxima de neutrófilos no tecido;
- $\lambda_{bn}$: taxa de apoptose de neutrófilos induzida por \(B\);
- $\mu_n$: taxa de decaimento natural de neutrófilos.
