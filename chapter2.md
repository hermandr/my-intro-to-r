---
title       : Introduction
description : History of R


--- type:NormalExercise lang:r xp:100 skills:1 key:f61268c9d1

##R is a programming language for statistical computing

"Quirky, flawed, and an enormous success"

<li>Pros

<ul>
<li>"The best thing about R is that it was written by statisticians, …" — Bo Gowgill, Google</li>
<li>Free and open source</li>
<li>Packages/Libraries for anything</li>
<li>Community support + Commercial development</li>
</ul></li>

<li>Cons

<ul>
<li>"…, the worst thing about R is that it was written by statisticians." — Bo Gowgill, Google</li>
<li>Steep learning curve (<a href="http://www.burns-stat.com/documents/books/the-r-inferno/" title="">The R Inferno</a>)</li>
<li>Speed (particularly, skill dependent, or when on Windows)</li>
</ul></li>

<li>Francois Pinard: "Using R is a bit akin to smoking"

<ul>
<li>"The beginning is difficult, one may get headaches and even gag the first few times."</li>
<li>"But in the long run, it becomes pleasurable and even addictive."</li>
<li>"Yet, deep down, for those willing to be honest, there is something not fully healthy in it."</li>
</ul></li>
<li>Alternatives: Python, Julia</li>
</ul>


--- type:NormalExercise lang:r xp:100 skills:1 key:633a354302

##Assignment operator

Download a copy of R Reference Card at <a href="http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf" title="">http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf</a>

Assignment: <- (= is also ok but not recommended)

<pre class="prettyprint lang-r"><span class="pln">x </span><span class="pun">&lt;-</span><span class="pln"> </span><span class="lit">5</span><span class="pln">      </span><span class="com"># assign value 5 to variable x; NO space between &lt; and -</span><span class="pln">
x           </span><span class="com"># inspect variable x</span></pre>

<pre>## [1] 5</pre></li>

*** =instructions
- Assign the value 91 to the variable x

*** =hint
- use the assignment operator <-

*** =pre_exercise_code
```{r}
```

*** =sample_code
```{r}
# Assign the value 91 to variable x


```

*** =solution
```{r}
# Assign the value 91 to variable x
x <- 91

```

*** =sct
```{r}
```

--- type:NormalExercise lang:r xp:100 skills:1 key:c6a196ffaa
##Arithmetic operators

Arithmetic operators: +, -, *, /, ^, %% (modulus), %/% (integer divide)

<pre class="prettyprint lang-r"><span class="lit">2</span><span class="pun">^</span><span class="lit">0.5</span><span class="pln">       </span><span class="com"># square root of 2</span></pre>

<pre>## [1] 1.414214</pre>

<pre class="prettyprint lang-r"><span class="pln">x </span><span class="pun">%%</span><span class="pln"> </span><span class="lit">3</span><span class="pln">      </span><span class="com"># 5 mod 3</span></pre>

<pre>## [1] 2</pre>

*** =instructions
- Calculate 5 * 3
- Calculate 12 / 7
- Assign the result of 11 modulus 3 to variable y

*** =hint
- use the assignment operator <-

*** =pre_exercise_code
```{r}
```

*** =sample_code
```{r}
# Calculate 5 * 3

# Calculate 12 / 7

# Assign the result of 11 modulus 3 to variable y


```

*** =solution
```{r}
# Calculate 5 * 3
5 * 3
# Calculate 12 / 7
12/7
# Assign the result of 11 modulus 3 to variable y
y <- 11 %% 3

```

*** =sct
```{r}
```
