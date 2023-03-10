# Week 1

## Summary Questions
- Define a hyperplane in a way that helps you understand it conceptually.
  - A divider for a high-dimensional space that separates two classes of data.

# Week 2
## Synthesis Questions

### Linear Regression
- What is a feature in this context?
- What are the significant of the $\beta$ terms within the modified $y=mx+b$ equations described in the article?
- What is SSE	:
	- How is it calculated?
	- What can it tell you about the values you chose for $\beta$
	- If you modify the $\beta_{1}$ term and the SSE goes up, was that a good modification?
- Write out the linear regression formula (involving $\beta$) when you wish to estimate the impact of age, height, and weight of someone regarding their marital status.
- What are the 4 assumptions described that you need to confirm before using linear regression?
- What is homoscedasticity? What is heteroscedasticity?

### SVM
- What are some use cases for an SVM? What does it do?
- What is the margin?
- Why does the margin need to be maximized? What does this allow for?
- What are the support vectors?
- What is the difference between a hard and soft margin SVM?

### SVM Math
- $wx-b=-1$ defines a margin of support vectors.
- What are the $w$ variables in the equation?
	- The weight values applied to each feature of $x$
- What is the equation for the decision boundary?
	- $\vec{w}\cdot\vec{x}-b=0$
- What is the size of the margin in terms of the vector $w$
	$$\text{The entire margin across the decision boundary: }\frac{2}{||\vec{w}||}$$
- What needs to be minimized, and what are the constraints for finding the optimal hyperplane decision boundary?
	- Minimize $||\vec{w}||$ in order to maximize the margin
	- The constraints are:
	$$y_i(\vec{w}_i\cdot\vec{x}_{i}-b)\ge 1:\begin{cases}y_{1}=1\implies\vec{w}\cdot\vec{x}-b\ge\\y_{1}=-1\implies\vec{w}\cdot\vec{x}-b\le -1\end{cases},\quad\forall i\in[1,\ldots,N]$$

### PCA
- What does PCA do?
	- It reduced the dimensions of a dataset by trends among different features and combining them into principal components
	- It is useful when trying to visualize data beyond 3D
- What is a principal component?
	- A eigenvector of covariance matrix that is importance-ranked by their eigenvalues
	- They are combined forms of original dimensions in the dataset to reduce dimensions
