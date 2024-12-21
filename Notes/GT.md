+++
title="群論"
+++

# 群論

---

**目次**

\toc

---

## 群の定義

$X$が集合であるとき，写像$\phi:X\times X\to X$のことを集合$X$上の**演算**と呼ぶ．以下では特に断らない限り演算$\phi(a,b)$を単に$ab$と書くことにする．

\def{
    $G$を空集合でない集合とする．$G$上の演算が定義されていて，次の性質を満たすとき，$G$を**群(Group)**と呼ぶ：
    1. **単位元(identity)**と呼ばれる元$e\in G$があり，すべての$a\in G$に対し$ae=ea=a$となる．
    2. すべての$a\in G$に対し$b\in G$が存在し，$ab=ba=e$となる．この元は$a$の**逆元(inverse)**と呼ばれ，$a^{-1}$と書く．
    3. すべての$a,b,c\in G$に対し，$(ab)c=a(bc)$が成り立つ(**結合法則(associativity)**)．
}

上の演算$ab$のことを群の**積(product)**と呼ぶ．集合$G$が群になるとき，「集合$G$には**群の構造が入る**」などという．

\def{
    $a,b$が群$G$の元で$ab=ba$なら，$a,b$は**可換である(commute)**という．$G$の任意の元$a,b$が可換なら，$G$を**可換群**，あるいは**アーベル群(abelian group)**と呼ぶ[^1]．
}

[^1]: 可換群をcommutative groupと書いている教科書を見たことがないので，論文を書くときなどはabelian groupと書いた方が良いだろう．

\def{
    $G$が群であるとき，その元の個数$|G|$を$G$の**位数(order)**と呼ぶ．位数が有限な群のことを**有限群(finite group)**と呼び，有限群でない群を**無限群(infinite group)**と呼ぶ．
}

\note{
    単位元は1と書くことがある．また，可換群の場合，積のことを**和**と呼び$ab$を$a+b$と書くことがある．演算を$a+b$と書くときには，単位元を0と書くことがある．そして，群$G$と$a\in G$，$n\in\N$に対し，
    \[
        a^0=1,\quad \overbrace{a\cdots a}^{n}=a^n,\quad a^{-n}=(a^n)^{-1}
    \]
    と定義する．
}

簡単な例を見て上の定義を確認しておこう：

\eg{
    $G$を2つの元$a,b$よりなる集合とする．つまり$G=\{a,b\}$である．これらの元の積を
    \[
        a\cdot a=a,\quad a\cdot b=b,\quad b\cdot a=b,\quad b\cdot b=a
    \]
    と定義する．まとめた表のことを**群表(group table)**と呼ぶ．なお，4つの積は，(行の元)$\times$(列の元)を表すものとする[^2]．このとき$G$は位数2の有限群である．また明らかに可換群であることも分かる．
}

[^2]: レンダリングが技術的に難しい...
---