---
layout: page
permalink: /528-course/
title: AA 528
description: Winter Quarter 2025
nav: false
---

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

Spacecraft dynamics and control involve understanding how gravitation, in addition to
other forces such as drag and environmental perturbations, lead to interesting
dynamics and means by which such a dynamics can be estimated and controlled. 
The list of topics that would fit this umbrella is indeed vast; these topics could
intersect astrodynamics, planetary motion, ascent and descent trajectories,
attitude dynamics, orbital perturbations, three-body problem and Halo orbits,
underlying the mechanics and operation of sensors and actuators, guidance problems,
verification and validation, data science of space mission analysis, design, and operation,
constellations and formation flight, among so many others. But I had to draw
the line for a one quarter course! Hence, here are the topics that I 
plan to discuss this quarter; even if you have seen these topics
before, you will learn something new.
<span style="color: orange;"> week 1)</span> Coordinates and Orientations: coordinate frames, rotation matrices, groups; quaternions and some algebra
<span style="color: orange;"> week 2)</span> Taking derivatives, kinematics for translation and rotation; dynamics for translation and rotation;
stability of torque free motion, <span style="color: orange;"> week 3)</span> two-body problem and examples covering
landing and satellite reconfiguration via quaternion feedback, <span style="color: orange;"> week 4)</span> gravity gradients
and introduction to rendezvous and docking,  <span style="color: orange;"> week 5)</span> more on rendezvous problem and perturbation
theory, <span style="color: orange;"> week 6)</span> attitude estimation, <span style="color: orange;"> week 7)</span> attitude control, <span style="color: orange;"> week 8)</span> restricted three body problem,
<span style="color: orange;"> week 9)</span> GPS and constellations, and <span style="color: orange;"> week 10)</span> group presentations. It will be fun!

<p><b>Class Time:</b> (Wednesdays and Fridays) 10:00 am - 11:20 am</p>

<p><b>Class Room:</b> Guggenheim Hall 204</p>

{% comment %}
<a href="https://washington.zoom.us/j/92496878244">Zoom Link</a> 
{% endcomment %}

<p><b>Homework Assignments:</b> Assigned every Friday and due the following Friday at 11:59pm on <a href="https://canvas.uw.edu/courses/1785234">Class Canvas</a>; homework grades will also be available on canvas</p> 

<p><b>Homework Submission Link:</b> <a href="https://canvas.uw.edu/courses/1785234">Class Canvas</a> </p>

<p><b>Project:</b> There will be a project/paper/presentation for the course assigned during the second half of the course and due at the end of the quarter</p>


<p><b>Grading:</b> Homework assignments will be 65% of the grade and 35% will be project</p>


<p><b>Office Hours:</b> Thursdays 4:00-6:00 pm in Guggenheim Hall 211/conference room

{% comment %}
<p> You can find the syllabus <a href="{{ site.baseurl }}/assets/pdf/teach_network/syllabus-Sp2022.pdf" target="_blank">here</a>. </p>
{% endcomment %}

<p> The e-book version of the book can be purchased from <a href="https://link.springer.com/book/10.1007/978-1-4939-0802-8" target="_blank">here</a>, as well as the bookstore and on Amazon.</p>

{% comment %}
<p> Also see another great textbook <a href="https://link.springer.com/book/10.1007/978-3-319-16646-9" target="_blank">here</a>.</p>
{% endcomment %}

{% comment %}
<p style="font-size:15pt"> Homework:</p>
<p> Here is the first homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW1.pdf" target="_blank"> PDF </a> (Due April 22, 2022).</p>
<p> Here is the second homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW2.ipynb" target="_blank"> Jupyter notebook </a> (Due May 8, 2022).Here is short <a href="https://www.dataquest.io/blog/jupyter-notebook-tutorial/">tutorial</a> how to setup and use Jupyter Notebooks.</p>
{% endcomment %}


<style>
table, th, td {
  border:2px solid black;
}
</style>


<table style="width:100%">
    <thead>
        <tr>
            <th colspan="6"> <p style="font-size:22pt"> <span style="color: orange;"> Course Schedule, Winter 2025</span> </p></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: orange;">Date</span>&nbsp;&nbsp;&nbsp;&nbsp;</th>
            <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: orange;">Topics</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
            <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: orange;"> Reference</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
            <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: orange;"> Notes</span></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 8</span></th>
            <th>syllabus/logistics; introduction; coordinate frames</th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 10</span></th>
            <th> parameterization of SO(3); quarternions </th>
            <th></th>
            <th>HW#1 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 15</span></th>
            <th> kinematics </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 17</span></th>
            <th> dynamics </th>
            <th></th>
            <th>HW#2 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 22</span></th>
            <th>2-body problem </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 24</span></th>
            <th> example: landing and reconfiguration problem</th>
            <th></th>
            <th>HW#3 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 29</span></th>
            <th> example: gravity gradient stabilization </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 31</span></th>
            <th> rendezvous and docking </th>
            <th></th>
            <th>HW#4 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 5</span></th>
            <th> more on rendezvous and docking </th>
            <th></th>
            <th></th>   
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 7</span></th>
            <th> perturbation theory </th>
            <th></th>
            <th>HW#5 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 12</span></th>
            <th>attitude determination </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 14</span></th>
            <th> more on attitude determination </th>
            <th></th>
            <th>HW#6 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 19</span></th>
            <th> attitude control </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 21</span></th>
            <th> more on attitude control </th>
            <th></th>
            <th>HW#7 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 26</span></th>
            <th>  restricted three-body problem </th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 28</span></th>
            <th> more on restricted three-body problem </th>
            <th></th>
            <th>HW#8 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 5</span></th>
            <th>Constellations and GPS</th>
            <th> </th>
            <th></th>
        </tr>
           <tr>
            <th><span style="color: orange;"> March 7</span></th>
            <th> More on constellations </th>
            <th></th>
            <th>HW#9 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 12</span></th>
            <th> Project Presentations </th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 14</span></th>
            <th> Project Presentations </th>
            <th></th>
            <th>Project reports due on March 17 at 11:59pm</th>
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
