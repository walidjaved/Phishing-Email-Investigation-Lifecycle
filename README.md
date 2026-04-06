# Phishing-Email-Investigation-Lifecycle

<h2> Description</h2>
<p><b>This project simulates a phishing-style attack chain against a Windows 11 endpoint and investigates the resulting activity in Splunk Enterprise. The goal of this lab was to build hands-on experience with SOC-style detection engineering, Windows log analysis, and incident investigation workflows.</b></p>

<p>Instead of focusing only on email delivery, this lab focuses on the post-click attacker behavior that defenders are most likely to investigate in a real-world environment, including:</p>


<ul>
  <li>suspicious process execution</li>
  <li>PowerShell abuse</li>
  <li>native Window tool abuse (LOLbins)</li>
  <li>reconnaissance activity</li>
  <li>suspicious parent-child process relationships</li>
  <li>network connections</li>
  <li>endpoint investigation in Splunk</li>
</ul>

<h2>Objectives</h2>
<p>The purpose of this lab was to:</p>
<ol>
  <li>Simulate suspicious user execution after a phishing email</li>
  <li>Forward Windows and Sysmon logs into Splunk</li>
  <li>Create custom detections for phishing-related attacker behaviour</li>
  <li>Investigate suspicious activity like a SOC analyst</li>
  <li>Build a dashboard for triage, investigation, and monitoring</li>
  <li>Document detection engineering and investigative workflow for portfolio use</li>
</ol>

<h2>Tools Used</h2>
<table>
  <tr>
    <th>Tool</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>Virtual Box</td>
    <td>Run Virtual Machines</td>
  </tr>
    <tr>
    <td>Kali Linux</td>
    <td>Attack Machine</td>
  </tr>
    <tr>
    <td>Windows 11 VM</td>
    <td>Victim Machine</td>
  </tr>
    <tr>
    <td>Splunk</td>
    <td>Log Analysis</td>
  </tr>
    <tr>
    <td>Sysmon</td>
    <td>Detailed Windows Logging</td>
</table>
