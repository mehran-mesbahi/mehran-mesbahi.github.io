---
layout: page
permalink: /597-course/
title: AA/ECE/ME 597
description: Winter Quarter 2024
nav: false
---

A networked dynamic system is a set of dynamical units that interact over an information-exchange network for its coordinated operation and behavior. Such systems have found many applications in diverse areas of science and
engineering, including multiple space, air, land, and underwater vehicles, energy and power systems, physiology, and
medicine. Currently, there is an active research effort underway in control and systems community to formalize these
dynamical systems and lay out a foundation for their analysis and control synthesis. This course provides an overview
of graph-theoretic techniques that have proven instrumental for studying networked dynamic systems. Specifically,
we will look at the following topics: (1) network models (graphs, random graphs, random geometric graphs, state-dependent
graphs, switching networks), (2) network properties (some useful combinatorial and algebraic properties
of graphs), (3) dynamics over networks- theory and some applications, including agreement/consensus protocol and
its various extensions, and (4) formation control. Other topics that will be covered- depending on the available time include:
advanced algebraic methods in graph theory, biological networks, network controllability and observability,
and games over networks. Suggested prerequisite is Linear Systems (AA/EE/ME 547) but if are taking linear systems concurrently and have solid background in linear algebra, you should be okay.

<p><b>Class Time:</b> (Wednesdays and Fridays) 1:00 pm - 2:20 pm</p>

<p><b>Class Room:</b> Guggenheim Hall 204</p>

{% comment %}
<a href="https://washington.zoom.us/j/92496878244">Zoom Link</a> 
{% endcomment %}

<p><b>Homework Assignments:</b> Assigned every Friday (except the first week) and due the following Friday at 11:59pm on <a href="https://canvas.uw.edu/courses/1695062">Class Canvas</a>; homework grades will also be available on canvas</p> 

<p><b>Homework Submission Link:</b> <a href="https://canvas.uw.edu/courses/1695062">Class Canvas</a> </p>

<p><b>Project:</b> There will be a project/paper/presentation for the course assigned during the second half of the course and due at the end of the quarter</p>


<p><b>Grading:</b> Homework assignments will be 70% of the grade and 30% will be project</p>


<p><b>Office Hours:</b> Thursdays 3:00-5:00 pm in Guggenheim Hall 305 (or instructor's office in Guggenheim Hall 311E)

{% comment %}
<p> You can find the syllabus <a href="{{ site.baseurl }}/assets/pdf/teach_network/syllabus-Sp2022.pdf" target="_blank">here</a>. </p>
{% endcomment %}

<p> You can access an online copy of the main textbook, referred as [MEBook2010] below <a href="https://alliance-primo.hosted.exlibrisgroup.com/permalink/f/kjtuig/CP71156690860001451" target="_blank">here</a>, provided by the UW library; other online resources or links to relevant books/papers will also noted.</p>

{% comment %}
<p> Also see another great textbook <a href="https://link.springer.com/book/10.1007/978-3-319-16646-9" target="_blank">here</a>.</p>
{% endcomment %}

{% comment %}
<p style="font-size:15pt"> Homework:</p>
<p> Here is the first homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW1.pdf" target="_blank"> PDF </a> (Due April 22, 2022).</p>
<p> Here is the second homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW2.ipynb" target="_blank"> Jupyter notebook </a> (Due May 8, 2022). Here is short <a href="https://www.dataquest.io/blog/jupyter-notebook-tutorial/">tutorial</a> how to setup and use Jupyter Notebooks.</p>
{% endcomment %}

<style>
table, th, td {
  border:2px solid black;
}
</style>


<table style="width:100%">
    <thead>
        <tr>
            <th colspan="6"> <p style="font-size:22pt"> Course Schedule, Winter 2024</p></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Date</th>
            <th>Topics</th>
            <th>Reference</th>
            <th>MM Notes</th>
            <th>Notes & check these out</th>
        </tr>
        <tr>
            <th>January 3</th>
            <th>syllabus/logistics, graph theory basics, examples, algorithms, networkx</th>
            <th>Chapters 1 and 2 [MEBook2010]
                </th>
            {% comment %}
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/GRAPHS_MAR30.pdf" target="_blank">Lecture 1-1</a></th>
            {% endcomment %}
            <th></th>
            <th>
            <a href="https://www.algorithmsilluminated.org/">Algorithms Illuminated</a>;
            <a href="https://www.nature.com/articles/s41586-020-2923-3.pdf" target="_blank">Superspreaders of Covid-19</a>;
            <a href="https://www.nature.com/articles/ncomms9414.pdf" target="_blank">Controllability of brain network</a>;
            </th>
        </tr>
        <tr>
            <th>January 5</th>
            <th>Euler's theorem, matrix representations, spectral graph theory</th>
            {%comment%}
            <th><a href="{{ site.baseurl }}/assets/pdf/AA597-lecture1-1.pdf" target="_blank">Algebraic Graph Theory Slides (updated)</a></th>
            {% endcomment %}
            <th></th>
            <th></th>
            {% comment %}
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/GRAPHS_MAR30.pdf" target="_blank">Lecture 1-2</a></th>
            {% endcomment %}
        </tr>
        <tr>
            <th>January 10</th>
            <th> consensus on undirected networks and consequences</th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>January 12</th>
            <th> consensus on directed networks and consequences</th>
            <th></th>
            <th></th>
            <th>HW#1 assigned</th>
        </tr>
        <tr>
            <th>January 17</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>January 19</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#2 assigned</th>
        </tr>
        <tr>
            <th>January 24</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>January 26</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#3 assigned</th>
        </tr>
        <tr>
            <th>January 31</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>February 2</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#4 assigned</th>
        </tr>
        <tr>
            <th>February 7</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>February 9</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#5 assigned</th>
        </tr>
        <tr>
            <th>February 14</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>February 16</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#6 assigned</th>
        </tr>
        <tr>
            <th>February 21</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>February 23</th>
            <th> </th>
            <th></th>
            <th></th>
            <th>HW#7 assigned</th>
        </tr>
        <tr>
            <th>February 28</th>
            <th> </th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>March 1</th>
            <th> Project Presentations </th>
            <th></th>
            <th></th>
            <th>HW#8 assigned</th>
        </tr>
        <tr>
            <th>March 8</th>
            <th> Project Presentations </th>
            <th></th>
            <th></th>
            <th>Project reports due on March 13</th>
        </tr>




{% comment %}        
        <tr>
            <th>Apr 4th</th>
            <th>Laplacian, its spectrum and connectivity</th>
            <th>Chp 2 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/GRAPHS_MAR30_annotated.pdf" target="_blank">Algebraic Graph Theory Slides (annotated)</a></th>
            <th>Linear Algebra: same</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/DFT.pdf" target="_blank"> circulant matrices</a></th> 
        </tr>
        <tr>
            <th>Apr 6th</th>
            <th>Agreemment protocol (undirected graph)</th>
            <th>Chp 2 and 3 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/Agreement_Protocol1.pdf" target="_blank">Notes (AP)</a></th>
            <th> Linear systems: Basic linear dynamical systems, their solution, stability and convergence properties</th>
            <th></th>
        </tr>
        <tr>
            <th>Apr 11th</th>
            <th>Agreemment protocol (directed graph + discrete time)</th>
            <th>Chp 3 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/Agreement_Protocol2.pdf" target="_blank">Notes (directed AP)</a></th>
            <th>Linear systems: same; Linear algebra [Horn2013Matrix]: non-negative matrices and their properties</th>
            <th></th>
        </tr>
        <tr>
            <th>Apr 13th</th>
            <th>Agreemment protocol (directed graph + discrete time)</th>
            <th>Cont. Chp 3 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/Agreement_Protocol3.pdf" target="_blank">Notes (directed AP-cont.)</a></th>
            <th>Linear systems: same; Linear algebra [Horn2013Matrix]: non-negative matrices and their properties,  Perron–Frobenius theorem</th>
            <th></th>
        </tr>
        <tr>
            <th>Apr 18th</th>
            <th>Factorization Lemma</th>
            <th>Cont. Chp 3 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/Factorization_Lemma.pdf" target="_blank">Notes (Factorization Lemma)</a></th>
            <th>Linear systems: same; Linear algebra [Horn2013Matrix]: Kronecker product of matrices</th>
            <th></th>
        </tr>
        <tr>
            <th>Apr 20th</th>
            <th>Varying graph</th>
            <th>Chp 4 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/Lyapunov_methods.pdf" target="_blank">Notes (Lyapunov methods)</a></th>
            <th>Linear systems: same; Linear algebra [Horn2013Matrix]: Perron–Frobenius theorem, [Mesbahi2010Graph, Appendix]: Lyapunov stability, LaSalle's invariance principle</th>
            <th></th>
        </tr>
        <tr>
            <th>Apr 25th</th>
            <th>Varying graph (cont.)+ Edge consensus</th>
            <th>Chp 4 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/Edge_consensus.pdf" target="_blank">Notes (Lyapunov methods cont.+ Edge consensus)</a> </th>
            <th>Linear systems, Linear algebra, [Mesbahi2010Graph, Appendix]: LaSalle's invariance principle for switched linear systems</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/BLOCKMATRIX.pdf" target="_blank">Block Matrix Multiplication</a>, and <a href="{{ site.baseurl }}/assets/pdf/teach_network/DIAGONAL.pdf" target="_blank">Eigenvalue-Eigenvector</a></th>
        </tr>
        <tr>
            <th>Apr 27th</th>
            <th>discretization and generalization of A.P.</th>
            <th>Chp 4 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/discretization.pdf" target="_blank">Notes (discretization vs discrete sampling)</a></th>
            <th>Linear systems: same; Linear algebra [Horn2013Matrix]: Perron–Frobenius theorem, Metzler matrices</th>
            <th><a href="https://ieeexplore.ieee.org/abstract/document/1429377" target="_blank"> Moreau'04</a>, and <a href="https://ieeexplore.ieee.org/document/1393134" target="_blank"> Moreau'05</a>; <a href="https://ieeexplore.ieee.org/document/1431045" target="_blank"> time-varying graph</a></th>
        </tr>
        <tr>
            <th>May 2nd</th>
            <th>Discrete A.P. and distributed estimation</th>
            <th>Chp 8 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/distributed_estimation.pdf" target="_blank">Notes</a> </th>
            <th>Discrete linear systems: Linear algebra [Horn2013Matrix]: Perron–Frobenius theorem, irreducible and primitive matrices</th>
            <th><a href="https://web.stanford.edu/~boyd/papers/pdf/avg_metropolis.pdf" target="_blank"> Metropolis weights</a>; <a href="https://projecteuclid.org/journals/annals-of-statistics/volume-21/issue-1/On-Reaching-a-Consensus-Using-Degroots-Iterative-Pooling/10.1214/aos/1176349032.full" target="_blank"> Consensus on opinions</a> </th>
        </tr>
        <tr>
            <th>May 4th</th>
            <th>Distributed Kalman Filtering</th>
            <th>Chp 8 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/Kalman_filter.pdf" target="_blank">Notes</a> and <a href="{{ site.baseurl }}/assets/pdf/teach_network/KALMAN.pdf" target="_blank">Slides</a> </th>
            <th>Discrete linear systems; Linear algebra [Horn2013Matrix]; Kalman Filter</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/ARRAYS.pdf" target="_blank">Python slides (Numpy array)</a></th>
        </tr>
        <tr>
            <th>May 9th</th>
            <th>Kalman Filtering (cont.)+ distributed optimization</th>
            <th>Chp 8 [Mesbahi2010Graph] <a href="{{ site.baseurl }}/assets/pdf/teach_network/Kalman_filter2.pdf" target="_blank">Kalman Filter2</a>  <a href="{{ site.baseurl }}/assets/pdf/teach_network/KALMAN.pdf" target="_blank"></a> </th>
            <th>Discrete linear systems; Linear algebra [Horn2013Matrix]; Kalman Filter</th>
            <th><a href="https://stanford.edu/~jduchi/projects/DuchiAgWa10_nips.pdf" target="_blank">Distributed Dual Averaging</a> </th>
        </tr>
        <tr>
            <th>May 11th</th>
            <th>distributed optimization (Cont.)</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/notesMay11.pdf" target="_blank">notes</a> </th>
            <th>Discrete linear systems; Linear algebra [Horn2013Matrix]; Basic convex analysis</th>
            <th><a href="https://stanford.edu/~jduchi/projects/DuchiAgWa10_nips.pdf" target="_blank">Distributed Dual Averaging</a> </th>
        </tr>
        <tr>
            <th>May 16th</th>
            <th>distributed optimization (Cont.) + Formation Control</th>
            <th>Chp 6 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/notesMay16.pdf" target="_blank">notes</a> </th>
            <th>Discrete linear systems; Linear algebra [Horn2013Matrix]; Basic convex analysis</th>
            <th> </th>
        </tr>
        <tr>
            <th>May 18th</th>
            <th>Formation Control (Cont.)</th>
            <th>Chp 6 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/notesMay18.pdf" target="_blank">notes</a> </th>
            <th>Discrete linear systems; Linear algebra [Horn2013Matrix]; </th>
            <th> </th>
        </tr>
        <tr>
            <th>May 23th</th>
            <th>Controllability of Networks</th>
            <th>Chp 10 [Mesbahi2010Graph], <a href="{{ site.baseurl }}/assets/pdf/teach_network/notesMay23.pdf" target="_blank">notes</a> </th>
            <th>Controllability and Observability of linear systems; PBH test</th>
            <th> <a href="http://control.asu.edu/Classes/MAE598/598Lecture05.pdf" target="_blank">slides</a> of LMIs for Controllability by M. Peet</th>
        </tr>
        <!--
        <tr>
            <th>Apr 18th</th>
            <th>(tentative!) Agreemment protocol (random graph) </th>
            <th>Chp 5 [Mesbahi2010Graph]</th>
            <th> Probability: Basic concepts such as Event, probability, and expectation. Also, convergence of sequences in probability. </th>
            <th></th>
        </tr>
        -->
{% endcomment %}
    </tbody>
</table>