---
keywords: fastai
description: Focus on Ifs, Switch, Expressions and how to build control structures in Java
title: Boolean Expressions and If Statements
toc: true
categories: [units]
image: /images/boolean.png
permalink: /unit/3
type: ap
week: 3
nb_path: _notebooks/2022-09-05-AP-boolean_ifs.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-05-AP-boolean_ifs.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Expression,-Assignments,-and-Condition-Statements">Expression, Assignments, and Condition Statements<a class="anchor-link" href="#Expression,-Assignments,-and-Condition-Statements"> </a></h2><p>All of the Units have video series.  We have access to information and content for College Board and Code.org.  Below are two sample videos, it is up to you to determine the detail or brevity that you will need according to your experience.</p>
<ul>
<li>AP Classroom <a href="https://apclassroom.collegeboard.org/8/home?apd=5kbsvu3q3p&amp;unit=3">Boolean Expressions</a></li>
<li>Code.org <a href="https://www.youtube.com/watch?v=2rQmLwYVYpw">If and Conditions</a>, less than 2 minutes</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Introduction-to-Boolean-expression">Introduction to Boolean expression<a class="anchor-link" href="#Introduction-to-Boolean-expression"> </a></h3><p>A Boolean expression is a logical statement that can be evaluated to True or False.  A Boolean expression may be composed of a combination of the Boolean constants true or false.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="c1">// All of the boolean expressions below evaluate to true</span>

<span class="k">if</span> <span class="p">(</span><span class="kc">true</span><span class="p">)</span> <span class="p">{</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;True code block&quot;</span><span class="p">);</span>
<span class="p">}</span>

<span class="k">if</span> <span class="p">(</span><span class="kc">true</span> <span class="o">&amp;&amp;</span> <span class="o">!</span><span class="kc">false</span><span class="p">)</span> <span class="p">{</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;True and Not False code block&quot;</span><span class="p">);</span>
<span class="p">}</span>

<span class="k">if</span> <span class="p">(</span><span class="kc">true</span> <span class="o">||</span> <span class="kc">false</span><span class="p">)</span> <span class="p">{</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;True or False code block&quot;</span><span class="p">);</span>
<span class="p">}</span>

<span class="k">if</span> <span class="p">((</span><span class="kc">true</span> <span class="o">&amp;&amp;</span> <span class="o">!</span><span class="kc">false</span><span class="p">)</span> <span class="o">&amp;&amp;</span> <span class="p">(</span><span class="kc">true</span> <span class="o">||</span> <span class="kc">false</span><span class="p">))</span> <span class="p">{</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;Confusing code block&quot;</span><span class="p">);</span>
<span class="p">}</span>

<span class="k">if</span> <span class="p">(</span><span class="o">!</span><span class="p">((</span><span class="kc">false</span> <span class="o">||</span> <span class="o">!</span><span class="kc">true</span><span class="p">)</span> <span class="o">||</span> <span class="p">(</span><span class="kc">false</span> <span class="o">&amp;&amp;</span> <span class="kc">true</span><span class="p">)))</span> <span class="p">{</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;De Morgan&#39;s law in my head of confusing code block&quot;</span><span class="p">);</span>
<span class="p">}</span>

<span class="c1">// Can any of the above expression be simplified?  What would they simplify to?  Are any of these expressions useful?</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>True code block
True and Not False code block
True or False code block
Confusing code block
De Morgan&#39;s law of confusing code block
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Hacks">Hacks<a class="anchor-link" href="#Hacks"> </a></h2><p>Build your own Jupyter Notebook lesson on ifs</p>
<ul>
<li>Explain if, if-else, and if-elseif-else.</li>
<li>Make a markdown block before you sample code</li>
<li>Comment in code to describe each decision </li>
</ul>
<p>Add to lesson switch-case</p>
<ol>
<li>Create and if-elseif-elseif-elsif-else statement, 5 or more conditions. </li>
<li>Covert the 5 or more decisions to a switch-case-case-case-case-otherwise.</li>
<li>Make a markdown block before each code example</li>
<li>Comment/establish a style of comments for your if-elseif and switch-case code blocks</li>
</ol>
<p>Finish lesson with De Morgan's law</p>
<ol>
<li>Describe De Morgan's law</li>
<li>Illustrate De Morgan's law</li>
<li>Show some code running that shows understanding</li>
</ol>
<p>Resources, it is really time to show you can find resources beyond the Teacher.   Code/Code/Coding is everywhere, find something that helps.</p>
<ol>
<li><a href="https://studio.code.org/s/csa4-2022?section_id=4160330">Code.org</a> Unitt 4 section 1 to 5 can help with some ideas.</li>
<li><a href="https://apclassroom.collegeboard.org/8/home?unit=3">AP Classroom unit 3</a> has outline for unit</li>
<li><a href="https://www.codecademy.com/learn/learn-java/modules/learn-java-conditionals-control-flow-u">CodeAcademy</a> has some online resources</li>
</ol>

</div>
</div>
</div>
</div>
 
