# Exercise Set 1 for the Financial Markets Course

Commit with your solutions. 

Prove the following: 

(i) \prec is both irreflexive (x \prec x never holds) and transitive 

To prove this proposition the relation \succ is irreflexive and transitive, we'll follow the same approach as before: 

\begin{itemize}
\item Irreflexivity: We need to show that $x \nsucc x$ for all $x$ 
\item Transitivity: We must also demonstrate that if $x \succ y$ and $y \succ z$, then $x \succ z$

Then for irreflexivity assume there exists an $x$ such that $x \succ x$. This would imply that $x$ is strictly better than itself, which is a contradiction for the definition of irrefexivity. Therefor $x \succ x never holds$. 

For the transitivity. Suppose $x \succ y$ and $y \succz z$. then by the definition of the strong perfered, $x$ is strickly better than $y$, and $y$ is strickly better than $z$. To prove transitivity, we need to show that $x$ is strickly better than $z$. Since $x \succ y$ and $y \succ z$, by the definition of transitivity, we can conclude that $x \succ z$. 

Therefore, $\succ$ is both irreflexive and transitive. 

Proposition (ii)
