# CH6 電感與電磁
## 目錄
> [目錄](#目錄)

> [6-1 磁的基本概念](<#6-1-磁的基本概念>)
> > [6-1-1 磁極、磁場與電力線](<#6-1-1-磁極、磁場與電力線>)
> > [6-1-2 磁通量與磁通面積](<#6-1-2-磁通量與磁通面積>)
> > [6-1-3 磁動勢與磁場強度](<#6-1-3-磁動勢與磁場強度>)  

> [6-2 電磁感應](<#6-2-電磁感應>)

>[6-3/6-4 電感](#6-36-4-電感)

## 6-1 磁的基本概念
### 6-1-1 磁極、磁場與電力線
1. 磁極 (<font color="blue">m</font>) <font color="green">(</font><font color="red">$N$</font>  <font color="blue">$S$</font><font color="green">)</font>
2. 磁場 (<font color="blue">$\vec{H}$</font>)
3. 磁力線 (<font color="blue">$Φ$</font>)
    * 1. 切線方向為磁場方向
    * 2. <font color="red">**永不相交**</font>
    * 3. 外部: <font color="red">$N$</font> → <font color="blue">$S$</font>, 內部: <font color="blue">$S$</font> → <font color="red">$N$</font>
    * 4. <font color="red">封閉</font>曲線
    * 5. 磁極<font color="red">不可</font>單獨存在
    * 6. 垂直進/出磁極
### 6-1-2 磁通量與磁通面積
1. $$B=\frac{Φ}{A}\quad(T,\,特斯拉\,或 \,Wb/m^2)$$
    * $B$: 磁通密度
    * $A$: 截面積
    * $\Phi$: 磁通量
2. $$Φ = m$$
    * $\Phi$: 磁通量
    * $m$: 磁極
3. $1\,Wb\,=\,10^8線\,=\,10^8馬克士威\,(Maxwell)$
### 6-1-3 磁動勢與磁場強度
1. $$\mathcal{F}=IN=H\ell=Φ\mathcal{R}\quadΦ=BA\quad\mathcal{R}=\frac{\ell}{\mu A}$$
    * $\mathcal{F}$: 磁動勢
    * $N$: 匝數 ($T$)
    * <font color="red">**☆ $\ell$: 磁路長度**</font>
    * $\mathcal{R}$: 磁阻
    * $\mu$: 導磁係數
    * $H$: 磁場強度
    * $\mu=\mu_0\mu_r$
    * $\mu_0=4π\times10^{-7}=\frac{B}{H}$

## 6-2 電磁感應
1. 法拉第定律 $$e=N\frac{ΔΦ}{Δt}$$
2. 冷次/愣次定律 $$e=-N\frac{ΔΦ}{Δt}$$
    * $e$: 感應電勢
3. Fleming's (佛來銘/夫來銘) 右手定則
    * 拇指: $F$ 力 ($V$ 速度)
    * 食指: $B$ 磁
    * 中指: $I$ 或 $e$ 電
    * $$e=B\ell v\sinθ$$
        * $\ell$: 線長
        * $v$: 移動速度
## 6-3/6-4 電感
1. <img src="https://resources.mrchip.cn/storage/images/20220321/223db2de563c29c766a6679c6a33ea49.png" width=75/> 電感器 (<font color="red">$L$</font> ($H$, 亨利))
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTtVi3rUUrM_aIYa_PQ9dJNaoYTnOIm7tv6Rp1WSkzgQEbP4wOwyAAlea9rfgxXzIq7DI&usqp=CAU" width=75 height=40> 可變電感器
2. $$e=N\frac{ΔΦ}{Δt}=L\frac{Δi}{Δt}$$
3. $$N^2=LR\quad L=\frac{N^2}{R}=\frac{\mu AN^2}{\ell}\quad R=\frac{\ell}{\mu A}$$
4. $$IL=et=NΦ$$
5. $$L_串=L_1+L_2+...$$
    * <font color="red">考慮互感($M$): </font>$L_串=L_1+L_2\color{red}{±2M}$
6. $$L_並=\frac{L_1L_2}{L_1+L_2}$$
    * <font color="red">考慮互感($M$): </font>$L_並=\frac{L_1L_2\color{red}{-M^2}}{L_1+L_2\color{red}{\mp M}}$
7. $$M=\sqrt[K]{L_1L_2}$$
    * $K=\frac{Φ_{12}}{Φ_1}=\frac{Φ_{21}}{Φ_2}$
8. $$I_1M=e_2t=N_2Φ_{12}$$
9. $$W=\frac{1}{2}QV=\frac{1}{2}LI^2