# IFT2035_TP2
<div>
<b> Course </b>: IFT2035 - Introduction to Programming Language <br>
<b> Professor </b>: Stefan Monnier  <br>
<b> Language used:</b> Prolog and LaTEX for report <br>
</div>

# Description (Exceprt from upts.pdf)

In this homework, you are going to write a program in Prolog that will manipulate the expression of an abstract syntax tree for a little <img src="https://render.githubusercontent.com/render/math?math=\lambda">-calculus called <img src="https://render.githubusercontent.com/render/math?math=\mu">PTS
(The name came from the fact that it is a type of Pure Type System, close to System U). The particularities of <img src="https://render.githubusercontent.com/render/math?math=\mu">PTS is that it is a mix of normal expressions and types.
As a result, in this language, the types have "normal" values (We can also say the values are of "first class") that we can pass them as arguments, return them back as results, or stock them in a data structure.
A way to represent this fact is to say <code>type:type</code>; the same that <code> int </code> is the type of whole numbers, <code> type </code> is the type of the types, so <code> 42 : int </code> and <code> int : type </code>
and because <code> type </code> itself is also a type so we have <code> type : type </code> <br> <br>
Therefore, the syntax of the language does not distinguish the sub-language of the types: The two are considered the same. More precisely, the heart of the language has the following syntax, it is valid for the types and also for "normal" expression
<center>
 <img src="https://render.githubusercontent.com/render/math?math=e ::= c \: | \: x \: | \: \lambda x:e_1.e_2 \: |\:  e_1e_2 \: |\: \Pi x: e_1. e_2 \: |\: \text{let }\: x = e_1 = e_2 \: \text{ in } \: e_3 ">
</center>

<b> For more details regarding the specification of the language, please consult <code> upts.pdf</code> located in this repo.</b>

