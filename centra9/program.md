---
layout: centrameeting9
title: CENTRA 2026
permalink: /centra9/program.html
"feature-img": img/centra9/centra9-banner.jpg
published: true
hide: true
---

## CENTRA 9 Program and Schedule
<br>

<div>
  <button class="btn active" onclick="showTable('day1', this)">Day 1 (Jan 11th, 2026)</button>
  <button class="btn" onclick="showTable('day2', this)">Day 2 (Jan 12th, 2026)</button>
  <button class="btn" onclick="showTable('day3', this)">Day 3 (Jan 13th, 2026)</button>
</div>

<table class="program" id="day1">
  <tr>
    <th>Time</th>
    <th>Main Activity</th>
  </tr>
  <tr>
    <td>15:00 - 17:00</td>
    <td>Project Sync</td>
  </tr>
  <tr>
    <td>18:00 - 19:00</td>
    <td>Pre-Meeting Reception</td>
  </tr>
</table>

<table class="program hidden" id="day2">
  <tr>
    <th>Time</th>
    <th>Main Activity</th>
    <th>Parallel Activity</th>
  </tr>
  <tr>
    <td>09:00 - 09:45</td>
    <td>Keynote talk 2</td>
    <td></td>
  </tr>
  <tr>
    <td>09:45 - 10:45</td>
    <td>Presentation Session 2</td>
    <td></td>
  </tr>
  <tr>
    <td>10:45 - 11:15</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>11:15 - 12:30</td>
    <td>Student Presentation</td>
    <td></td>
  </tr>
  <tr>
    <td>12:30 - 14:00</td>
    <td>Lunch</td>
    <td>Lunch & Steering Committee Meeting</td>
  </tr>
  <tr>
    <td>14:00 - 15:00</td>
    <td>Project Group Discussion</td>
    <td></td>
  </tr>
  <tr>
    <td>15:00 - 15:30</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>15:30 - 16:30</td>
    <td>Presentation Session 3</td>
    <td></td>
  </tr>
  <tr>
    <td>16:30 - 17:00</td>
    <td>Conclusion & Closing</td>
    <td></td>
  </tr>
</table>

<table class="program hidden" id="day3">
  <tr>
    <th>Time</th>
    <th>Main Activity</th>
    <th>Parallel Activity</th>
  </tr>
  <tr>
    <td>09:00 - 09:45</td>
    <td>Keynote talk 2</td>
    <td></td>
  </tr>
  <tr>
    <td>09:45 - 10:45</td>
    <td>Presentation Session 2</td>
    <td></td>
  </tr>
  <tr>
    <td>10:45 - 11:15</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>11:15 - 12:30</td>
    <td>Student Presentation</td>
    <td></td>
  </tr>
  <tr>
    <td>12:30 - 14:00</td>
    <td>Lunch</td>
    <td>Lunch & Steering Committee Meeting</td>
  </tr>
  <tr>
    <td>14:00 - 15:00</td>
    <td>Project Group Discussion</td>
    <td></td>
  </tr>
  <tr>
    <td>15:00 - 15:30</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>15:30 - 16:30</td>
    <td>Presentation Session 3</td>
    <td></td>
  </tr>
  <tr>
    <td>16:30 - 17:00</td>
    <td>Conclusion & Closing</td>
    <td></td>
  </tr>
</table>

<script>
  function showTable(dayId, btn) {
    document.getElementById('day1').classList.add('hidden');
    document.getElementById('day2').classList.add('hidden');
    document.querySelectorAll('.btn').forEach(b => b.classList.remove('active'));
    document.getElementById(dayId).classList.remove('hidden');
    btn.classList.add('active');
  }
</script>

<style>
  .program {
    width: calc(100% - 300px);
    border-collapse: collapse;
    font-family: Arial, sans-serif;
    margin-top: 15px;
  }

  .program th, .program td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }

  .program th {
    background-color: #85BCF1;
    color: white;
  }

  .program tr:nth-child(even) {
    background-color: #f9f9f9;
  }

  .program tr:nth-child(odd) {
    background-color: #ffffff;
  }

  .program tr:hover {
    background-color: #f1f1f1;
  }

  /* Buttons */
  .btn {
    background-color: #85BCF1;
    color: white;
    padding: 10px 18px;
    margin-right: 8px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
    transition: background-color 0.3s, transform 0.2s;
  }

  .btn:hover {
    background-color: #4ba2f5;
    transform: scale(1.05);
  }

  .btn.active {
    background-color: #4ba2f5;
  }

  /* Hide tables by default */
  .hidden {
    display: none;
  }
</style>
