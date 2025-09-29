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
  <button class="btn active" onclick="showTable('day1', this)">Day 1</button>
  <button class="btn" onclick="showTable('day2', this)">Day 2</button>
</div>
<table class="program" id="day1">
  <tr>
    <th>Time</th>
    <th>Main Activity</th>
    <th>Parallel Activity</th>
  </tr>
  <tr> 
    <td>08:30 - 09:00</td>
    <td>Registration</td>
    <td></td>
  </tr>
  <tr>
    <td>09:00 - 09:30</td>
    <td>Opening Remarks</td>
    <td></td>
  </tr>
  <tr>
    <td>09:30 - 10:15</td>
    <td>Keynote talk 1</td>
    <td></td>
  </tr>
  <tr>
    <td>10:15 - 10:45</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>10:45 - 11:30</td>
    <td>Demo Session</td>
    <td>PRAGMA Student Ice Breaking</td>
  </tr>
  <tr>
    <td>11:30 - 12:30</td>
    <td>PRAGMA Update</td>
    <td></td>
  </tr>
  <tr>
    <td>12:30 - 13:30</td>
    <td>Lunch</td>
    <td></td>
  </tr>
  <tr>
    <td>13:30 - 15:30</td>
    <td>PRAGMA Working Group Proposals (3-4 topics)</td>
    <td></td>
  </tr>
  <tr>
    <td>15:30 - 16:00</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>16:00 - 17:30</td>
    <td>Presentation Session 1</td>
    <td>Student Hacking Session 1</td>
  </tr>
  <tr>
    <td>17:30 - 18:30</td>
    <td></td>
    <td>Dinner</td>
  </tr>
  <tr>
    <td>Overnight</td>
    <td></td>
    <td>Student Hacking Session 2</td>
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
    <td>09:45 - 10:15</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>10:15 - 12:00</td>
    <td>PRAGMA Working Group Showcases (3-4 topics)</td>
    <td></td>
  </tr>
  <tr>
    <td>12:00 - 13:30</td>
    <td>Lunch</td>
    <td>Lunch & Steering Committee Meeting</td>
  </tr>
  <tr>
    <td>13:30 - 15:00</td>
    <td>Presentation Session 2</td>
    <td></td>
  </tr>
  <tr>
    <td>15:00 - 15:30</td>
    <td>Coffee break</td>
    <td></td>
  </tr>
  <tr>
    <td>15:30 - 16:30</td>
    <td>Awarding & PRAGMA Working Group Next Plan</td>
    <td></td>
  </tr>
  <tr>
    <td>16:30 - 17:00</td>
    <td>PRAGMA Wrap-up</td>
    <td></td>
  </tr>
  <tr>
    <td>18:00 - 20:00</td>
    <td>Banquet Dinner</td>
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
    width: 100%;
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
    background-color: #4CAF50;
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
    background-color: #4CAF50;
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
    background-color: #45a049;
    transform: scale(1.05);
  }

  .btn.active {
    background-color: #2e7031; /* darker when active */
  }

  /* Hide tables by default */
  .hidden {
    display: none;
  }
</style>
