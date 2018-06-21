$$\bf Thm\ 2.1$$ 
Division algo.
給整數a和b，b > 0, 會存在unique整數q跟r滿足
$$a = qb + r, 0\leq r < b$$.
$$\it Proof$$

$$\blacksquare$$

這定理可以應用在把整數分類。比如說，所有的數字$$n$$都只會是奇數或偶數，所以$$n = 2b + 1$$或是$$n = 2b$$，在題目上好用的是，如果給出一個奇怪的close form要你證明它是$$q$$的倍數，那麼我們可以把數字分成$$\{n = qb + i\mid 0 \leq i  < q\}$$，把全部i種n一個一個代進去即可。

應用題:
![](https://i.imgur.com/Uaaiq07.png)
Problems 2.1中的3,4,5,6,8,9,10。

$$\bf Def\ 2.1$$
$$a \mid b$$: a divides b.
$$a \nmid b$$: b is not divisible by a.

$$\bf Def\ 2.2$$
Greatest Commom Divisor(GCD):
Greatest Commom Divisor of a and b, denoted by gcd(a,b), is the positive integer d satisfying the following:
(1) $$d \mid a$$ and $$d \mid b$$
(2) if $$c \mid a$$ and $$c \mid b$$, then $$c \leq d$$.

$$\bf Thm\ 2.3$$
gcd(a,b) = ax + by, not both of which are zero.
$$\it Proof$$

$$\blacksquare$$

$$\bf Def\ 2.3$$
a and b,not both of which are zero, are said to be relatively prime whenever gcd(a,b) = 1.

$$\bf Thm\ 2.4$$
a and b,not both of which are zero.Then a and b are relatively prime $$\Leftrightarrow$$ $$\{1 = ax + by \mid a, b  \in integer \}$$
$$\it Proof$$

$$\blacksquare$$

$$\bf Coro\ 1$$
if gcd(a,b) = d, then gcd(a/d, b/d) = 1.
$$\it Proof$$

$$\blacksquare$$

$$\bf Coro\ 2$$
if $$a \mid c$$ and $$b \mid c$$ with gcd(a,b) = 1, then $$ab \mid c$$.
$$\it Proof$$

$$\blacksquare$$

$$\bf Thm\ 2.5\ Euclid's\ lemma$$
if $$a \mid bc$$ with gcd(a,b) = 1, then $$a \mid c$$.
$$\it Proof$$

$$\blacksquare$$

$$\bf Thm\ 2.6$$
d = gcd(a,b)$$\Leftrightarrow$$
(1) $$d \mid a$$ and $$d \mid b$$
(2) if $$c \mid a$$ and $$c \mid b$$, then $$c \mid d$$.
注意，這裡指出了比$$\bf Def\ 2.2$$更強的結果，指出$$c \mid d$$, 不僅僅是$$c \leq d$$.
$$\it Proof$$

$$\blacksquare$$

![](https://i.imgur.com/7jwWd1K.png)
![](https://i.imgur.com/cnwNcwt.png)
