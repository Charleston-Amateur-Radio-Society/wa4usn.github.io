---
layout: page
title: Net Schedule
permalink: /cars-nets/
---

<p></p>

<style>
.nets-notice {
  background: #f8f9fa;
  border-left: 4px solid #4a7c59;
  padding: 0.75rem 1rem;
  margin-bottom: 1.5rem;
  font-size: 0.9rem;
  color: #444;
  border-radius: 0 4px 4px 0;
}
.nets-notice strong { color: #2d5a3d; }

.nets-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.9rem;
  margin-bottom: 1rem;
}
.nets-table thead tr {
  background: #2d5a3d;
  color: #fff;
}
.nets-table thead th {
  padding: 0.65rem 0.85rem;
  text-align: left;
  font-weight: 600;
  letter-spacing: 0.03em;
  white-space: nowrap;
}
.nets-table tbody tr {
  border-bottom: 1px solid #e0e7e2;
}
.nets-table tbody tr:nth-child(even) {
  background: #f4f8f5;
}
.nets-table tbody tr:hover {
  background: #e8f2ec;
}
.nets-table td {
  padding: 0.7rem 0.85rem;
  vertical-align: top;
  color: #333;
}
.nets-table td.day {
  font-weight: 700;
  color: #2d5a3d;
  white-space: nowrap;
}
.nets-table td.time {
  white-space: nowrap;
  font-variant-numeric: tabular-nums;
}
.nets-table td.freq {
  font-family: monospace;
  font-size: 0.85rem;
  white-space: nowrap;
}
.net-tag {
  display: inline-block;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  padding: 0.15rem 0.45rem;
  border-radius: 3px;
  margin-left: 0.4rem;
  vertical-align: middle;
  text-transform: uppercase;
}
.tag-ares     { background: #d4edda; color: #155724; }
.tag-digital  { background: #cce5ff; color: #004085; }
.tag-directed { background: #fff3cd; color: #856404; }
.tag-skywarn  { background: #f8d7da; color: #721c24; }
.tag-emcomm   { background: #e2d9f3; color: #432874; }
.tag-training { background: #fce4ec; color: #880e4f; }
.tag-ssb      { background: #d1ecf1; color: #0c5460; }

@media (max-width: 650px) {
  .nets-table, .nets-table thead, .nets-table tbody,
  .nets-table th, .nets-table td, .nets-table tr {
    display: block;
  }
  .nets-table thead tr {
    position: absolute;
    top: -9999px;
    left: -9999px;
  }
  .nets-table tbody tr {
    border: 1px solid #cde0d4;
    border-radius: 6px;
    margin-bottom: 0.75rem;
    padding: 0.5rem;
  }
  .nets-table td {
    padding: 0.25rem 0.5rem;
  }
  .nets-table td::before {
    content: attr(data-label) ": ";
    font-weight: 700;
    color: #2d5a3d;
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }
}
</style>

## Net Schedule

<div class="nets-notice">
  <strong>Note:</strong> All nets are held on the linked repeaters unless otherwise noted.
  When using the linked repeaters, wait a second after pushing the PTT button — speaking too soon will cut off your first word or two.
</div>

<table class="nets-table">
  <thead>
    <tr>
      <th>Day</th>
      <th>Time</th>
      <th>Net Name</th>
      <th>Frequency</th>
      <th>Mode</th>
      <th>Contact</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="day" data-label="Day">Sunday</td>
      <td class="time" data-label="Time">8:00 PM</td>
      <td data-label="Net">Lowcountry ARES Net <span class="net-tag tag-ares">ARES</span></td>
      <td class="freq" data-label="Frequency">Linked Repeaters</td>
      <td data-label="Mode">FM Voice</td>
      <td data-label="Contact">N8BKN</td>
      <td data-label="Notes">Joins Statewide ARES at 8:20 PM. Open to non-ARES members — a great way to meet emergency operators.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Sunday</td>
      <td class="time" data-label="Time">8:30 PM</td>
      <td data-label="Net">2m Weak Signal Digital Net <span class="net-tag tag-digital">Digital</span></td>
      <td class="freq" data-label="Frequency">145.700 USB</td>
      <td data-label="Mode">Contestia 64/1000</td>
      <td data-label="Contact">AJ4UQ</td>
      <td data-label="Notes">Reaches FL and NC. Use a horizontally-polarized antenna aimed at FM02at. Set Fldigi to use RSID.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Tuesday</td>
      <td class="time" data-label="Time">8:00 PM</td>
      <td data-label="Net">TARC 2m Net <span class="net-tag tag-directed">Directed</span></td>
      <td class="freq" data-label="Frequency">Linked Repeaters</td>
      <td data-label="Mode">FM Voice</td>
      <td data-label="Contact">K4TCP</td>
      <td data-label="Notes">Informal directed net with rotating net controls.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Tuesday</td>
      <td class="time" data-label="Time">9:00 PM</td>
      <td data-label="Net">SKYWARN Net <span class="net-tag tag-skywarn">SKYWARN</span></td>
      <td class="freq" data-label="Frequency">Linked Repeaters</td>
      <td data-label="Mode">FM Voice</td>
      <td data-label="Contact">—</td>
      <td data-label="Notes">Practice net for hurricane season and other weather events.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Wednesday</td>
      <td class="time" data-label="Time">8:00 PM</td>
      <td data-label="Net">2m Weak Signal Digital Net <span class="net-tag tag-digital">Digital</span></td>
      <td class="freq" data-label="Frequency">145.700 USB</td>
      <td data-label="Mode">Contestia 64/1000</td>
      <td data-label="Contact">AJ4UQ</td>
      <td data-label="Notes">Same format as Sunday's digital net.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Thursday</td>
      <td class="time" data-label="Time">9:00 AM</td>
      <td data-label="Net">Statewide Hospital Practice Net <span class="net-tag tag-emcomm">EmComm</span></td>
      <td class="freq" data-label="Frequency">SCHEART Repeaters</td>
      <td data-label="Mode">FM Voice</td>
      <td data-label="Contact">—</td>
      <td data-label="Notes">Use Awendaw, Wallace VHF, or Whitehall repeaters. Individual check-ins taken at end of net.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Thursday</td>
      <td class="time" data-label="Time">8:00 PM</td>
      <td data-label="Net">Newcomers Net <span class="net-tag tag-training">Training</span></td>
      <td class="freq" data-label="Frequency">Linked Repeaters</td>
      <td data-label="Mode">FM Voice</td>
      <td data-label="Contact">KK4WWV</td>
      <td data-label="Notes">A friendly net to practice being net control. Contact KK4WWV if you'd like to try running it.</td>
    </tr>
    <tr>
      <td class="day" data-label="Day">Daily</td>
      <td class="time" data-label="Time">7:00 PM</td>
      <td data-label="Net">Carolina SSB Net <span class="net-tag tag-ssb">SSB</span></td>
      <td class="freq" data-label="Frequency">3.915 LSB</td>
      <td data-label="Mode">SSB Voice</td>
      <td data-label="Contact">—</td>
      <td data-label="Notes">See <a href="http://www.scssb.net/">scssb.net</a> for more information.</td>
    </tr>
  </tbody>
</table>
