---
demo presentation:

title: Demo  

theme: serif
css: css/custom.css

center: false
---

<h1> Title </h1>

<h2>Your name </h2>

<h6> Department of XYZ </h6>
<h6> University of ABC </h6>


---

# Introduction

----

Here's a list of items: 

* Item 1
* Item 2

---
# Section 2

----

### Slide 2.2

You can include $\LaTeX$ either inline $x=3$ or 

$$\int_{-\infty}^{\infty} \frac{1}{x^2+1}d x=\pi$$ 


----

### Slide 2.3

You can also include code snippets 

```julia
using Plots 

plot(sin,-2,2)
```

----

### Slide 2.4


<div class="container">
<div class="col">

<small>
You can also split the slide into two or more columns using 

```
<div class="container">
<div class="col">`

</div>

<div class="col">`

</div>
</div>

```

</small>
</div> 

<div class="col">

<img src="static/peaks.png" width="100%">

</div>


----

You can include theorems  

<div class="theorem">
  <div class="theorem-title">Theorem 1</div>
  <div class="theorem-content">
    Let \( a, b \in \mathbb{R} \). If \( a^2 = b^2 \), then \( a = b \) or \( a = -b \).
  </div>
</div>




<div class="theorem">
  <div class="theorem-title">Theorem 2 (Euclid)</div>
  <div class="theorem-content">
   There are infinitely many primes. 
  </div>
</div>

---

# Section 3