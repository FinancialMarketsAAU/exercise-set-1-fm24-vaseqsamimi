# Exercise Set 1 for the Financial Markets Course

Commit with your solutions. 

Prove the following: 

(i) $\prec$ is both irreflexive ($x \prec x$ never holds) and transitive 

To prove this proposition the relation \succ is irreflexive and transitive, we'll follow the same approach as before: 

\begin{itemize}
\item Irreflexivity: We need to show that $x \nsucc x$ for all $x$ \\
\item Transitivity: We must also demonstrate that if $x \succ y$ and $y \succ z$, then $x \succ z$
\end(itemize)

Then for irreflexivity assume there exists an $x$ such that $x \succ x$. This would imply that $x$ is strictly better than itself, which is a contradiction for the definition of irrefexivity. Therefor $x \succ x$ never holds. 

For the transitivity. Suppose $x \succ y$ and $y \succ z$. then by the definition of the strong perfered, $x$ is strickly better than $y$, and $y$ is strickly better than $z$. To prove transitivity, we need to show that $x$ is strickly better than $z$. Since $x \succ y$ and $y \succ z$, by the definition of transitivity, we can conclude that $x \succ z$. 

Therefore, $\succ$ is both irreflexive and transitive. 

Proposition (ii)

To prove that the relation $\sim$ is reflexive, transitive, and symmetric: 

\begin{enumerate}
  \item The reflexitivity states that. $\forall x \in X, x \sim x$ holds. 
  \item For the transitivity states that. If $x \sim y$ and $y \sim z$, then $x \sim z \forall x,y,z \in X$. 
  \item Lastly symmetry states that: If $x \sim y$, then $y \sim x \for all x,y \in X$
\end{enumerate}

This directly states the properties of the 3 condition above and by that means the relation $\sim$ must satisfy.

Proposition (iii)

"If $x \succ y$ and $y \sim z", then $x \succ z$. 


2. Lexicographic preference
(i) To show that the lexicographic preference relation $\succsim$ is transitive, we need to prove that if $(x_1, x_2) \succsim (y_1,y_2)$ and $(y_1,y_2) \succsim (z_1,z_2), then (x_1, x_2) \succsim (z_1, z_2).

Let's consider the cases: 

1. If $x_1 \leq y_1$, and $y_1 \leq z_1$, then $(x_1, x_2 \succsim (z_1,z_2)$.

2. If $x_1=y_1$ and $y_1=z_1$, then $x_1 \geq y_2$ and $y_2 \geq z_2$ then $x_2 \geq z_2$ and by that, this means that, $(x_1,x_2) \succsim (z_1,z_2)$.

In both cases $(x_1,x_2) \succsim (z_1,z_2)$ holds. Therefore, the lexicorgraphic preference relation is transitive. 

(ii)

Now we need to show that $\succsim$ is not continous, we cosider the sequence $(x^n_1,x^n_2)=(1-1/n,1)$ and $(y_1,y_2)=(1,0)$. 

For this sequence, as n approaches infinity $(x^n_1, x^n_2)$ converges to $(1,1)$, and $(y_1,y_2)=(1,0)$. 

Since $(1,1) \succsim (1,0)$ when $x \approach \infty$ the $(1-1/n,1)=(1,1)$  

Now, while $(1,1) \succsim (1,0)$ due to the first compononent of $(1,1)$ being greater than the first component of $(1,0)$, we also have $(1,0)  \not \succsim (1,1)$ because the second component that means $(1,0)<(1,1)$. 

This discontiniuity occours because the lexicographic preference relation $\succsim$ does not consider the second component until the first component is equal. 

