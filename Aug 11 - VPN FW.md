<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aug 11 - VPN FW</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><p>##<strong>Phase I</strong></p>
<blockquote>
<ul>
<li>Implement Cisco ASA in Ottawa, Toronto on commercial internet link - goal to replace existing VPN connection w/ commercial internet connection</li>
</ul>
<blockquote>
<ul>
<li>Equipment will be setup in HA active/standby architecture, similar to current setup for perimeter f/w</li>
</ul>
</blockquote>
</blockquote>
<p>##<strong>Phase II</strong></p>
<blockquote>
<ul>
<li>Lifecycle replace insulation/choke routers - requires internet outage, must be off-hours</li>
<li>Setup secondary profiles on ASA for DR VPN capability in OTT, TOR</li>
</ul>
</blockquote>
<hr>
<h2 id="aug-11">Aug 11</h2>
<h3 id="zoom-call-roger-dave-darren">- Zoom call, Roger, Dave, Darren</h3>
<p>** Steps for Phase I - Implement VPN/FWs on Commercial Internet</p>
<blockquote>
<ul>
<li>Dave to go on-site and plug cross-over between OTT FWs</li>
<li>Dave to hook up console port to TOR FWs</li>
<li>Darren to copy config from virtual/temp ASA to new FWs</li>
<li>Dave to go back on-site, unplug virtual/temp, plug in new FWs (update config w/ IP addresses?)</li>
<li>Gerald can resume testing of Windows Helo For Business on new connection, ensure split-tunnel configured</li>
</ul>
<blockquote>
<ul>
<li><strong>Once satisfied, ready for cutover</strong></li>
</ul>
</blockquote>
<ul>
<li>Cutover will require an update to the DNS A record to point to the new host, clients should switch to new connection</li>
<li>Will need to schedule similar process for TOT</li>
</ul>
<blockquote>
<ul>
<li><strong>ONCE OTT, TOR IMPLEMENTED END OF PHASE I</strong></li>
</ul>
</blockquote>
</blockquote>
</div>
</body>

</html>
