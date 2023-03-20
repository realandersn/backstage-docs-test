# LaTeX math equations

LaTeX math equations are available through [KaTeX](https://katex.org/) and the `katex-markdown` PyMarkdown extension. You can use inline or block equations. Prior to May 2020, we used [Mathjax](https://mathjax.org) for rendering our math equations and it was replaced in favour of KaTeX due to rendering issues.

### Inline

For inline math equations, you can use the following syntax.

```raw
$`p(x|y) = \frac{p(y|x)p(x)}{p(y)}, (p(x|y) = \frac{p(y|x)p(x)}{p(y)}).`$
```

### Blocks

For block math equations, you can use the following syntax:

````raw
```math
\begin{aligned}
p(v_i=1|\mathbf{h}) = \sigma\left(\sum_j w{ij}h_j + b_i\right) \\
p(h_j=1|\mathbf{v}) = \sigma\left(\sum_i w{ij}v_i + c_j\right)
\end{aligned}
```
````

### Examples

For real code samples, check out [our example Markdown file from our Mkdocs action container](https://ghe.spotify.net/pulp-fiction/mkdocs-action-container/blob/master/example-site/docs/index.md).
