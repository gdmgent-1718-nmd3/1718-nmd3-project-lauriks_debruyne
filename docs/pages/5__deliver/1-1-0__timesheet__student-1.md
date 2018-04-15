---
layout   : default
permalink: deliver/timesheets/student-1/
published: true
# Custom Page Variables
# ─────────────────────
title: Student 1
---
{%- comment %}
Vul de timesheet aan in het bestand `_data/timesheet-1.yml`
{%- endcomment %}

{% include timesheet.md timesheet=site.data.timesheet-1 %}

<table class="table">
  <thead>
    <tr>
      <th scope="col">Datum</th>
      <th scope="col">Tijd</th>
      <th scope="col">Wat</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">12 februari </th>
      <td>1:30</td>
      <td>Analyse en begin concept bedenken</td>
    </tr>
    <tr>
      <th scope="row">18 februari</th>
      <td>2:00</td>
      <td>bevraging + museum bezoek</td>
    </tr>
    <tr>
      <th scope="row">19 februari</th>
      <td>1:30</td>
      <td>Analyse verder uitwerken</td>
    </tr>
    <tr>
      <th scope="row">23 februari</th>
      <td>1:30</td>
      <td>Persona’s uitwerken + eerste journey map</td>
    </tr>
  </tbody>
</table>