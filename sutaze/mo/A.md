# 1.

# 2.

# 3. 
**Nájdite všetky celé čísla n také, že $𝑛 > 2$ a čı́slo $n^{n-2}$ je n-tá mocnina celého čı́sla**
$$ \forall \ n \in \mathbb{N}-\{1,2\} : \exists\ x \in \mathbb{N} : $$
$$ n^{n-2} = x^n $$
$$ n^{\frac{n-2}{n}} = x $$
$$ \frac{n}{n^{2/n}} = x $$

Hľadáme všetky n pre ktoré je x celé číslo.
Riešením tejto rovnice pre definovanú množinu čísel je jedine $n=4$
Pre $n=3$ je $x \approx 1.44$
Dokážeme že nemá riešenia pre $n\geq5$
Zamerajme sa na $n^{2/n}$ ak dokážeme, že je iracionálne, tak x je iracionálne.
Dokážeme to sporom:
$gcd(a,b) =$ najväčší spoločný deliteľ

$$ \exists \ a,b \in \mathbb{N}: gcd(a,b) = 1 \ \land \  n^{2/n} = a/b $$
$$ \exists \ p \in \mathbb{P} : p|a \implies p^n|a^n $$
$$ n^{2/n} = a/b \implies b^nn^2=a^n $$
$$ p^n|a^n \land b^nn^2=a^n \implies p^n|n^2 $$
$$ (\spadesuit)\quad p^n \geq 2^n > n^2 $$

$2^n > n^2$ dokážeme následovne indukciou (dôležité: $n\geq5$):

$$ 2^5 > 5^2 \rightarrow 32 > 25 \ \checkmark $$
$$ \exists \ k \in (4;inf) : 2^k > k^2 $$
$$ (\star)\quad 2*2^k > 2k^2 \rightarrow 2^{k+1} > 2k^2 $$

Keďže k > 4 tak:
$$ (k-1)^2\geq4^2>2 $$
$$ \begin{align}
k^2-2k+1>&\,2\\
k^2-2k-1>&\,0\\
2k^2-2k-1>&\,k^2\\
2k^2>&\,k^2+2k+1=(k+1)^2,
\end{align} $$

Podľa $(\star)$ a predošlého dôkazu :
$$ 2^{k+1} > 2k^2 \implies 2^{k+1} > (k+1)^2 \implies 2^n > n^2 $$
Ale týmpádom v $(\spadesuit)$ nastáva spor, keďže väčšie číslo nemôže deliť menšie, takže $n^{2/n}$ je iracionálne číslo:

$$ (n \in \mathbb{N}-\{1,2,4\}) : n^{2/n} \notin \mathbb{Q} \implies \frac{n}{n^{2/n}} \notin \mathbb{Q} $$
$$ QED $$

# 4.

# 5.

# 6.