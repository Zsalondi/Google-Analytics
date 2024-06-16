<p align="center">
<img src="https://i.imgur.com/B9CC1Sv.png" alt="osTicket logo"/>
</p>

<h1>Google Analytics: Finding Key Metrics</h1>
This tutorial outlines how to explore metrics in a Google Analytics demo account by reviewing a scenario with metrics of interest, finding the values for those metrics, and recording the results. 
The metrics will be used to analyze information such as customer engagement, monetization, and to identify trends.<br />


<!---<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) --->

<h2>Scenario</h2>

As a new marketing associate at Google, you have been asked to familiarize yourself with the metrics in Google Analytics that are available for the Google Merchandise Store. To help you do this, your manager has given you a list of metrics for user acquisition, engagement, and monetization that you can view under the Life cycle section of the tool. Normally, someone reviews these metrics on a monthly basis. Since this has been incorporated into your training assignment, everyone on the team is thrilled that you’ll be helping to get some real work done!

<h2>Tools Used </h2>

- Google Analytics 4 property: Google Merchandise Store (web data)

<h2>Step 1: Access the Google Analytics demo account</h2>
<p>https://analytics.google.com/analytics/web/demoAccount?appstate=/p213025502</p>
<img src="https://i.imgur.com/uy1deJs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Step 2: Set the month for the time frame </h2>
<p>
Navigate to Reports to locate and click the date range, and then select Custom.</p>
<img src="https://i.imgur.com/gW5bgZx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p>With the start date highlighted, scroll up and select January 1 of the current year on the calendar. Next, click to highlight the end date and scroll up to select January 31 of the current year.</p>
<p> <img src="https://i.imgur.com/4mE6R8W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Step 3: Find Acquisition metrics</h2>
<p>
Next find the total number of new users and the number and percentage of new users who arrive at the Google Merchandise Store after using these search engines:
<ul>
  <li>Google</li>
  <li>Bing</li>
  <li>YouTube</li>
  <li>Baidu</li>
</ul></p>
<br />

<p> Browse the data under Life cycle > Acquisition to find where you can locate the search information, and record the total new users and number of new users for each search engine. </p>
<p>
<img src="https://i.imgur.com/HUfJZEf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/sCatPit.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<p> Then, calculate the percentage of new users from each search engine. </p>
<p>
<img src="https://i.imgur.com/KINLE2i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Step 4: Find Engagement metrics</h2>
<p>
The manager asked for the total users for the following events:
<ul>
  <li>session_start</li>
  <li>begin_checkout</li>
  <li>remove_from_cart</li>
  <li>purchase</li>
</ul></p>

<p>Browse the data under Life cycle > Engagement to find each of the events, and record the values for total users. Also, calculate and record the following as insights for your manager:
<ul>
<b>Number of users with cart abandonment = </b>
<li>(total users for begin_checkout) − (total users for purchase)</li> <br />
<b>Sales conversion rate =</b> 
<li>[(total users for purchase) / (session_start)] x 100 </li>
</ul>
</p>
<br />

<p>Use the drop-down for Rows per page and select 50 so you can view all the events on a single page.</p>
</p>
<p>
<img src="https://i.imgur.com/NPk12kI.png" height="80%" width="80%" alt=""/>
</p>
<p>
<img src="https://i.imgur.com/oYkdrSU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Step 5: Find Monetization metrics</h2>
<p>
The manager has asked for the total revenue, the number of first-time buyers, and the top three best-selling items. <br />

Browse the data under Life cycle > Monetization to find the revenue amounts and top three best-selling items. Record the information. 
</p>
<p>
<img src="https://i.imgur.com/k0Psy5O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />




<p>
Tickets are directed through various departments within the help desk, each of which can be customized with its own set of settings.
</p>
<p>
<img src="https://i.imgur.com/jj8Dfub.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
A new department named 'System Administrators' has been added.</p>
<p>
<img src="https://i.imgur.com/HirGRt3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Teams enable grouping of Agents from various Departments to address specific issues or users, organized through Help Topics or Ticket Filters. Navigate to 'Agents' > 'Teams' > 'Add New Team' to create one.</p>
<p>
<img src="https://i.imgur.com/cXAdRac.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Enter the necessary details for the team.</p>
<p>
<img src="https://i.imgur.com/I1zQPbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
To add Agents to the team, click on their names from the Agent list and click on 'Create Team'.</p>
<p>
<img src="https://i.imgur.com/YhNNTkm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Enable ticket creation by anyone by going to 'Settings' > 'Users'.</p>
<p>
<img src="https://i.imgur.com/NLJkcDB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Ensure the option 'Require registration and login to create tickets' is unchecked.</p>
<p>
<img src="https://i.imgur.com/xtczToC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next, we'll set up agents with access to the help desk, tasked with responding to and resolving tickets.</p>
</p>
<p>
<img src="https://i.imgur.com/yCoKXqL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>Navigate to 'Agents' > 'Add New Agent' to proceed.
</p>
<p>
<img src="https://i.imgur.com/nORAqaN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Create an agent named 'Jane Doe' and establish a password for her account.<p>
<img src="https://i.imgur.com/IDGIqAB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<img src="https://i.imgur.com/ya0dQoF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Assign department and role access to agents as needed.</p>
<p>
<img src="https://i.imgur.com/EeIzwD5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We can also assign the agent to a team that was previously created.</p>
<img src="https://i.imgur.com/PQnuiAN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/nprHnpt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Another agent named John Doe was also created.</p>
<p>
<img src="https://i.imgur.com/HsxSEOF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
"Next, we'll add users to our directory. Users can register an account to submit tickets and monitor their status.</p>
<p>
<img src="https://i.imgur.com/PhHCtqh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/5hobfZn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Verify that the new user, Karen Kim, has been added to the user directory.</p>
<p>
<img src="https://i.imgur.com/5zjSeyX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now, let's proceed to set up the Service Level Agreement (SLA).</p>
<p>
<img src="https://i.imgur.com/T2d02Kp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p> Navigate to 'Admin Panel' > 'Manage' > 'SLA Plans' and select 'Add New SLA Plan'.
</p>
<p>
<img src="https://i.imgur.com/Fuwxibl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
In osTicket, you can create unlimited SLA Plans. These plans define the expected timeframe for resolving tickets, as set by the help desk administrator.</p>
<p>
<img src="https://i.imgur.com/3P4jOEu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We've established three SLA plans, each with different severity levels and response times. 
</p>
<p>
<img src="https://i.imgur.com/pIH3ULS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>Next, let's set up the help topics. Navigate to Manage > Help Topics in the Admin Panel and select 'Add New Help Topic'.
</p>
<p>
<img src="https://i.imgur.com/4FXCmkp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>For this exercise, let's create four additional help topics: Business Critical Outage, Personal, Computer Issues, Equipment Request, and Password Reset.</p>
<p>
<img src="https://i.imgur.com/NJkC8wN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
<img src=https://i.imgur.com/dIbrzLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>As we conclude this lab, we've laid the groundwork for our support system. In the upcoming lab, we'll delve into creating, triaging, and resolving tickets, applying what we've built so far.</p>
