# Wielomiany
## zadanie rozwiązane metodą hornera

$$  W(x) = 6 x^4 - x^3 +5x^2 - 1x -1$$

pierwiastkami tego wielomanu mogą być dzielniki wyrazu wolnego {$\pm1$}, LUB ułamek dzielników wyrazów wolnego, przez dzielniki wyrazu najwyższego stopnia czyli {$\pm\frac{1}{6}$ ; $\pm\frac{1}{3}$ ; $\pm\frac{1}{2}$}

w tym wypadku W(1) = 8, a W(-1) = 12

dlatego próbujemy teraz ułamki, i wychodzi nam że W($\frac{1}{2}$)=0, dlatego używamy schematu hornera aby $$(6 x^4 - x^3 +5x^2 - 1x -1): (x-\frac{1}{2})$$ 

|   |6  |-1 |5  |-1 |-1 |
|---|---|---|---|---|---|
|$\frac{1}{2}$||$(6*\frac{1}{2})-1$|1+5|3-1|1-1|
|             |6|2|6|2|0|

ze schematu hornera dostajemy

$$W(x) = (6x^3 + 2x^2 + 6x +2) * (x - \frac{1}{2})$$

{{< katex display >}}