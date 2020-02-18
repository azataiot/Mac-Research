[TOC]

Data science and machine learning requires a certain mathematical foundation, but if you only use it for engineering, and if you don't have much time, you don't have to learn it too much too depth. You have to understand the basic formula, and then learn the certain topic if you have problems.

## Advanced mathematics

### 1. Definition of derivation

Concept of derivative and defferential

$f'({{x}_{0}})=\underset{\Delta x\to 0}{\mathop{\lim }}\,\frac{f({{x}_{0}}+\Delta x)-f({{x}_{0}})}{\Delta x}$    （1）

Or:

$f'({{x}_{0}})=\underset{x\to {{x}_{0}}}{\mathop{\lim }}\,\frac{f(x)-f({{x}_{0}})}{x-{{x}_{0}}}$      （2）

### 2. The geometric meaning and physical meaning of the left and right derivatives

The left and right derivatives of the function $f(x)$ at $x_0$ are defined as:

Left derivative：${{{f}'}_{-}}({{x}_{0}})=\underset{\Delta x\to {{0}^{-}}}{\mathop{\lim }}\,\frac{f({{x}_{0}}+\Delta x)-f({{x}_{0}})}{\Delta x}=\underset{x\to x_{0}^{-}}{\mathop{\lim }}\,\frac{f(x)-f({{x}_{0}})}{x-{{x}_{0}}},(x={{x}_{0}}+\Delta x)$



Right derivative：${{{f}'}_{+}}({{x}_{0}})=\underset{\Delta x\to {{0}^{+}}}{\mathop{\lim }}\,\frac{f({{x}_{0}}+\Delta x)-f({{x}_{0}})}{\Delta x}=\underset{x\to x_{0}^{+}}{\mathop{\lim }}\,\frac{f(x)-f({{x}_{0}})}{x-{{x}_{0}}}$

### 3. The relationship between the conductability and continuity of a function

**Th1:** the function $f(x)$ can be differentiated at $x_0$$\Leftrightarrow f(x)$ can be derived at $x_0$

**Th2:** If the function is derivable at point $x_0$，Then $y=f(x)$ is continuous at point $x_0$，Otherwise, it is not established.That is, the function continuation does not necessarily have a derivative.

**Th3:** ${f}'({{x}_{0}})$ exists$\Leftrightarrow {{{f}'}_{-}}({{x}_{0}})={{{f}'}_{+}}({{x}_{0}})$

### 4. Tangent and normal of the plane curve

Tangent equation : $y-{{y}_{0}}=f'({{x}_{0}})(x-{{x}_{0}})$

Normal equation：$y-{{y}_{0}}=-\frac{1}{f'({{x}_{0}})}(x-{{x}_{0}}),f'({{x}_{0}})\ne 0$

### 5. Four arithmetic rules

Suppose the function $u=u(x), v=v(x)$] is derivable at the point $x$ then:

(1) $(u\pm v{)}'={u}'\pm {v}'$    $d(u\pm v)=du\pm dv$

(2)$(uv{)}'=u{v}'+v{u}'$    $d(uv)=udv+vdu$

(3) $(\frac{u}{v}{)}'=\frac{v{u}'-u{v}'}{{{v}^{2}}}(v\ne 0)$    $d(\frac{u}{v})=\frac{vdu-udv}{{{v}^{2}}}$

### 6. Basic derivative and differential table

(1) $y=c$（constant）    ${y}'=0$     $dy=0$

(2) $y={{x}^{\alpha }}$($\alpha $ is a real number)  ${y}'=\alpha {{x}^{\alpha -1}}$   $dy=\alpha {{x}^{\alpha -1}}dx$

(3) $y={{a}^{x}}$   ${y}'={{a}^{x}}\ln a$     $dy={{a}^{x}}\ln adx$

 special case:  $({{{e}}^{x}}{)}'={{{e}}^{x}}$       $d({{{e}}^{x}})={{{e}}^{x}}dx$

(4) $y={{\log }_{a}}x$  ${y}'=\frac{1}{x\ln a}$      

$dy=\frac{1}{x\ln a}dx$

 special case:$y=\ln x$           $(\ln x{)}'=\frac{1}{x}$    $d(\ln x)=\frac{1}{x}dx$

(5) $y=\sin x$     

${y}'=\cos x$    $d(\sin x)=\cos xdx$

(6) $y=\cos x$    

${y}'=-\sin x$    $d(\cos x)=-\sin xdx$

(7) $y=\tan x$  

${y}'=\frac{1}{{{\cos }^{2}}x}={{\sec }^{2}}x$ $d(\tan x)={{\sec }^{2}}xdx$

(8) $y=\cot x$ ${y}'=-\frac{1}{{{\sin }^{2}}x}=-{{\csc }^{2}}x$ $d(\cot x)=-{{\csc }^{2}}xdx$

(9) $y=\sec x$ ${y}'=\sec x\tan x$   

 $d(\sec x)=\sec x\tan xdx$

(10) $y=\csc x$ ${y}'=-\csc x\cot x$   

$d(\csc x)=-\csc x\cot xdx$

(11) $y=\arcsin x$  

${y}'=\frac{1}{\sqrt{1-{{x}^{2}}}}$  

$d(\arcsin x)=\frac{1}{\sqrt{1-{{x}^{2}}}}dx$

(12) $y=\arccos x$ 

${y}'=-\frac{1}{\sqrt{1-{{x}^{2}}}}$   $d(\arccos x)=-\frac{1}{\sqrt{1-{{x}^{2}}}}dx$

(13) $y=\arctan x$ 

${y}'=\frac{1}{1+{{x}^{2}}}$   $d(\arctan x)=\frac{1}{1+{{x}^{2}}}dx$

(14) $y=\operatorname{arc}\cot x$    

${y}'=-\frac{1}{1+{{x}^{2}}}$  

$d(\operatorname{arc}\cot x)=-\frac{1}{1+{{x}^{2}}}dx$

(15) $y=shx$   

${y}'=chx$    $d(shx)=chxdx$

(16) $y=chx$   

${y}'=shx$    $d(chx)=shxdx$

### 7. The differential method of functions determined by composite functions, inverse functions, implicit functions and parametric equations

(1) The algorithm for the inverse function: Let $y=f(x)$ be monotonously continuous in a neighborhood of point $x$, and can be derivatived at point $x$ and ${f}'(x)\ne 0 $, then its inverse function is derivable at $y$ corresponding to point $x$, and there is $\frac{dy}{dx}=\frac{1}{\frac{dx}{dy}}$

(2) The algorithm for the compound function: If $\mu =\varphi (x)$ can be derived at the point $x$, and $y=f(\mu )$ is at the corresponding point $\mu $($\mu =\varphi (x)$) can be a derivative, then the composite function $y=f(\varphi (x))$ can be a derivative at point $x$, and ${y}'={f}'(\mu )\ Cdot {\varphi }'(x)$

(3) There are generally three ways to find the implicit function derivative $\frac{dy}{dx}$:

1) The equations on both sides of the $x$ derivation, you need to remember that $y$ is a $x$ function, then the $y$ function is a composite function of $x$. For example $\frac{1}{y}$, ${{y}^{2}}$, $ln y$, ${{{e}}^{y}}$, etc. are all composite functions of $x$.
The derivation of $x$ should be done according to the compound function linkage rule.

2) Formula method. Known by $F(x,y)=0$ ，$\frac{dy}{dx}=-\frac{{{{{F}'}}_{x}}(x,y)}{{{{{F}'}}_{y}}(x,y)}$ where ${{{F}'}_{x}}(x,y)$,
${{{F}'}_{y}}(x,y)$ represents the partial derivative of $F(x,y)$ to $x$ and $y$, respectively.

3) Using differential form invariance

### 8. Commonly used Higher derivative formula

（1）$({{a}^{x}}){{\,}^{(n)}}={{a}^{x}}{{\ln }^{n}}a\quad (a>{0})\quad \quad ({{{e}}^{x}}){{\,}^{(n)}}={e}{{\,}^{x}}$

（2）$(\sin kx{)}{{\,}^{(n)}}={{k}^{n}}\sin (kx+n\cdot \frac{\pi }{{2}})$

（3）$(\cos kx{)}{{\,}^{(n)}}={{k}^{n}}\cos (kx+n\cdot \frac{\pi }{{2}})$

（4）$({{x}^{m}}){{\,}^{(n)}}=m(m-1)\cdots (m-n+1){{x}^{m-n}}$

（5）$(\ln x){{\,}^{(n)}}={{(-{1})}^{(n-{1})}}\frac{(n-{1})!}{{{x}^{n}}}$

（6）Leibniz formula：if $ u(x)\,,v(x)$ Both $n$ th can be derivative，then

 ${{(uv)}^{(n)}}=\sum\limits_{i={0}}^{n}{c_{n}^{i}{{u}^{(i)}}{{v}^{(n-i)}}}$，among them ${{u}^{({0})}}=u$，${{v}^{({0})}}=v$

