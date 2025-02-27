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
<span style="color: orange;"> week 9)</span> GPS, constellations, space networks, and <span style="color: orange;"> week 10)</span> group presentations. It will be fun!

<p>Please see the "Announcements" link on <a href="https://canvas.uw.edu/courses/1785234">Class Canvas</a> for a poll before the first class</p> 

<p><b>Class Time:</b> (Wednesdays and Fridays) 10:00 am - 11:20 am</p>

<p><b>Class Room:</b> Guggenheim Hall 204</p>

{% comment %}
<a href="https://washington.zoom.us/j/92496878244">Zoom Link</a> 
{% endcomment %}

<p><b>Homework Assignments:</b> Assigned every Friday and due the following Friday at 11:59pm on <a href="https://canvas.uw.edu/courses/1785234">Class Canvas</a>; homework grades will also be available on canvas</p> 

<p><b>Homework Submission Link:</b> <a href="https://canvas.uw.edu/courses/1785234">Class Canvas</a> </p>

<p><b>Project:</b> There will be a project/paper/presentation for the course assigned during the second half of the course and due at the end of the quarter</p>


<p><b>Grading:</b> Homework assignments will be 65% of the grade and 35% will be project</p>


<p><b>Office Hours:</b> Thursdays 4:00-6:00 pm in Guggenheim Hall 211/conference room; <span style="color: red;"> no office hours on Feb. 13 and no homework due on Feb. 14</span>

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
            <th>&nbsp;<span style="color: orange;"> MM Notes</span>&nbsp;</th>
            <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color: orange;"> Reminders</span></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 8</span></th>
            <th> introductory remarks</th>
            {% comment %}
            <th><a href="{{ site.baseurl }}/assets/pdf/AA528-W2025-Lectures/mehran-notes-528-W2025-introductory.pdf" target="_blank">mehran-lecture0</a></th>
            {% endcomment %}
            <th><a href="https://www.dropbox.com/scl/fi/sdzwfztwr2hau3q0w8iti/mehran-notes-528-W2025-introductory.pdf?rlkey=zo96302om7sfegjqgd1837rm2&st=4lryh3zz&dl=0">mehran-lecture0</a></th>
            <th>preface to lecture notes</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 8</span></th>
            <th>syllabus/logistics; introduction; coordinate frames</th>
            {% comment %}
            <th><a href="{{ site.baseurl }}/assets/pdf/AA528-W2025-Lectures/mehran-notes-528-W2025-lecture1.pdf" target="_blank">mehran-lecture1</a></th>
            {% endcomment %}
            <th><a href="https://www.dropbox.com/scl/fi/p3z4lkb3jktwmjixzils9/mehran-notes-528-W2025-lecture1.pdf?rlkey=akzf8cxbanrkxvwfqb4z9evjy&st=j0xi0y42&dl=0">mehran-lecture1</a> (1/14;2:39pm)</th>
            <th>please go over my "not-due" assignment for this lecture</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 10</span></th>
            <th> parameterization of SO(3); quarternions </th>
            <th><a href="https://www.dropbox.com/scl/fi/co1ojtk2mc01cwrlw4jrp/mehran-notes-528-W2025-lecture2.pdf?rlkey=inezyesnmgy5oft260addq1td&st=yrw2c0oc&dl=0">mehran-lecture2</a> (1/15;6:20pm)</th>
            <th>HW#1 assigned</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 15</span></th>
            <th> kinematics </th>
            <th><a href="https://www.dropbox.com/scl/fi/1mcav5sgulfi2gmtktcc4/mehran-notes-528-W2025-lecture3.pdf?rlkey=95occqmodhhi8lfgttj1slffa&st=zlerjknv&dl=0">mehran-lecture3</a> (1/14;2:39pm)</th>
            <th>started adding time tags to lecture notes for updates</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 17</span></th>
            <th> dynamics </th>
            <th><a href="https://www.dropbox.com/scl/fi/ysghqeuxipky2jb00m06u/mehran-notes-528-W2025-lecture4.pdf?rlkey=vuiothz5pfneamq9bl2089w0i&st=vfitr25a&dl=0">mehran-lecture4</a> (1/16;11:00pm)</th>
            <th>HW#2 assigned; HW#1 due</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 22</span></th>
            <th>2-body problem </th>
            <th><a href="https://www.dropbox.com/scl/fi/i9s6ulalscjdaixbsd00u/mehran-notes-528-W2025-lecture5.pdf?rlkey=237nhuk0hwc8tkirm6z69uwzf&st=k7yoxmso&dl=0">mehran-lecture5</a> (1/25;5:17pm)</th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 24</span></th>
            <th> example: simple landing guidance</th>
            <th><a href="https://www.dropbox.com/scl/fi/lhsyvhkkzyw2n7ikg2bjj/mehran-notes-528-W2025-lecture6.pdf?rlkey=d1e9yf71phpzvdeqfoxu1j4ji&st=evph632v&dl=0">mehran-lecture6</a> (1/25;5:17pm)</th>
            <th>HW#3 assigned; HW#2 due</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 29</span></th>
            <th> attitude reconfiguration; axisymmetric spacecraft </th>
            <th><a href="https://www.dropbox.com/scl/fi/ebskhqsd2sa9cwyuloc0l/mehran-notes-528-W2025-lecture7.pdf?rlkey=b499m2ve6mgzcp8dzrn9i3fxh&st=yv9bu8i6&dl=0">mehran-lecture7</a> (1/25;5:17pm)</th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Jan 31</span></th>
            <th> gravity gradient stabilization </th>
            <th><a href="https://www.dropbox.com/scl/fi/ne7wimbbr60dmg0y1z1qw/mehran-notes-528-W2025-lecture8.pdf?rlkey=2jdnlx12zri43f8qe1v9fi9l8&st=08wxhppr&dl=0">mehran-lecture8</a> (1/31;11:30am)</th>
            <th>HW#4 assigned; HW#3 due</th>
        </tr> 
        <tr>
            <th><span style="color: orange;"> Feb 5</span></th>
            <th> rendezvous and docking </th>
            <th><a href="https://www.dropbox.com/scl/fi/29r9ez8rrhsdaf51pv51e/mehran-notes-528-W2025-lecture9.pdf?rlkey=vo8otvqwai36v7fp9shk2e3ni&st=8p5esj6b&dl=0">mehran-lecture9</a> (2/5;1:25pm)</th>
            <th></th>   
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 7</span></th>
            <th> perturbation theory </th>
            <th><a href="https://www.dropbox.com/scl/fi/j0er02kv3tl8iz1necbbr/mehran-notes-528-W2025-lecture10.pdf?rlkey=nah23h7xgzc7jpc8xjee5lu41&st=ete0f6zy&dl=0">mehran-lecture10</a> (2/4;5:05pm)</th>
            <th>HW#5 assigned; HW#4 due </th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 12</span></th>
            <th>attitude determination </th>
            <th><a href="https://www.dropbox.com/scl/fi/huyllctxarjm3xadilk4s/mehran-notes-528-W2025-lecture11.pdf?rlkey=k6cqyto0hjm0ejv8ju31vdr54&st=ofexiym4&dl=0">mehran-lecture11</a> (2/11;5:21pm)</th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 14</span></th>
            <th> no class</th>
            <th></th>
            <th>No homework due this week/except project papers</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 19</span></th>
            <th> attitude control </th>
            <th><a href="https://www.dropbox.com/scl/fi/y0b0v89sm6b5zq8txrbmz/mehran-notes-528-W2025-lecture12.pdf?rlkey=0izbybuzzhujod2ssguypfst2&st=2lbggz02&dl=0">mehran-lecture12</a> (2/18;6:21pm)</th>
            <th></th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 21</span></th>
            <th> more on attitude control </th>
            <th><a href="https://www.dropbox.com/scl/fi/ee1y0lkgyjcpjrezezi9i/mehran-notes-528-W2025-lecture13.pdf?rlkey=tyuzvhfzjwjk2gnqqab1j1b81&st=a6q7jsmm&dl=0">mehran-lecture13</a> (2/20;9:50pm)</th>
            <th>HW#6 assigned; HW#5 due</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 26</span></th>
            <th>CMGs</th>
            <th><a href="https://www.dropbox.com/scl/fi/nqdvf753mako0ayl69hte/mehran-notes-528-W2025-lecture14.pdf?rlkey=1z7sgm88358p2door2b3vxi7q&st=zebnjhau&dl=0">mehran-lecture14</a> (2/26;5:41pm)</th>
            <th><a href="https://arc.aiaa.org/doi/10.2514/2.4987">paper this lecture is based on</a> (2/26;5:41pm)</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> Feb 28</span></th>
            <th>restricted three-body problem </th>
            <th><a href="https://www.dropbox.com/scl/fi/dm7wq8yuxryjtswemm7mz/mehran-notes-528-W2025-lecture15.pdf?rlkey=dmrm0r66hnrfujwhbqtp4uq44&st=huij8q4d&dl=0">mehran-lecture15</a> (2/26;5:41pm)</th>
            <th>HW#7 assigned; HW#6 due</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 5</span></th>
            <th>more on restricted three-body problem</th>
            <th> </th>
            <th></th>
        </tr>
           <tr>
            <th><span style="color: orange;"> March 7</span></th>
            <th>constellations, GPS, space networks </th>
            <th> </th>
            <th>HW#7 due</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 12</span></th>
            <th> Project Presentations </th>
            <th> students presenting on their projects</th>
        </tr>
        <tr>
            <th><span style="color: orange;"> March 14</span></th>
            <th> Project Presentations </th>
            <th>students presenting on their projects</th>
            <th>Project reports due on March 17 at 11:59pm</th>
        </tr>
    </tbody>
</table>

<br>

<br>

During the course of the quarter, I will include some papers below that you can consider to dive into for your project. However, if there are other papers that you like to consider, please coordinate with me ahead of time (at least 3-4 weeks before the end of the quarter).

<br>
<br>
<table style="width:100%">
    <thead>
        <tr>
            <th colspan="6"> <p style="font-size:22pt"> <span style="color: orange;"> Some suggested Papers for the Project</span> </p></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th><span style="color: orange;"> Related to Lecture</span></th>
            <th><span style="color: orange;"> Papers</span></th>
            <th><span style="color: orange;"> Student assigned</span></th>
        </tr>
        <tr>
            <th>landing/guidance</th>
            <th><a href="https://paperpile.com/shared/sXKDkNvq3SO2guQkwQaGYTQ">sample related papers</a> </th>
            <th>notes</th>
        </tr>
        <tr>
            <th>halo orbits</th>
            <th><a href="https://paperpile.com/shared/sfoCilxpdR9mI4vtyxjMvGA">sample related papers</a> </th>
            <th>notes</th>
        </tr>
        <tr>
            <th>quaternions</th>
            <th><a href="https://paperpile.com/shared/sng6EhV4tQiyZMPKo3OVR0Q">sample related papers</a> </th>
            <th>notes</th>
        </tr>
        <tr>
            <th>attitude estimation</th>
            <th><a href="https://paperpile.com/shared/sLuXAb_J2Tg2VMvKNVNQrNQ">sample related papers</a> </th>
            <th>notes</th>
        </tr>
        <tr>
            <th>RW and CMGs</th>
            <th><a href="https://paperpile.com/shared/sJATEgqS~TuiJlM0GX7pPFw">sample related papers</a> </th>
            <th>notes</th>
        </tr>   
        <tr>
            <th>constellation design</th>
            <th><a href="https://paperpile.com/shared/s2WrhmtqfRFyMBdPV9sXOTA">sample related papers</a> </th>
            <th>notes</th>
        </tr>    
    </tbody>
</table>
