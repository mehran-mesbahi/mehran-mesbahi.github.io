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

Here are the <a href="{{ site.baseurl }}/assets/pdf/AA528-W2025-Lectures/mehran-notes-528-W2025-introductory.pdf" target="_blank">introductory remarks</a> on the course notes.

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
            <th> Space networks </th>
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
            <th><span style="color: orange;"> Paper</span></th>
            <th><span style="color: orange;"> Student assigned</span></th>
        </tr>
        <tr>
            <th>lecture x</th>
            <th>suggested paper</th>
            <th>initials</th>
        </tr>
    </tbody>
</table>
