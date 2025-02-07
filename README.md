<h1>osTicket Lab 3: Ticket Creation & Resolution</h1>

<h2>Project Summary</h2>
<p>
  In this final segment of my osTicket labs, I role-played multiple ticket scenarios. 
  By logging in as both end users (e.g., Karen, Ken) and help desk agents (e.g., John, Jane), 
  I demonstrated how tickets move from creation to resolution, incorporating SLA changes, 
  department reassignment, and agent collaboration.
</p>

<ul>
  <li><strong>Focus Areas:</strong>
    <ul>
      <li>Opening tickets as different end users</li>
      <li>Assigning &amp; updating ticket properties (SLA, help topic, department)</li>
      <li>Resolving and closing tickets</li>
    </ul>
  </li>
  <li><strong>Scenarios:</strong>
    <ul>
      <li>Business Critical Outage (misclassified by the user, corrected by agent)</li>
      <li>General Inquiry → Low priority → Quick fix</li>
      <li>Personal Computer Issue from a high-level executive (CFO)</li>
    </ul>
  </li>
</ul>

<hr />

<h2>Steps & Screenshots</h2>
<ol>
  <li>
    <strong>Archiving the Maintenance Department</strong><br />
    Before creating tickets, I archived an unused “Maintenance” department 
    under <em>Agents &gt; Departments</em>, simplifying our department structure. 
    <br /><br />
    <p align="center">
      <img src="https://i.imgur.com/gPRCc87.png" alt="Archiving department" width="600" />
      <br />
      <em>Figure 4.1 – Maintenance department set to ‘Archived.’</em>
    </p>
  </li>
  <br />

  <li>
    <strong>Ticket One: Business Critical Outage</strong><br />
    <ul>
      <li><em>User Karen</em> logs into the End User portal, opens a new ticket 
          describing “mobile online banking is down,” but mistakenly picks <em>Report a Problem</em> 
          instead of <em>Business Critical Outage</em>.</li>
          <p align="center">
      <img src="https://i.imgur.com/Qx4PSiH.png" alt="Karen ticket" width="600" />
    </p> <br />
      <li><em>Agent John</em> logs in and sees the new ticket. He changes SLA to <code>Sev-B</code>, 
          corrects the Help Topic, and assigns it to the <code>Online Banking</code> team.</li>
        <p align="center">
      <img src="https://i.imgur.com/Zq6O8kW.png" alt="John Agent" width="600" />
      <img src="https://i.imgur.com/bE7NZEw.png" alt="John Agent" width="600" />
      <br />
    </p> 
      <li><em>Agent Jane</em> (member of Online Banking) reassigns the ticket to herself, 
          updates Karen with the fix, and resolves the ticket.</li>
       <p align="center">
      <img src="https://i.imgur.com/uNACsFj.png" alt="Jane agent" width="600" />
      <img src="https://i.imgur.com/lGZoM21.png" alt="Jane agent" width="600" />
      <br />
      <img src="https://i.imgur.com/n0Ya0ka.png" alt="Ticket details" width="600" />
      <br />
      <em>Figure 4.2 – Observing the first ticket’s properties and reclassification.</em>
    </p>
     </ul>
  </li>
  <br />

  <li>
    <strong>Ticket Two: General Inquiry (Adobe Software Issue)</strong><br />
    <ul>
      <li><em>User Ken</em> opens a ticket labeled <em>General Inquiry</em> about the accounting department being unable to use Adobe software.</li>
      <p align="center">
      <img src="https://i.imgur.com/x8Skb7F.png" alt="User Ken" width="600" />
      <br />
     </p> 
      <li><em>Agent John</em> responds to request more info. Ken says only 2 people are affected, so John sets SLA to <code>Sev-C</code>. 
          Ken tries a system reboot, which fixes the issue. John documents that and closes the ticket.</li>
        <p align="center">
      <img src="https://i.imgur.com/rG1CCVP.png" alt="Agent John" width="600" />
      <br />
     </p> 
    <p align="center">
      <img src="https://i.imgur.com/pvO220i.png" alt="Adobe issue ticket" width="600" />
      <br />
      <em>Figure 4.3 – Low-priority ticket with quick resolution.</em>
    </p>
  </li>
      </ul>
  <br />

  <li>
    <strong>Ticket Three: Personal Computer Issue (CFO)</strong><br />
    <ul>
      <li><em>User Karen</em> opens another ticket about the CFO’s laptop not powering on, selecting <em>Personal Computer Issues</em>.</li>
       <p align="center">
      <img src="https://i.imgur.com/RARgivE.png" alt="Karen 2nd ticket" width="600" />
    </p> <br />
      <li><em>Agent John</em> sees it’s for the CFO, sets priority to <em>Emergency</em> and SLA to <code>Sev-B</code>, 
          then assigns the ticket to himself. The root cause was a faulty charger, so once replaced, he resolves the ticket.</li>
     <p align="center">
      <img src="https://i.imgur.com/fV3WRmq.png" alt="Agent John 2" width="600" />
       <img src="https://i.imgur.com/DaJpnk7.png" alt="Agent John 2" width="600" />
    </p> <br />
    <p align="center">
      <img src="https://i.imgur.com/CyKqZxU.png" alt="Emergency CFO ticket" width="600" />
      <br />
      <em>Figure 4.4 – High-priority ticket assigned to John for quick turnaround.</em>
    </p>
  </li>
  </ul>
  <br />

  <li>
    <strong>Reviewing Closed Tickets</strong><br />
    Under the Agent Panel’s <em>Tickets &gt; Closed</em> section, I verified the resolved tickets. 
    This confirms each scenario was properly documented and closed.
    <br /><br />
    <p align="center">
      <img src="https://i.imgur.com/tRSF6pQ.png" alt="Viewing closed tickets" width="600" />
      <br />
      <em>Figure 4.5 – Confirming all tickets have been resolved or closed.</em>
    </p>
  </li>
</ol>

<hr />

<h2>Conclusion</h2>
<p>
  These three ticket scenarios illustrate how osTicket handles different priorities 
  (Business Critical vs. General Inquiry vs. Personal Computer Issue). Agents can reclassify tickets, 
  change SLAs, or pass them to different teams as needed. Overall, osTicket’s structure 
  and my prior configurations make for an efficient help desk workflow.
</p>
