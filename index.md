## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/sagisk/Matrix-Analysis-Roger-Horn-and-Charlie-Johnson/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

```markdown
# 1.0 Introduction

#### Exercise 1.0.P1
$x^TAx = \sum_{i}x_{i}\sum_{j}A_{ij}x_{j} = \sum_{i}\sum_{j}A_{ij}x_i^2$ is a quadratic function of $x$ hence, it is continuous. Assuming that the set $S = \{x \in R^n : x^Tx = 1\}$ is compact (closed and bounded) we can apply the Weierstrass’s theorem to get that the function $x^TAx$ attains its maximum at some point in $S$. Then following the text derivations we have that $Ax = \lambda x$ where $\lambda$ is an eigenvalue of $A$. Hence, any real symmetric matrix have at least one real eigenvalue.

ToDo: Show that $S$ is a compact set.

#### Exercise 1.0.P2
The problem is: maximize $x^TAx$ subject to $x^Tx = 1$. Let's take the eigenvalue decomposition of $A$. Let $v_1,...v_n$ be the orthonormal eigenvectors of $A$. Note that the set of eigenvectors creates a basis for $R^n$ hence $x = \sum_{i = 1}^{n} a_iv_i$ and $x^TAx = \sum_{i=1}^{n}\lambda_i a_i^2$ (by noting that $Av_i = \lambda_iv_i$. Now the problem becomes: maximize $\sum_{i=1}^{n}\lambda_i a_i^2$ subject to $\sum_{i = 1}^{n} a_i^2 = 1$. Since the weights $a_i^2$ add up to one the greatest value will be achieved if we set up $a_i = 1$ for $i$ corresponding to the greatest eigenvalue $\lambda_i$ and $a_{j \not= i} = 0$. Hence, the solution of the problem is is the largest real eigenvalue of $A$.

```

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
