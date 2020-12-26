---
# Page title
title: Introduction of Chapter 2

# Title for the menu link if you wish to use a shorter link title, otherwise remove this option
linktitle: "2.1 Introduction"

# Page summary for search engine
summary: Blah, blah, blah

# Date page published
date: 2020-12-23

# Academic page type (do not modify)

type: book

# Position of this page in the menu. Remove this option to sort alphabetically
weight: 1
---

This is written for example page 1 of first chapter/lecture of machine learning course.


## Heading of section 1


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. 

If you pay attention you can learn more. This is an example of markdown callout.
{{% callout note %}}
A Markdown callout is useful for displaying notices, hints, or definitions to your readers.
{{% /callout %}}

Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Alternatively, a warning can be displayed to the reader using the warning option:

{{% callout warning %}}
Here's some important information...
{{% /callout %}}

## Another heading

Nullam vel molestie justo. Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

## Some Mathematics

$$x^2 + y^2 = r^2$$ is the equation of a circle centered at $(0,0)$ with radius $r$.

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. 


Now the input matrix $\bf{\hat{X}}$ can be written as
$$
\begin{eqnarray}
\bf{\hat{X}} & = & \begin{bmatrix}
1 & x_1 & x_1^2 & x_1^3 \\\\
1 & x_2 & x_2^2 & x_2^3 \\\\
\vdots & \vdots & \vdots & \vdots \\\\
1 & x_n & x_n^2 & x_n^3 \\\\
\end{bmatrix} \nonumber \\\\
& = & \begin{bmatrix}
\hat{x}_0^{(1)} & \hat{x}_1^{(1)} & \hat{x}_2^{(1)} & \hat{x}_3^{(1)}  \\\\
\hat{x}_0^{(2)} & \hat{x}_1^{(2)} & \hat{x}_2^{(2)} & \hat{x}_3^{(2)}  \\\\
\vdots & \vdots & \vdots & \vdots \\\\
\hat{x}_0^{(n)} & \hat{x}_1^{(2)} & \hat{x}_2^{(n)} & \hat{x}_3^{(n)}  \\\\
\end{bmatrix} = \begin{bmatrix}
\text{--} \left(x^{(1)} \right)^T \text{--}\\\\
\text{--} \left(x^{(2)} \right)^T \text{--}\\\\
\vdots \\\\
\text{--} \left(x^{(n)} \right)^T \text{--}\\\\
\end{bmatrix}
\end{eqnarray}
$$


Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

## Math example from wowchemy site

$$\gamma_{n} = \frac{ 
\left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T 
\left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}
{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.
 
## Tables

| Command           | Description                    |
| ------------------| ------------------------------ |
| `hugo`            | Build your website.            |
| `hugo serve -w`   | View your website.             |


| $i$        | $1$      | $x$     | $x^2$   | $x^3$      | $y$       |
|------------|----------|---------|---------|------------|-----------|
| $1$        | $1$      | $x_1$   | $x_1^2$ |  $x_1^3$   | $y^{(1)}$ |
| $1$        | $1$      | $x_2$   | $x_2^2$ |  $x_2^3$   | $y^{(2)}$ |
| $1$        | $1$      | $x_3$   | $x_3^2$ |  $x_3^3$   | $y^{(3)}$ |
| $\vdots$   | $\vdots$ | $\vdots$| $\vdots$|  $\vdots$  | $\vdots$  |
| $1$        | $1$      | $x_n$   | $x_n^2$ |  $x_n^3$   | $y^{(n)}$ |

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. 