# cs21001-assignment-1--propositional-logic---representation-and-deduction-solved
**TO GET THIS SOLUTION VISIT:** [CS21001 Assignment 1- Propositional Logic – Representation and Deduction Solved](https://www.ankitcodinghub.com/product/cs21001-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116659&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS21001 Assignment 1- Propositional Logic – Representation and Deduction  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
Coding Assignment 1 : Propositional Logic – Representation and Deduction

Notations:

Propositions. Boolean variables with True (⊤) and False (⊥) values

Literals. Propositions (p) or negated propositions (¬p)

Connectives. Binary operators (⋊⋉) such as, AND (∧), OR (∨), IMPLY (→) and IFF (↔) Propositional Formula. Recursively defined as, ϕ = p | (ϕ) | ¬ϕ | ϕ ⋊⋉ ϕ, where ⋊⋉∈ {∧,∨,→,↔}

Problem Statement:

Input. Propositional Formula (ϕ) as strings with propositions, negations, connectives and brackets, ‘(’ and ‘)’

Postfix Formula Representation. Propositional Formula (ϕ) as strings with propositions, negations, connectives in Postfix format (this will made available to you in code as a string for ready-made processing!)

Output. You will be asked to write separate functions for the following parts (in the already supplied code):

1. Represent the postfix propositional formula (ϕ) as a binary tree (τ) data structure, known as expression tree, which contains propositions as leaf nodes and operators {∧,∨,¬,→,↔} as internal nodes

4. Transformation of the formula step-wise (ϕ ϕI ϕN ϕC/ϕD) using the expression tree data structure (τ τI τN τC/τD) as follows:

(a) Implication-Free Form (IFF): Formula (ϕI) after elimination of → and ↔

(b) Negation Normal Form (NNF): Formula (ϕN) where ¬ appears only before propositions

(c) Conjunctive Normal Form (CNF): Formula (ϕC) with conjuction of disjunctive-clauses where each disjunctive-clause is a disjunction of literals

(d) Disjunctive Normal Form (DNF): Formula (ϕD) with disjuction of conjuctive-clauses where each conjunctive-clause is a conjunction of literals

(a) the validity (⊤) or the invalidity of the formula (whether it is a tautology or not), or

(b) the satisfiability or the unsatisfiability (⊥) of the formula (whether it is a contradiction or not)

Algorithms:

Expression Tree Formation. Let the generated postfix string from the propositional formula (ϕ) be PS[1..n]. The recursive function ETF, i.e. τ ← ETF(PS[1..n]), is as follows:

• If n = 1 (i.e. PS[1] is a proposition), then τ = CREATENODE(ϕ);

• If n &gt; 1 and PS[n] = ¬, then τ = CREATENODE(¬);τ →7 rightChild = ETF(PS[1..(n − 1)]);

• If n &gt; 2 and PS[n] =⋊⋉, then τ = CREATENODE(⋊⋉);τ 7→ leftChild = ETF(PS[1..(k − 1)]);τ →7 rightChild = ETF(PS[k..(n − 1)]);

• return τ;

Here, the primary question is – how to find k for the last step? (this will be explained to you!)

Printing Expression Tree. The recursive function ETP(τ) is as follows:

• If τ 7→ element is not NULL, then

PRINT (; ETP(τ 7→ leftChild); PRINT(τ 7→ element); ETP(τ →7 rightChild); PRINT ); Here, the PRINT subroutine displays the respective charater as output.

• If τ 7→ element is proposition pi, then return (vi = ⊤)? ⊤ : ⊥;

• If τ 7→ element is ¬, then return (EVAL(τ 7→ rightChild) = ⊤)? ⊥ : ⊤;

• If τ →7 element is ∧, then return EVAL(τ 7→ leftChild)∧ EVAL(τ 7→ rightChild);

• If τ →7 element is ∨, then return EVAL(τ 7→ leftChild)∨ EVAL(τ 7→ rightChild);

• If τ 7→ element is →, then return (EVAL(τ 7→ leftChild) = ⊤) and (EVAL(τ 7→ rightChild) = ;

• If τ 7→ element is ↔, then return ((EVAL(τ 7→ leftChild) = ⊤) and (EVAL(τ 7→ rightChild) = ⊤)) or ((EVAL(τ 7→ leftChild) = ⊥) and (EVAL(τ 7→ rightChild) = ;

IFF Transformation. The recursive function IFF, i.e. τI ← IFF(τ), is as follows:

• If τ 7→ element is ¬, then

/ ∗ IFF(¬ϕ) = ¬IFF(ϕ) ∗ /

• If τ 7→ element is {∧,∨}, then

/ ∗ IFF(ϕ1 ∧ ϕ2) = IFF(ϕ1) ∧ IFF(ϕ2) IFF(ϕ1 ∨ ϕ2) = IFF(ϕ1) ∨ IFF(ϕ2) ∗ /

• If τ 7→ element is →, then

/ ∗ IFF(ϕ1 → ϕ2) = ¬IFF(ϕ1) ∨ IFF(ϕ2) ∗ /

• If τ 7→ element is ↔, then

/ ∗ IFF(ϕ1 ↔ ϕ2) = IFF(ϕ1 → ϕ2) ∧ IFF(ϕ1 → ϕ2) ∗ /

• return τ;

Here, ϕI can be obtained (as a string expression) by calling ETP(τI).

NNF Transformation. The recursive function NNF, i.e. τN ← NNF(τI), is as follows:

• If τI 7→ element is ¬, then

– if (τI 7→ rightChild) 7→ element is ¬, then / ∗ NNF(¬¬ϕ) = NNF(ϕ) ∗ /

– if (τI 7→ rightChild) 7→ element is ∧, then

/ ∗ NNF(¬(ϕ1 ∧ ϕ2)) = ¬NNF(ϕ1) ∨ ¬NNF(ϕ2)

– if (τI 7→ rightChild) 7→ element is ∨, then ∗ /

/ ∗ NNF(¬(ϕ1 ∨ ϕ2)) = ¬NNF(ϕ1) ∧ ¬NNF(ϕ2) ∗ /

• If τI 7→ element is {∧,∨}, then

/ ∗ NNF(ϕ1 ∧ ϕ2) = NNF(ϕ1) ∧ NNF(ϕ2) NNF(ϕ1 ∨ ϕ2) = NNF(ϕ1) ∨ NNF(ϕ2) ∗ /

• return τI;

Here, ϕN can be obtained (as a string expression) by calling ETP(τN).

CNF Transformation. The recursive function CNF, i.e. τC ← CNF(τN), is as follows:

• If τN 7→ element is ∧, then

/ ∗ CNF(ϕ1 ∧ ϕ2) = CNF(ϕ1) ∧ CNF(ϕ2) ∗ /

• If τN 7→ element is ∨, then /* Distribution Law enforcement */

– if (τN 7→ leftChild) 7→ element is ∧, then

/ ∗ CNF((ϕ1l ∧ ϕ1r) ∨ ϕ2) = CNF(ϕ1l ∨ ϕ2) ∧ CNF(ϕ1r ∨ ϕ2) ∗ / – if (τN 7→ rightChild) 7→ element is ∧, then

/ ∗ CNF(ϕ1 ∨ (ϕ2l ∧ ϕ2r)) = CNF(ϕ1 ∨ ϕ2l) ∧ CNF(ϕ1 ∨ ϕ2r) ∗ /

• return τN;

Here, ϕC can be obtained (as a string expression) by calling ETP(τC). The subroutine DUPLICATE(τ) creates another exact replica of the expression tree rooted at τ.

DNF Transformation. The recursive function DNF, i.e. τD ← DNF(τN), is as follows:

• If τN 7→ element is ∨, then

/ ∗ DNF(ϕ1 ∨ ϕ2) = DNF(ϕ1) ∨ DNF(ϕ2) ∗ /

• If τN 7→ element is ∧, then /* Distribution Law enforcement */

– if (τN →7 leftChild) 7→ element is ∨, then

/ ∗ DNF((ϕ1l ∨ ϕ1r) ∧ ϕ2) = DNF(ϕ1l ∧ ϕ2) ∨ DNF(ϕ1r ∧ ϕ2) ∗ /

– if (τN 7→ rightChild) 7→ element is ∨, the

/ ∗ DNF(ϕ1 ∧ (ϕ2l ∨ ϕ2r)) = DNF(ϕ1 ∧ ϕ2l) ∨ DNF(ϕ1 ∧ ϕ2r) ∗ /

• return τN;

Here, ϕD can be obtained (as a string expression) by calling ETP(τD). The subroutine DUPLICATE(τ) creates another exact replica of the expression tree rooted at τ.

Exhaustive Search for Validity/Satisfibility. The function CHECK(τ) is as follows:

• For every value tuple {v1,v2,…,vn} corresponding to n propositions {p1,p2,…,pn}, if EVAL(τ,v1,v2,…,vn) = ⊤, then print “hVALID + SATISFIABLEi”

• For every value tuple corresponding to n propositions {p1,p2,…,pn}, if EVAL , then print “hINVALID + UNSATISFIABLEi”

• Otherwise, for any pair of value tuples {v1,v2,…,vn} and corresponding to n propositions {p1,p2,…,pn} such that, EVAL(τ,v1,v2,…,vn) = ⊤ and EVAL , then print “hSATISFIABLE+ INVALIDi”, for {v1,v2,…,vn} and , respectively

Example:

Input Propositional Formula. ϕ = (¬p ∧ q) → (p ∧ (r → q))

Postfix Formula Representation. p ¬ q ∧ p r q → ∧ → (YOUR INPUT STRING)

Expression Tree Formation. Depending on the recursive call, two types of parse tree (τ) can be formed. Figure 1 shows the representation of such expression trees.

Figure 1: Expression Tree Structure for Original Formula and the Corresponding CNF

Formula Evaluation. {p = ⊥,q = ⊤,r = ⊤} ⇒ ϕ = ⊥ ; {p = ⊥,q = ⊥,r = ⊥} ⇒ ϕ = ⊤

Formula Transformations. The path through which you shall be doing this is as follows:

ϕ PostFix τ (Print ϕ) τI (Print ϕI) τN (Print ϕN) τC/τD (Print ϕC/ϕD)

IFF : ϕI = IFF(ϕ) = IFF((¬p ∧ q) → (p ∧ (r → q))) = ··· = ¬(¬p ∧ q) ∨ (p ∧ (¬r ∨ q))

NNF : ϕN = NNF(ϕI) = NNF(¬(¬p ∧ q) ∨ (p ∧ (¬r ∨ q)))) = ··· = (p ∨ ¬q) ∨ (p ∧ (¬r ∨ q))

CNF : ϕC = CNF(ϕN) = CNF((p ∨ ¬q) ∨ (p ∧ (¬r ∨ q))) = ··· = (p ∨ ¬q ∨ p) ∧ (p ∨ ¬q ∨ ¬r ∨ q)

DNF : ϕD = DNF(ϕN)

Check for Validity/Satisfibility. = DNF((p ∨ ¬q) ∨ (p ∧ (¬r ∨ q))) = ··· = (p) ∨ (¬q) ∨ (p ∧ ¬r) ∨ (p ∧ q)

INVALID : {p = ⊥,q = ⊤,r = ×} (× denotes don′t care term)

SATISFIABLE : {p = ⊤,q = ×,r = ×} OR {p = ×,q = ⊥,r = ×}

Sample Execution:

Compile: (C Code) gcc ROLLNO_CT1.c − lm (Please follow the filename convention given!)

(C++ Code) g++ ROLLNO_CT1.cpp − lm (Please follow the filename convention given!)

Execution: ./a.out

Sample Run:

Enter Propositional Logic Formula: (!p &amp; q) -&gt; (p &amp; (r -&gt; q)) Postfix Representation of Formula: p ! q &amp; p r q -&gt; &amp; -&gt;

++++ PostFix Format of the Propositional Formula ++++

(’-’ used for ’-&gt;’ and ’~’ used for ’&lt;-&gt;’) YOUR INPUT STRING: p!q&amp;prq-&amp;-

++++ Expression Tree Generation ++++

Original Formula (from Expression Tree): ( ( ! p &amp; q ) -&gt; ( p &amp; ( r -&gt; q ) ) )

++++ Expression Tree Evaluation ++++

Enter Total Number of Propositions: 3

Enter Proposition [1] (Format: Name &lt;SPACE&gt; Value): p 0

Enter Proposition [2] (Format: Name &lt;SPACE&gt; Value): q 1

Enter Proposition [3] (Format: Name &lt;SPACE&gt; Value): r 1

The Formula is Evaluated as: False

++++ IFF Expression Tree Conversion ++++

Formula in Implication Free Form (IFF from Expression Tree):

( ! ( ! p &amp; q ) | ( p &amp; ( ! r | q ) ) )

++++ NNF Expression Tree Conversion ++++

Formula in Negation Normal Form (NNF from Expression Tree):

( ( p | ! q ) | ( p &amp; ( ! r | q ) ) )

++++ CNF Expression Tree Conversion ++++

Formula in Conjunctive Normal Form (CNF from Expression Tree):

( ( ( p | ! q ) | p ) &amp; ( ( p | ! q ) | ( ! r | q ) ) )

++++ DNF Expression Tree Conversion ++++

Formula in Disjunctive Normal Form (DNF from Expression Tree):

( ( p | ! q ) | ( ( p &amp; ! r ) | ( p &amp; q ) ) )

++++ Exhaustive Search from Expression Tree for Validity / Satisfiability Checking ++++

Enter Number of Propositions: 3

Enter Proposition Names (&lt;SPACE&gt; Separated): p q r Evaluations of the Formula:

{ (p = 0) (q = 0) (r = 0) } : 1

{ (p = 0) (q = 0) (r = 1) } : 1

{ (p = 0) (q = 1) (r = 0) } : 0

{ (p = 0) (q = 1) (r = 1) } : 0

{ (p = 1) (q = 0) (r = 0) } : 1

{ (p = 1) (q = 0) (r = 1) } : 1

{ (p = 1) (q = 1) (r = 0) } : 1

{ (p = 1) (q = 1) (r = 1) } : 1

The Given Formula is: &lt; INVALID + SATISFIABLE &gt;

Submit a single C/C++ source file following proper naming convention [ ROLLNO_CT1.c(.cpp) ]. Do not use any global/static variables. Use of STL is allowed.
