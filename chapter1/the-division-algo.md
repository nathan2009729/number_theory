$$\bf Theorem\ 2.1$$ 
Division algo.
給整數a和b，b > 0, 會存在unique整數q跟r滿足
$$a = qb + r, 0\leq r < b$$.
$$\it Proof$$

$$\blacksquare$$

這定理可以應用在把整數分類。比如說，所有的數字$$n$$都只會是奇數或偶數，所以$$n = 2b + 1$$或是$$n = 2b$$，在題目上好用的是，如果給出一個奇怪的close form要你證明它是$$q$$的倍數，那麼我們可以把數字分成$$\{n = qb + i\mid 0 \leq i  < q\}$$，把全部i種n一個一個代進去即可。