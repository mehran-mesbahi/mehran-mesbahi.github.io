---
layout: page
permalink: /controlx/
title: ControlX
description: ControlX 
nav: false
---


ControlX Community consist of a group of researchers on UW campus interested in ``control theory+x'' The control theory part is also interpreted broadly, 
any aspect of decision-making in a dynamic setting, including filtering,
systems/control, optimization, robustness, geometry, etc. And of course the
"+" side spans aerospace, robotics, autonomy, transportation, power systems, biology, neuroscience, etc.

The faculty involved in ControlX community include:


Here is the schedule for 2023-2024.

2023-2024 <a href="https://docs.google.com/spreadsheets/d/15qRJJw_5K2AZG05LP__wtbmaBrEAwjxUT9t85En7kSQ/edit#gid=1817158029/">Schedule</a>


<p><b>Class Time:</b> (M/W) 11:30 pm - 12:50 pm </p>
<p><b>Class websites:</b> Canvas page (homework submissions) and https://shahriarta.github.io/teaching/ </p>
<p><b>Class Room:</b> GUG 204/ <a href="https://washington.zoom.us/j/92496878244">Zoom Link</a> </p>
<p><b>Office Hours:</b> Wednesdays 2:00-3:00 pm in <a href="https://washington.zoom.us/j/95457808598">Zoom Link</a>/GUG 305 (Shahriar); 
      <br>&emsp; &emsp; &emsp; &emsp; &emsp; Fridays 3:30-4:30 pm in <a href="https://washington.zoom.us/j/97544541643">Zoom Link</a> (Dan);
      <br>&emsp; &emsp; &emsp; &emsp; &emsp; We can always setup up another time by email too.</p>


<p> You can find the syllabus <a href="{{ site.baseurl }}/assets/pdf/teach_network/syllabus-Sp2022.pdf" target="_blank">here</a>. </p>

<p> You can also access an online copy of the main textbook <a href="https://alliance-primo.hosted.exlibrisgroup.com/permalink/f/kjtuig/CP71156690860001451" target="_blank">here</a>, provided by the UW library.</p>
<p> Also see another great textbook <a href="https://link.springer.com/book/10.1007/978-3-319-16646-9" target="_blank">here</a>.</p>


<p style="font-size:15pt"> Homework:</p>
<p> Here is the first homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW1.pdf" target="_blank"> PDF </a> (Due April 22, 2022).</p>
<p> Here is the second homework assignment <a href="{{ site.baseurl }}/assets/pdf/teach_network/HW2.ipynb" target="_blank"> Jupyter notebook </a> (Due May 8, 2022). Here is short <a href="https://www.dataquest.io/blog/jupyter-notebook-tutorial/">tutorial</a> how to setup and use Jupyter Notebooks.</p>


<style>
table, th, td {
  border:2px solid black;
}
</style>


<table style="width:100%">
    <thead>
        <tr>
            <th colspan="4"> <p style="font-size:20pt"> Course Schedule</p></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Date</th>
            <th>Topic</th>
            <th>Resources</th>
            <th>Prerequisite</th>
            <th>Extra resources</th>
        </tr>
        <tr>
            <th>March 28th</th>
            <th>syllabus/logistics + intro</th>
            <th>Chp 1 and 2 [Mesbahi2010Graph];
                <a href="{{ site.baseurl }}/assets/pdf/teach_network/GRAPHS_MAR30.pdf" target="_blank">Algebraic Graph Theory Slides</a>
                </th>
            <th>Linear Algebra [Horn2013Matrix]: left/right nullspace, rank-nullity theorem, Singular-value Decomposition (SVD), Moore–Penrose psuedo-inverse</th>
            <th>
            <a href="https://www.nature.com/articles/s41586-020-2923-3.pdf" target="_blank">Superspreaders of Covid-19</a>;
            <a href="https://www.nature.com/articles/ncomms9414.pdf" target="_blank">Controllability of brain network</a>;
            </th>
        </tr>
        <tr>
            <th>March 30th</th>
            <th>Introduction to algebraic graph theory</th>
            <th><a href="{{ site.baseurl }}/assets/pdf/teach_network/GRAPHS_MAR30.pdf" target="_blank">Algebraic Graph Theory Slides (updated)</a></th>
            <th>Linear Algebra [Horn2013Matrix]: Positive semi-definite (PSD) matrices, Eigen-value Decomposition (EVD)</th>
            <th></th>
        </tr>
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
    </tbody>
</table>
