---
layout: about
title: About Us
navbar: about
---
A Brief History of SIG-Game  {#Brief-History}
===========================

The Missouri S&amp;T Association for Computing Machinery (ACM)
Special Interest Group for AI Competition Game Development
(SIG-Game) started in Fall 2007 as a gung-ho group of developers
from Missouri S&amp;T loosely associated with the S&amp;T
student chapter of ACM. Their goal was to create a programming
competition designed to test a competitor’s ability to design
and implement an effective, artificially intelligent player for a
novel game. Thus MegaMinerAI was born.

As the development team grew, and with the success of each
semester’s competition, the group formalized under the title
SIG-Game. With the increased size, comes increased
flexibility. While the initial development (Dev) team needed people
with networking ability, current members work on: asynchronous
communication, compression, databases, distributed computing,
evolutionary algorithms, game theory, graphic design, interpreters,
language interoperability, meta programming, parallel computing,
procedural generation, testing, visualization, and more.

<div class="text-center">
  <img src="{{ site.static_url }}img/wrench.png" style="width:75px;">
</div>

What We Do  {#What-We-Do}
==========

MegaMinerAI
-----------

MegaMinerAI is a 24-hour artificial intelligence (AI) programming
competition hosted each semester by S&T ACM SIG-Game. Competitors must
use their 24-hours to develop a program to play a novel game developed
by SIG-Game's development team. The details of the game are kept
secret until the day of competition, so competitors must demonstrate
their wits and coding skills to develop the best AI!

Programs are pitted against one another in SIG-Game's Arena, where
thousands of games are played in the cloud. Game results are available
to users, so that they may further debug their code and refine their
strategy. After the competition ends, a triple-elimination is run to
determine the winners. The top three student teams are awarded prize
money and crowned as the victors of MegaMinerAI.

Open Source
-----------

In addition to developing novel games for MegaMinerAI, the
SIG-Game Development team develops and maintains a framework to
host MegaMinerAI and other programming competitions. Though game
details are kept secret until competition day, our framework is
open source and available
on <a target="_blank" href="https://github.com/siggame">GitHub</a>.


As our competition attendance has grown to record levels, the SIG-Game
Developers have begun a redesign of the competition framework. Each
component of the framework is open source and available on GitHub.

<hr>

Our Projects  {#Projects}
============

<div class="panel-group" id="accordion">

  {% for category in site.data.projects %}
    <div class="panel panel-default">
      <div class="panel-heading" data-toggle="collapse" data-parent="#accordion" href="#{{ category[0] | replace: ' ', '-' }}">
        <h4 class="panel-title">
          {{ category[0] }}
          <span class="glyphicon glyphicon-chevron-down pull-right" style="color:#008CBA"></span>
        </h4>
      </div>
      <div id="{{ category[0] | replace: ' ', '-' }}" class="panel-collapse collapse">
        <div class="panel-body">
          <ul class="list-unstyled">
            {% for project in category[1] %}
              <li><a href="{{ project.url }}">{{ project.name }}</a></li>
            {% endfor %}
          </ul>
        </div>
      </div>
    </div>
  {% endfor %}

</div>

<hr>

Contact Us  {#Contact-Us}
==========

{:refdef: .list-unstyled }
* E-mail SIG-Game at [siggame@mst.edu](mailto:siggame@gmail.com)
* E-mail the SIG-Game Chair, Victoria Kraemer, at <vjkgz3@mst.edu>
{: refdef .list-unstyled}

Suggested Contact Us format Update:

| Contact | Email |
| ------- | -------- | 
| SIG-GAME | siggame@gmail.com |
| Victoria Kraemer - Chair | vjkgz3@mst.edu |

Officers
--------

| Name | Role | Email |
|-------|--------|---------|
| Daniel Tauritz | Faculty Advisor | tauritzd@mst.edu |
| Victoria Kraemer | Chair | vjkgz3@mst.edu |
| Trevan Lang | Vice Chair | txlm4d@mst.edu |
| Hannah Reinbolt | Secretary | hmrvg9@mst.edu |
| Brett Sears | Public Relations | brswc2@mst.edu |
| Michael Beaver | Web Lead | mbbh8@mst.edu |
| Reno DuBois | Web Lead | rtdm9c@mst.edu |
| Quincy Conduff | Arena Lead | qlcfz5@mst.edu |
| Shawn McCormick | AI Lead | shawn.mccormick@mst.edu |
| Joshua Pondrom | Vis Lead | japrkf@mst.edu |
| Chris Kinney | Game Lead | ckq49@mst.edu |
| Jeffrey Strahm | Vice Game Lead | jssfg8@mst.edu |

<!--  LocalWords:  MegaMinerAI
 -->
