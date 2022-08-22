$\def\defequiv{{\; \cdot\equiv\cdot \;}}$

# A method of constructing a non-standard model in the Bernays-Gödel axiomatic set theory

Petr Vopěnka
(Presented by Academician P. S. Alexandrov on October 12, 1961)

The initial system is the axiomatic system $\Sigma^*$ of set theory (cf. [1]). For this system, we construct another model. Ordinal numbers of the model are not well ordered in terms of the original theory. The general method for constructing such a model can be applied on some special occasions, for example, for constructing a model in which there are $2^{\aleph_0}$ natural numbers from the point of view of the theory in which the model is built.

1. In the following we denote by $s$ an infinite set, and by $I$ a maximal ideal on $P(s)$, if $I$ is a set of subsets of $s$, for which:

    1) If $a\in I,\; b\subseteq s,\; a\subseteq b$, then $b\in I$.
    2) If $a\in I,\; b\in I$, then $a\cap b\in I$.
    3) If $a\cup b \in I$, then either $a\in I$ or $b \in I$.

$\quad\quad K(s, I)$ is the class of all functions defined on the set $s$. Let's define for two such functions $f(x)$ and $g(x),\ f \equiv g \pmod{I}$ if and only if $f(x) = g(x)$ for all $x$ from some set $m\in I$. The relation $f \equiv g \pmod I$, is obviously reflexive, symmetric and transitive.

2. Define the sets $P_\alpha$ for any ordinal number $\alpha$ by induction: $P_0 = 0, P_\alpha = \mathbf{P}(\cup_{\beta<\alpha}P_\beta)$. Obviously, $\cup_{\alpha\in O_n} P_\alpha = V$ (their union equals the universal class). For every $x\in V$ there is a first $\alpha\in O_n$ such that $x\in P_\alpha$ (we denote $\alpha = \tau(x)$).
 For each $f\in K(s, I)$, we define $\mathrm{ind}_f = \inf_{m\in I} \sup_{x\in m} z (f (x))$. Obviously from $f \equiv g \pmod I$ it follows that $\textrm{ind}_f = \textrm{ind}_g$.
 Let us define the class $K'(s, I)$ as follows: $f\in K'(s, I)\defequiv f\in K(s, I)\&\tau(f(x))<\textrm{ind}_f$ for any $x\in s$. For the class $K'(s, I)$ it holds:
 1) for every $f\in K(s, I)$ there exists $g\in K'(s, I)$ such that
$g \equiv f \pmod I$;
 2) for every $f\in K'(s, I)$ the class $\bar{f}$ of all $g\in K'(s, I)$ with $g \equiv f \pmod I$ is a set.

3. The class of all sets $\bar{f}$ (for $f\in K'(s, I)$) will be denoted by $\bar{V}$. The class $\bar{E}$ contains exactly the ordered pairs of the type $\langle\bar{f}, \bar{g}\rangle$, for which: $\bar{f}\in V\&\bar{g}\in V\& f(x)\in g(x)$ for all $x$ of some $m\in I$. Obviously $\langle\bar{f}, \bar{g}\rangle$ does not depend on the choice of special functions from the sets $f$ and $g$.
 Let us define the class $\varphi(\bar{f})$ for any $\bar{f}\in \bar{V}$ as follows: $\bar{g}\in\varphi(\bar{f}) \defequiv \langle\bar{f}, \bar{g}\rangle\in \bar{E}$.

4. Sets $(\Pi^*)$, classes $(\text{Cls}^*)$ and the relation $\in^*$ of the model $\Gamma(s, I)$ are defined as follows:
\\[M^*(X) \defequiv X\in\overline{V}; \\]
$\text{Cls}^*(X) \;.\hspace{-2pt}\equiv.\; X\subseteq \overline{V}$ and for every $\overline{f}$ there is $\overline{g}$ such that
\\[\varphi(\overline{g}) = X \cap \varphi(\overline{g});\\]
\\[x\in^* Y \defequiv \{ M^*(x) \;\&\; M^*(Y) \;\&\; \langle XY\rangle \in \overline{E}\} \cdot\cup\cdot \{M^*(x)\;\&\;\text{Cls}^*(Y)\;\&\; X\in Y\}.\\]
The set $\overline{f}$ is equal to the class $\varphi(\overline{f})$ (of the model $\Gamma(s, I)$). It can be proved, that this model satisfies all the axioms of the system $\Sigma^*$.

5. Class $O_n^*$ of the model $\Gamma(s, I)$ consists of all sets $\overline{f}$ such that on some $m\in I$ the function $f(x)$ takes as its values only ordinal numbers of the original theory.
 The natural numbers of the model are sets $\overline{f}$ such that on some $m \in I$ the function $f(x)$ takes as its values only the natural numbers of the original theory.
 In the case when $I$ consists of all subsets of the set $s$ containing one element, $\Gamma(s, I)$ is isomorphic to the original theory. In other cases, we obtain a non-standard model of set theory. If, for example, $s$ is a countable set, then there are $2^{\aleph_0}$ natural numbers of the model $\Gamma(s, I)$ from the point of view of the original theory, but in this case there are also $2^{\aleph_0}$ ordinal numbers up to the first uncountable from the point of view of the original theory.
 In the case when $s$ is uncountable and $I$ is not equivalent to an ideal on a set of smaller cardinality, then we obtain a model which is not isomorphic to $\Gamma(s', I')$, where $|s'| < |s|$.

Charles University in Prague, Czech Republic
Received on September 1, 1961

### References
1. K. Gödel, Ann. of Math. Studies, No. 3 (1940).
