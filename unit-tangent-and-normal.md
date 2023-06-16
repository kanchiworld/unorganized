
Unit Tangent and Unit Normal vectors in 2-D

The point is that unit normal can be calculated simply by visual observation. (flip the coeff of i and j, and introduce a minus sign on any one of them. We don’t have to take the derivatives to calculate unit normal in 2-D case. Proof below).

$$
\vec{r}\left(t\right)\ \equivf\left(t\right)\hat{i}+g\left(t\right)\hat{j}
Unit Tangent 
\vec{T}\left(t\right)=\frac{\vec{r^\prime}\left(t\right)}{\left|\vec{r^\prime}\left(t\right)\right|}
=\frac{f^\prime\hat{i}+g^\prime\hat{j}}{\sqrt{f^{\prime2}+g^{\prime2}}}

Unit Normal
\vec{N}\left(t\right)=\frac{\vec{T^\prime}\left(t\right)}{\left|\vec{T^\prime}\left(t\right)\right|}
\vec{T^\prime}\left(t\right)=\frac{1}{\sqrt{\left(f^{\prime2}+g^{\prime2}\right)}}\frac{d}{dt}\left(f^\prime\hat{i}+g^\prime\hat{j}\right)+\left(f^\prime\hat{i}+g^\prime\hat{j}\right)\frac{d}{dt}\left(\frac{1}{\sqrt{\left(f^{\prime2}+g^{\prime2}\right)}}\right)

=\frac{1}{\sqrt{\left(f^{\prime2}+g^{\prime2}\right)}}\left(f^{\prime\prime}\hat{i}+g^{\prime\prime}\hat{j}\right)+\left(f^\prime\hat{i}+g^\prime\hat{j}\right)\left(\frac{-1}{2}\right)\left(\frac{2f^\prime f^{\prime\prime}+2g^\prime g^{\prime\prime}}{\left(f^{\prime2}+g^{\prime2}\right)^{3/2}}\right)
=\frac{1}{\left(f^{\prime2}+g^{\prime2}\right)^{3/2}}\left[\left(f^{\prime2}+g^{\prime2}\right)\left(f^{\prime\prime}\ i+g^{\prime\prime}\ j\right)-\left(f^\prime f^{\prime\prime}+g^\prime g^{\prime\prime}\right)\left(f^\prime\ i+g^\prime j\right)\right]
=\frac{1}{\left(f^{\prime2}+g^{\prime2}\right)^{3/2}}\left[\left(g^{\prime2}f^{\prime\prime}-f^\prime g^\prime g^{\prime\prime}\right)i+\left(f^{\prime2}g^{\prime\prime}-f^\prime g^\prime f^{\prime\prime}\right)j\right]

=\frac{1}{\left(f^{\prime2}+g^{\prime2}\right)^{3/2}}\left[g^\prime\left(g^\prime f^{\prime\prime}-f^\prime g^{\prime\prime}\right)i-f^\prime\left(g^\prime f^{\prime\prime}-f^\prime g^{\prime\prime}\right)j\right]
=\frac{\left(g^\prime f^{\prime\prime}-f^\prime g^{\prime\prime}\right)}{\left(f^{\prime2}+g^{\prime2}\right)^{3/2}}\left[g^\prime i-f^\prime j\right]
\left|\vec{T^\prime}\right|=\frac{\left(g^\prime f^{\prime\prime}-f^\prime g^{\prime\prime}\right)}{\left(f^{\prime2}+g^{\prime2}\right)^}

\vec{N}\left(t\right)=\frac{\vec{T^\prime}\left(t\right)}{\left|\vec{T^\prime}\left(t\right)\right|}

=g’i-f’jf’2+g’2

$$















