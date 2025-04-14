## Berry Phase Theory in solids
#### Adiabatic Theorem
什么是绝热过程？
对于一个单摆，如果我们握住支撑体剧烈地移动，那这个单摆将混乱的无规则摆动；如果我们平稳地移动支撑体，单摆将平滑地连续移动。这里涉及到了两个时间，外部时间$T_e$代表摆在振荡平台上平台的振荡周期；内部时间$T_i$代表摆的振荡周期。外部平稳的移动可看作一个绝热过程，即对应着$T_e\gg T_i$。

**绝热定理**：当系统的哈密顿量随时间缓慢变化时，若初始时刻系统处于某个非简并的本征态，则系统始终保持在对应的瞬时本征态上，并积累动力学相位和几何相位。

If _H_ doesn't include _t_
初始时刻$\psi(0)=\sum_{n}c_n\phi_n$
根据$i\hbar \frac{\partial}{\partial t}\psi(t)=\hat{H}\psi(t)$
$\psi(t)=\sum _{n}c_n \phi_n e^{-iE_n/\hbar}$

if H includes t
$i\hbar \frac{\partial}{\partial t}\psi(t)=\hat{H}(t)\psi(t)$
$\psi(t)=\sum _{n}c_n(t) \phi_n (t)e^{-iE_nt/\hbar}$

类似于不含时哈密顿量系统在t时刻多了动力学相位$-E_nt$，绝热系统的态函数会产生$\theta_n(t)$的动力学相位，并且由于哈密顿量的变化额外产生由$c_n$带来的几何相位$\gamma_n(t)$