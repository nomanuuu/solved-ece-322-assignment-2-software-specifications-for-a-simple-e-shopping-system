Download Link: https://assignmentchef.com/product/solved-ece-322-assignment-2-software-specifications-for-a-simple-e-shopping-system
<br>
<strong>1. </strong>Develop software specifications for a simple e-shopping system using the formalism of finite state machines. Consider some selected functionality. Make appropriate assumptions.

<u>Note</u>: there could be a variety of possible solutions; there is nothing wrong about that.  Your answer will be evaluated on a basis of its completeness and correctness (taking into consideration the assumptions you have made).

<em> </em><strong>2</strong>.Suggest a collection of test cases to test a procedure finding a maximum of three integer numbers

maxofThreeNumbers(int n1, int n2, int n3)

Consider (i) exhaustive testing and (ii) error guessing.

<strong>3</strong>.(i) Suppose that an application has <em>n</em> inputs (variables) and each variable partitions its input space in <em>m</em> equivalence classes. Determine the number of equivalence classes. How many tests do you require. Could be the number of tests made lower? Do detailed calculations for <em>n </em>=10 and <em>m</em> =10.

<ul>

 <li>a system invokes function <em>S</em> if the reading of a given sensor is within the [<em>a, b</em>] or [<em>c, d</em>], <em>b &lt;c</em>. The entire range of possible values is [-50, 50]. Identify equivalence classes. List a collection of tests.</li>

 <li>generalize the problem in (ii) by considering that there are two sensors where the function is invoked for the sensors’ readings are in [<em>a<sub>i</sub>, b<sub>i</sub></em>] or [<em>c<sub>i</sub>, d<sub>i</sub></em>], <em>b<sub>i</sub> &lt;c<sub>i</sub></em>, <em>i</em>=1, 2. How many test cases do you require here.                                                                                          <strong>4</strong>. Consider a 3-dimensional input domain described as</li>

</ul>

<h1><em>W</em> = [0, 10] × [-5, 20] × [0, 7]</h1>

(viz. there are 3 input variables assuming values in the corresponding intervals). In this domain there are three equivalence classes

<em>W</em><sub>1</sub>= {(<em>x, y, z</em>) | max (|<em>x</em>-1|, |<em>y</em>-1|, |<em>z</em>-1|) ≤ <em>e</em>}

1 of 2 <em>W</em><sub>2</sub>= {(<em>x, y, z</em>) | max (|<em>x</em>-5|, |<em>y</em>-10|, |<em>z</em>-4|) ≤ <em>e</em>}

<h2>W<sub>3</sub> = W-W<sub>1</sub>-W<sub>2</sub></h2>

where <em>e</em> is a certain positive number. What should be possible values of <em>e</em> so that these equivalence classes form a partition?





