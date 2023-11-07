# Analiza Matematyczna

## Ciągi

1. nierówność bernoulliego

$$(1+x)^n>1+nx$$
dla $n\ge 2$ oraz $x>-1$ oraz $x\neq 0$

2. zależność $e$

$$\lim_{x \to \infty}(1+\frac{c}{n})^n=e^c$$

3. kolejna zależność $e$

$$\lim_{x \to \infty}(1+\frac{1}{2n+3})^{2n+3}=e$$

4. Warunek Cauch'ego

$$|f(x)-g|< \epsilon $$
gdzie g to granica

5. Twierdzenie Bolzana-Weierstrassa

psuje się formatowanie tekstu wiec musisz przeczytać [gdzieś indziej](https://pl.wikipedia.org/wiki/Twierdzenie_Bolzana-Weierstrassa). tldr: Jak jest jakiś ciąg ograniczony to istnieje taki podciąg, który jest zbieżny, po prostu musisz ciąć oryginalny ciąg na salami, i któraś z połówek jest zbieżna.

1. Dwumian Newtona 
$${n\choose k}= \frac{n!}{k!*(n-k)!}$$

## Szeregi

1. Kryterium zagęsczenie(d'Alemberta):

jeśli:
$$\lim_{n \to \infty} \frac{a_{n+1}}{a_n} < 1 $$
to jest zbieźny.

natomiast, jeśli od pewnego momentu:
$$\frac{a_{n+1}}{a_n} \ge 1$$
to jest rozbieźny.

2. Kryterium Cauchy'ego

jeśli ciąg $a_n$ jest nierosnący dla wszystkich $n$:

$$\sum_{n=1}^{\infty}a_n$$

to ciąg $a_n$ jest tylko zbieżny kiedy kiedy poniższy ciąg też jest zbieżny: 

$$\sum_{n=1}^{\infty} 2^n*a_{2n}$$


99. źródła:
- <https://www.math.uni.wroc.pl/~mpal/academic/2023/skrypt.pdf>
- <https://pl.wikipedia.org/wiki/Ci%C4%85g_Cauchy%E2%80%99ego>
- <https://pl.wikipedia.org/wiki/Twierdzenie_Bolzana-Weierstrassa>
- <https://www.matemaks.pl/kryterium-d-alemberta.html>
- <https://pl.wikipedia.org/wiki/Kryterium_Cauchy%E2%80%99ego_zag%C4%99szczaj%C4%85ce>

{{< katex display >}}
