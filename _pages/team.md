---
title: "Hydroinformatics Lab - Team"
layout: gridlay
excerpt: "Hydroinformatics Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors).

## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Masters and Bachelor Students 
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni
<table align="center" style="width:100%">
<tr><th>Visitors</th>
    <th>Master Students</th> 
    <th>Ph.D. Students</th>
  </tr>
  <tr>
    <td>Mehmet Ercan, 2015</td>
    <td>Stuart Sheffield, 2016</td>
    <td></td>
  </tr>
  <tr>
    <td>Md. Jahangir Alam, 2013</td>
    <td>Ben Felton, 2015</td>
    <td></td>
  </tr>
  <tr>
    <td>Phillis Mbewe, 2013</td>
    <td>Alicia Nobles, 2014</td>
    <td></td>
  </tr>
  <tr>
    <td>Mirza Billah, 2013</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mostafa Elag, 2013</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Tony Castronova</td>
    <td></td>
    <td></td>
  </tr>
</table>

## Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration.

## Lab Guests

[Amir Safavi-Naeini](http://stanford.edu/~safavi/) (Stanford), summer 2015

[Mark H Fischer](https://people.phys.ethz.ch/~mfischer/) (Weizmann Institute of Science), fall 2015

[Alexander Ako Khajetoorians](http://www.ru.nl/spm) (Radboud University), fall 2015

[Mohammad Hamidian](http://www.mhamidian.com) (Harvard->UC Davis), spring 2016

[Ivan Bozovic](https://www.bnl.gov/cmpmsd/mbe/default.asp) (BNL / Yale), spring 2016

[Freek Massee](http://www.fmassee.nl) (Paris), spring 2016

[Felix Baumberger](http://dqmp.unige.ch/baumberger/) (Geneva), spring 2016

[Jasper van Wezel](http://www.jvanwezel.com/) (UvA), summer 2016
