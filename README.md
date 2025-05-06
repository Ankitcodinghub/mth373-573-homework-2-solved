# mth373-573-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [MTH373-573 Homework 2 Solved](https://www.ankitcodinghub.com/product/mth373-573-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97988&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MTH373-573 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Problem1: ForwardSubstitutiononSteroids 8points

Suppose we are given a linear system 𝐴𝑥 = 𝑏, we say we can solve for 𝑥 without inverting 𝐴 when we mean we can use Gaussian elimination (with or without partial or full pivoting as appropriate) to compute 𝑥. For example, we can solve for 𝑦 = 𝐴−1𝐵𝑥 by first computing 𝑧 = 𝐵𝑥 and then solving for 𝑦 using 𝐴𝑦 = 𝑧. In case of triangular linear systems, such solution would involve use of forward and back substitutions.

Using this background, suppose you are given 𝐿, 𝐾 ∈ R𝑛×𝑛 which are both lower triangular matrices, and 𝐵 ∈ R𝑛×𝑛 any general matrix. Then, specify an algorithm for computing 𝑋 ∈ R𝑛×𝑛 so that 𝐿𝑋𝐾 = 𝐵.

Problem2: Gaussianeliminationandpartialpivoting 60 points

<ol>
<li>(a) &nbsp;WriteafunctiontoimplementGaussianeliminationwithnopivotingasinalgorithm1.(15
points)
</li>
<li>(b) &nbsp;WriteafunctiontoimplementGaussianeliminationwithpartialpivotingasinalgorithm2. (15 points)</li>
<li>(c) &nbsp;Testyourcode.Foreachoftheexamplesasstatedbelow,reportthevariousmeasurements as below in a table. Use relative measurements as necessary, and 2-norm for all appropriate norms and condition numbers. You can use functions available from NumPy or SciPy for</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
these purposes.

• The condition number (np.linalg.cond),

• the error from un-pivoted solve from your function in part (a),

• the residual from un-pivoted solve from your function in part (a),

• the error from partially-pivoted solve from your function in part (b),

• the residual from partially-pivoted solve from your function in part (b), • theerrorfromnp.linalg.solve,

• theresidualfromnp.linalg.solve.

</div>
<div class="column">
(30 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
Report if any of the solves fail. You should try to write your code so that it prints the above table automatically without user interaction.

For each matrix below, write 2 or 3 sentences on your observations with regard to condi- tioning, necessity of pivoting, and reasons for your observed results.

Use the following matrices of sizes 𝑛 = 10, 20, 30, 40 to test your code:

1. Arandommatrixofsize𝑛×𝑛withentriesuniformlysampledfrom[0,1)(usenp.random.randn). 2. The Hilbert matrix given by:

𝑎𝑖𝑗 = 1 (𝑖, 𝑗 = 1, … , 𝑛). 𝑖+𝑗−1

</div>
</div>
<div class="layoutArea">
<div class="column">
4/6

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
3. The matrix given by

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡1 ⋯ 1⎤

⎢−1 1 ⋯ 1⎥ 𝐴𝑛=⎢−1 −1 1 ⋯ 1⎥ ⎢⋮ ⋱ ⋮⎥ ⎣−1 −1 −1 ⋯ 1⎦

Foreachcase,let𝑥⋆=[1 ⋯ 1]𝑇 ∈R𝑛bethevectorofall1sofsize𝑛.Now,compute𝑏as the matrix-vector product 𝐴 𝑥 ⋆ and solve the linear system 𝐴 𝑥 = 𝑏.

Problem3: ScaledLinearSystems 5+5+2=12points

A matrix 𝐴 = [𝑎𝑖𝑗]𝑛×𝑛 is said to row equilibrated if it is scaled so that max|𝑎𝑖𝑗| = 1, 1 ≤ 𝑖 ≤ 𝑛. In

solving a system of equations 𝐴𝑥 = 𝑏, we can produce an equivalent system in which the matrix

is row equilibrated by dividing the 𝑖th equation by max |𝑎𝑖𝑗|. 1≤𝑗 ≤𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) Solve the system of equations:

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡1 1 2×109⎤⎡𝑥1⎤ ⎡1⎤ ⎢2 −1 109 ⎥ ⎢𝑥2⎥ = ⎢1⎥

⎣12 0⎦⎣𝑥3⎦⎣1⎦

</div>
</div>
<div class="layoutArea">
<div class="column">
by using Gaussian elimination with partial pivoting and the function you wrote for it in Problem 2.

<ol start="2">
<li>(b) &nbsp;Solve the same problem but now changing the linear system into a row equilibrated one and using Gaussian elimination without partial pivoting. You can reuse the function you wrote in Problem 2. Are the answers the same? Why or why not?</li>
<li>(c) &nbsp;State your reasoning for the why or why not part in 2 to 4 sentences.

The reasoning part is open ended and worth only 2 points. However, if you do not provide

an explanation for your observations, you will not get those 2 points.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5/6

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Submission Notes

<ol>
<li>Theanswertoalltheoreticalproblems,outputofPythoncodeforcomputationalproblems including figures, tables and accompanying analyses should be provided in a single PDF file along with all your code files.</li>
<li>Youcantypeset(pleaseconsiderusingLATEXifyouchoosetodoso),orwritebyhandand scan/take photographs of solutions for theoretical questions. For scanning or photography, please put in the extra effort and provide a single PDF file of your submission.</li>
<li>For Problem 2, submit your code in one file: problem_2.py. You can use the Python file provided as a boilerplate.</li>
<li>For Problem 3, submit your code in one file again: problem_3.py. You will of course, copy- paste the functions written in problem_2.py for Gaussian elimination without and with partial pivoting into this file.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
6/6

</div>
</div>
</div>
