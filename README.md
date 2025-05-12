# eecs2011-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EECS2011 Assignment 2 Solved](https://www.ankitcodinghub.com/product/eecs2011-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91337&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS2011 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Assignment Objectives: This assignment consists of three problems and is designed to let you exercise on the following concepts related to Lecture Slides 3, 4, 5, and 6.

 Problem 1:

o Recursion: As a beginner, we tend to mentally trace the steps of a process iteratively

(step 1, then step 2, then step 3, …). But to become a competent algorist we also need to be adept at a higher level of abstract mental process, namely, thinking recursively. There is a close connection between that process and mathematical induction. Induction is also applicable to iterative loops (e.g., Loop Invariant). So, we need to be good at induction too.

o Analysis of recursive algorithms by mathematical induction.

 Problem 2:

o From abstract to concrete: How to implement an ADT by a suitable concrete data

structure that supports operations defined in the ADT, and satisfies a given set of additional specifications, restrictions, and resource requirements.

 Problem 3:

o Developing apps: How to select and effectively use suitable data structures to solve

an application problem. In this assignment we want to see how to make effective use of linear data structures such as stacks in parsing expressions and related problems.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 1:

Imagine a row of n lights , numbered 1 to n, that can be turned on or off only under certain conditions as follows. The first light can be turned on or off anytime. Each of the other lights can be turned on or off only when the preceding light is on and all other lights before it are off. If all the lights are on initially, how can you turn them all off? For three lights numbered 1 to 3, you can take the following steps, where 1 indicates a light that is ON and 0 indicates OFF:

111 3 lights ON initially 011 Turn OFF light 1 010 Turn OFF light 3 110 Turn ON light 1 100 Turn OFF light 2 000 Turn OFF light 1

We can solve this problem by indirect recursion using the two methods turnOff() and turnOn() that mutually call each other. The algorithm in pseudo-code for turnOff(n) is shown below:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Algorithm turnOff( n )

</div>
</div>
<div class="layoutArea">
<div class="column">
// Pre-Condition:

// Post-Condition: 1. if ( n = 1 ) then 2. else{ //n2

</div>
<div class="column">
Lights 1 .. n are all currently on. Lights 1 .. n are all turned off.

Turn OFF light 1

</div>
</div>
<div class="layoutArea">
<div class="column">
3.

4.

5.

6.

7. } end

</div>
<div class="column">
if ( n &gt; 2 ) then turnOff( n – 2 ) Turn OFF light n

if(n&gt;2)then turnOn(n–2) trunOff( n – 1 )

// trunOff

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>a) &nbsp;Write a similar algorithm in pseudo-code for turnOn(n).</li>
<li>b) &nbsp;Implement these algorithms in Java. Use the results in a program to display the sequence of
steps to turn off n lights that are initially on. Show the output for a few values of n. The output

format should be similar to the 3-lights example shown above.
</li>
<li>c) &nbsp;Obtain, with sufficient explanation, an accurate estimate of the number of times lights are
turned off or on during the entire process. Express the answer as a function of n.
</li>
<li>d) &nbsp;Combine the two algorithms turnOff(n) and turnOn(n) and replace them with a single recursive
two parameter algorithm flipSwitches(n, s) written in pseudo-code. The boolean parameter s indicates which version is intended: switching n lights ON or OFF.

[Note: turnOff() and turnOn() methods should no longer be used/invoked in your new algorithm  use only FlipSwitches() instead.]
</li>
</ol>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 2:

Give a Java implementation of the deque ADT (see [GTG §6.3] for definition) using two stacks as the only instance variables. What are the running times of the methods?

[Note: For the two instance variables you may use the Stack&lt;E&gt; class from the Java Standard Library, but you are only allowed to use its “pure” stack methods (see LS6, p. 5) and NOT the extra non-stack members such as those inherited from elsewhere.]

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 3:

An expression with binary operators can be expressed unambiguously as a fully parenthesized infix expression (FPIE) , or un-parenthesized postfix expression (UPPE).

A FPIE exp is either an operand, or of the form ( exp1 op exp2 ) , where exp1 and exp2 are FPIEs and op is a binary operator. The same expression as UPPE is either the said operand or of the form exp’1 exp’2 op , where exp’1 and exp’2 are UPPE equivalents of exp1 and exp2 , respectively. Here is an illustrative example:

((a + 20)/((b – c)*(53.4 – d))) asFPIE,

a20+bc – 53.4d –*/ asequivalentUPPE.

Another way the same expression can be expressed unambiguously is the FPIE but with all left parentheses removed, i.e., we use only right parentheses. Let’s call this version as right parenthesized infix expression (RPIE). The above example expression is:

a + 20)/b – c)*53.4 – d))) asequivalentRPIE.

Write a Java program that takes from the standard input a valid RPIE and outputs the equivalent FPIE and UPPE.

Note:

<ul>
<li>Conversion from a FPIE to its equivalent RPIE is trivial: simply remove all left parentheses. However, the reverse conversion is interesting and non-trivial.</li>
<li>An input string may include blank spaces, (right) parentheses, operands, and the four arithmetic operators +, –, *, / . Any character other than blank spaces, operators, and (right) parentheses will be assumed as part of an operand. Operands may be any numeric constants or variable identifiers but are not syntactically checked. Not withstanding that, IllegalArgumentException may be thrown if the input does not represent a valid RPIE.</li>
</ul>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>&nbsp;</li>
</ul>
</div>
</div>
</div>
</div>
