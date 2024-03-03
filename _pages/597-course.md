---
layout: page
permalink: /597-course/
title: AA/ECE/ME 597
description: Winter Quarter 2024
nav: false
---

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

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


<p><b>Office Hours:</b> Thursdays 3:00-5:00 pm in AERB 130 (or instructor's office in Guggenheim Hall 311E)

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
            <th>
            <a href="https://www.algorithmsilluminated.org/">Algorithms Illuminated</a>;
            <a href="https://cambridgeuniversitypress.github.io/FirstCourseNetworkScience/">A First Course in Network Science</a>;
            
            <a href="https://www.nature.com/articles/s41586-020-2923-3.pdf" target="_blank">Superspreaders of Covid-19</a>;
            <a href="https://www.nature.com/articles/ncomms9414.pdf" target="_blank">Controllability of brain network</a>; your personal homework this week (no need to turn anything in) is to become familiar with python/juypter notebook/networkx or something  similar, e.g., matlab/julia, to create, draw, and analyze networks/graphs, and be able to simulate dynamic systems described by differential equations
            </th>
        </tr>
        <tr>
            <th>Jan 5</th>
            <th>Euler's theorem, a few notions on graphs, connectivity, breadth-first-search </th>
            <th><a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-5.pdf" target="_blank">Mehran Notes</a></th>
            <th></th>
            <a href="https://www.algorithmsilluminated.org/">Algorithms Illuminated</a>, read about Euler's theorem history.
        </tr>
        <tr>
            <th>Jan 10</th>
            <th> No lecture due to MM travel</th>
            <th> will do a make up lecture/notes</th>
            <th></th>
        </tr>
        <tr>
            <th>Jan 12</th>
            <th> node and edge connectivity, spectral graph theory, introduction to dynamics on adjacency and Laplacian, introduction to notions of control on networks</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-12.pdf" target="_blank">Mehran Notes</a></th>
            <th>HW#1 assigned; see course canvas page</th>
        </tr>
        <tr>
            <th>Jan 17</th>
            <th> consensus protocol </th>
            <th> Chapter 3 [MEBook2010]; <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-17.pdf" target="_blank">Mehran Notes</a></th>
            <th> Consensus protocol is a versatile distributed algorithm for achieving something that at the surface seems useless; but it is one of the most used module for devising a host of distributed algorithms for optimization, formation control, and estimation</th>
        </tr>
        <tr>
            <th>Jan 19</th>
            <th> consensus on directed networks</th>
            <th> Chapter 3 [MEBook2010]; <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-19.pdf" target="_blank">Mehran Notes</a></th>
            <th>HW#2 assigned (see course canvas page); HW#1 due; check out: <a href="https://www.incontrolpodcast.com/1632769/14297756-ep19-naomi-ehrich-leonard-part-ii-unveiling-the-dynamics-of-collective-decision-making-from-flocking-starlings-to-desert-ants-political-polarization-and-the-creative-dance-between-arts-and-control-theory">Naomi Leonard Podcast</a> related to our discussion </th>
        </tr>
        <tr>
            <th>Jan 24</th>
            <th> Lyapunov analysis for networks </th>
            <th>Chapter 4 [MEBook2010]; <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-24.pdf" target="_blank">Mehran Notes</a></th>
            <th><a href="https://ieeexplore.ieee.org/document/1333204"> one of the original works in this area </a> and <a href="https://arxiv.org/pdf/1407.7585.pdf"> a more recent work </a> </th>
        </tr>
        <tr>
            <th>Jan 26</th>
            <th> More on Lyapunov analysis; unicyle formations </th>
            <th>Chapter 4 [MEBook2010]; <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-26.pdf" target="_blank">Mehran Notes</a></th>
            <th><a href="https://ieeexplore.ieee.org/document/4200872"> paper on planar collective motion </a> by Sepulchre/Paley/Leonard</th>
        </tr>
        <tr>
            <th>Jan 31</th>
            <th> unicyle formations; formation specifications/graph rigidity </th>
                <th>Chapter 6 [MEBook2010]; <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Jan-31.pdf" target="_blank">Mehran Notes</a></th>
            <th></th>
        </tr>
        <tr>
            <th>Feb 2</th>
            <th> formation control; <a href="https://paperpile.com/shared/OuVYMh"> Fax/Murray paper </a></th>
            <th>Chapter 6 [MEBook2010]</th>
            <th>HW#4 assigned; HW#3 due (both on canvas page)</th>
        </tr>
        <tr>
            <th>Feb 7</th>
            <th>games on networks/chip firing/more formation control  </th>
            <th> <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Feb-7.pdf" target="_blank">Mehran Notes</a> </th>
            <th></th>
        </tr>
        <tr>
            <th>Feb 9</th>
            <th> state-dependent networks; network synthesis </th>
            <th> <a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Feb-9.pdf" target="_blank">Mehran Notes</a> </th>
            <th>HW#5 assigned; HW#4 due</th>
        </tr>
        <tr>
            <th>Feb 14</th>
            <th> network controllability </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>Feb 16</th>
            <th> network controllability; network H2 performance and effective resistance </th>
            <th></th>
            <th>HW#5 due</th>
        </tr>
        <tr>
            <th>Feb 21</th>
            <th> distributed least squares </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>Feb 23</th>
            <th>  distributed optimization </th>
            <th></th>
            <th>no homework assigned this week</th>
        </tr>
        <tr>
            <th>Feb 28</th>
            <th>distributed estimation and filtering  </th>
            <th><a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-Feb-28.pdf" target="_blank">Mehran Notes</a> </th>
            <th></th>
        </tr>
        <tr>
            <th>March 1</th>
            <th>distributed estimation and filtering; Markov chains</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/mehran-notes-597-W2024-March-1.pdf" target="_blank">Mehran Notes</a> </th>
            <th>HW#6 due</th>
        </tr>
           <tr>
            <th>March 6</th>
            <th> Project Presentations </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th>March 8</th>
            <th> Project Presentations </th>
            <th></th>
            <th>HW#8 due; Project reports due on March 13</th>
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
