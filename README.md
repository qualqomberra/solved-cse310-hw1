Download Link: https://assignmentchef.com/product/solved-cse310-hw1
<br>
<strong>Introduction: </strong>Objective of this homework is for you to get familiar with and reinforce algorithm analysis techniques discussed in the class including O, Ω, and Θ notation as well as algorithm design using divide and conquer.

<strong>Requirements</strong>:

<ol>

 <li><strong> [15 Pts]</strong> Algorithm Analysis: Study the following sorting algorithm.</li>

</ol>

SORT (A)     // Assume there are <em>n</em> elements in A

<ul>

 <li><strong>for </strong>i = 0 <strong>to </strong><em>n</em> – 1</li>

 <li>k = i + 1</li>

 <li><strong>for </strong>j = i + 2 <strong>to </strong><em>n</em></li>

 <li><strong>if </strong>A[k] &gt; A[j]</li>

 <li>k = j</li>

 <li><strong>if </strong>k ≠ i + 1</li>

 <li>temp = A[i + 1]</li>

 <li>A[i + 1] = A[k]</li>

 <li>A[k] = temp</li>

</ul>

<ul>

 <li>(10 pts) Use the longer approach described in the lecture <strong>CSE360_1_L1_Part3</strong> week 1 that we used in analyzing Insertion-Sort to compute the running time <em>T</em>(<em>n</em>) of the above SORT algorithm. You may need to define variable such as <em>t<sub>i</sub> </em>or <em>t<sub>j</sub></em>, similar to the variable <em>t<sub>j</sub></em> we used in the lecture.</li>

 <li>(5 pts) Determine the worst case running time and the best case running time as a function of functions of <em>n</em>.</li>

</ul>






















<strong>2.[35 Pts]</strong> Asymptotic Notation and Mathematical Induction: Use the definition of O, Ω, and Θ notation to prove that




<ol>

 <li>(<em>5 points</em>) Let <em>f</em>(<em>n</em>) = 0.02<em>n</em><sup>2</sup> + 20<em>n</em>. Show that <em>f</em>(<em>n</em>) = Θ(<em>n</em><sup>2</sup>).</li>

 <li>(<em>5 points</em>) Let <em>f</em>(<em>n</em>) = Θ(<em>n</em><sup>2</sup>) and <em>g</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>2</sup>). Show that <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) = Θ(<em>n</em><sup>2</sup>).</li>

 <li>(1<em>5 points</em>) f(n) = 6n2 + 7n + 5 =&gt; O(n2), f(n)= 6n2  + 7n + 5 =&gt; Ω(n2) and f(n)= 6n2  + 7n + 5   =&gt; Θ(n2)</li>

 <li>(<em>10 points</em>) Using mathematical induction to prove</li>

</ol>

<sup></sup><em>k</em><em><sup>n</sup></em>1<em>k</em>2 <em>n</em>(<em>n</em>1)(<sub>6</sub>2<em>n</em>1)




<h1>Algorithm Design Questions</h1>

<ol start="3">

 <li><strong>3</strong>. <strong>[10 Pts]</strong> Use recursion to solve following problem. Then determine the running time Powering of a number: For a give number X and an integer n &gt;= 0, compute</li>

</ol>

X<sup>n</sup>

Normally, we would multiply X, n times. However that will give is O(n)  time. How do we do this calculation better using recursion (i.e, using recursion) ? Write down your algorithm and prove that its time complexity is better then O(n)




<strong>4.[15 Pts]</strong> Suppose you are given a set of cities (p number of cities) and there longitude and latitude coordinates. You need to determine the two closest cities. Write an algorithm that uses Divide and Conquer approach to determine the two closest cities. Assume that the subroutine GET_DISTANCE(s, d)  takes the longitude and latitude values of s and d and returns the distance between s and d. Using the same method you have applied in question 2 above determine the running time of your algorithm

<strong> </strong>

<h1>Submission</h1>

<ol>

 <li>a) For questions, 1-4, submit a PDF file containing your answers. Answers can be handwritten (make sure answers are readable) and scanned as PDF. Submit online to the canvas</li>

</ol>


