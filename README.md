# osTicket-Ticket-Lifestyle-Examples
osTicket Lifestyle Examples

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifestyle Examples</h1>
In this lab, we will be creating tickets as end users and observing all the ticket properties and responding to them as help desk professionals
<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

- <h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h1>This tutorial is a follow up to the previous <a href="https://github.com/mchajdecki/osTicket-Post-Installation-Configuration">os Ticket - Post Installation Configuration </a></h1>

- The resources used in this osTicket Ticket Lifecycles continue from the previous tutorial the - osTicket - Post Installation Configuration.
- Log into the osTicket Windows Virtual Machine to continue.

<h2>For the purpose of this tutorial we will be connecting to the osTicket from the links below. Admin/Analayst Login and the End User log in.</h2>

- Admin/Analyst Login Page: <a href="http://localhost/osTicket/scp/login.php">Admin/Analyst Login</a> where you configure settings on the back end for osTicket.
- End Users osTicket URL: <a href="http://localhost/osTicket"> End Users osTicket URL</a> essentially a help desk worker that works on tickets.</a> 

<h3>In this tutorial we will access both portals the Admin and the End user to create tickets as end users and observing all the ticket properties and responding to them as help desk professionals
</h3>

<h3>For an in depth rundown on Microsoft Azure visit this helpful guide <a href="https://github.com/mchajdecki/Microsoft-Azure">Microsoft Azure Full Tutorial</a>

<h2>This tutorial outlines the following</h2>
<ul>

<li><a href="#clean">Clean Up Departments</a></li>
<li><a href="#create">Create Ticket as an End User</a></li>
<li><a href="#observe">Observe Ticket Properties as Agent</a></li>
<li><a href="#change#">Change Agent Permissions</a></li>
<li><a href="#close">Working and Closing Ticket</a></li>
</ul>
</br>


<h1 id="clean"><i>Clean Up Departments</i></h1>
<h2>Before getting started we will log in as Admin and delete the maintance department. The reason for this is when you create tickets it automatically gets assigned to this department and we want the tickets to utilize the departments we created in post installation configuration.</h2>

<p>
  <ol type="1">
     <li>Navigate to and Log into the Admin/Analyst section of osTicket to begin <a href="http://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a></li></li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Post-Installation-Configuration/blob/f7d3512b9790ed44176901a82cb1dbd26ef8e795/images/Slide-1.jpg" alt="Slide_1"/>
</p>
<br>
<hr>


<p>
  <ol type="1">
     <li>Click on the Admin button to get to the Agent Panel.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Post-Installation-Configuration/blob/a2ef753363ca16ad18d34ec7dd51c6016624500c/images/Slide_40.jpg" alt="Slide_40"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
     <li>Go to Agents --> Departments.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Post-Installation-Configuration/blob/cef9fd37861ba4ace9c33b4304c85bbb75ceaea1/images/Slide_41.jpg" alt="Slide_41"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
     <li>Check box to select maintance department and click on Delete.</li>
    <li>Once the pop up message appears select Yes, Do it! to confirm deletio of the selected departments.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Post-Installation-Configuration/blob/da5676eb5d72542e926dba3df9ef5000d69552e8/images/Slide_42.jpg" alt="Slide_42"/>
</p>
<br>
<br>
<hr>


<h1 id="create"><i>Create Ticket as an End User</i></h1>
<h2>Showing a perspective of an End user having an issue and creating a ticket to get it resolved.</h2>

<p>
  <ol type="1">
    <li>As the End Users in this osTicket URL: <a href="http://localhost/osTicket">My help desk Support Ticket System.</a>
      <li>Click Open a New Ticket.</li>
     <li>Fill in the form to open a new ticket.</li>
    <li>The ticket help topic should be general inquiry and the Issue summary should state; The entire mobile/online banking system is down with a brief description of the issue.</li>
     <li>Click Create Ticket.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/28589c8a81d78341bdc0c278a4024fbbbb7e7e64/images/Slide-1.jpg" alt="Slide_1"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
     <li>Support ticket request created message will display.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/56fc45cc60a945a709d7188c0be2e1d5829116b8/images/Slide-2.jpg" alt="Slide_2"/>
</p>
<br>
<nr></nr>
<hr>

<h1 id="observe"><i>Observe Ticket Properties as Agent.</i></h1>
<h2></h2>

<p>
  <ol type="1">
    <li>Go into the<a href="http://localhost/osTicket/scp/login.php">Admin/Analyst Login Portal</a> and login as agent John.
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/4619bf05410d1cd6b565091b7855e1ab4d4221b5/images/Slide-3.jpg" alt="Slide_3"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Navigate to Tickets and select the ticket created by the End user.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/c08055f5bbde49868daa4f3bb004f96f157614b2/images/Slide-4.jpg" alt="Slide_4"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Observe the ticket as Agent John - (view only)</li>
    <li>Notice how you cant make changes to the ticket or updates since your permissions as Agent John are for view only.</li>
    <li>Only thing you can do is post an internal note. Type in a not of your choice and click post note to test.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/c310a719646ea32914e1ac64e50fdbc4df8f00cc/images/Slide-5.jpg" alt="Slide_5"/>
</p>
<br>
<hr>

<h1 id="change"><i>Change Agent Permissions.</i></h1>
  <ol type="1">
    <li>In the next step we will change Agent Johns permissions so he can access more features of the created ticket.</li>
    <li>Access the Admin panel by clicking on the Admins Panel button.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/48b79be3ff4e80f40b157ed5bdc95d40f4106298/images/Slide-6.jpg" alt="Slide_6"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Once in the admin panel click on Agents to continue.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/dce8477a36be1a6eb22c5750575064b1a701d29b/images/Slide-7.jpg" alt="Slide_7"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Click on the agent you want to make changes to as Admin.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/df26d0f3bbf4551f8844ddeb8fabaddba3638ac7/images/Slide-8.jpg" alt="Slide_8"/>
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>Click on access and then select more access for the agent to make changes and have more options with the selected tickets.</li>
    <li>Save the changes.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/ead4d90640fa173f51bc6e5fa89b94389fbac550/images/Slide-9.jpg" alt="Slide_9"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Log out for changes to take place.</li>
    <li>Log back in to observe the ticket with granted permissions.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/c6fb58b5673e4b8f3f93c9b3d296dce1b79d2d67/images/Slide_10.jpg" alt="Slide-10"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Click back on the ticket to observe it with the new granted permissions.</li>
    <li>Notice all the editable and changeable options.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/2783fdc4a36c3d2e13fa59860bcb4d4a9606500c/images/Slide_11.jpg" alt="Slide-11"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>As John we can now make crucial changes to the ticket such as; prority, department, assigned to , SLA plan , Help topic and due date.</li>
    <li>Observe the ticket changes and updates after granted permissions.</li>
    <li>Since one of the changes was to assign the ticket - as agent John we cant see the ticket anymore. Unless again we change more permissions in the Admin panel.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/1795d6bc087c0aa9923bec0a030f6b8990c92f22/images/Slide_12.jpg" alt="Slide-12"/>
</p>
<br>
<br>
<hr>


<h1 id="close"><i>Working and Closing tickets.</i></h1>
<h2></h2>

<p>
  <ol type="1">
     <li>Navigate to the Admin/Analyst section of osTicket and log in as the agent the ticket was assigned to; in my example it is agent Mark Smith<a href="http://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a></li></li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/a9147fffa783e15fb51e2c3b79e53fd0d01cbfb0/images/Slide_13.jpg" alt="Slide_13"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>As agent Mark Smith we can see the ticket that we were assigned.</li>
    <li>Click on the ticket.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/c52c27134bd00db7d42793f8ff142bdc9f3e2520/images/Slide_14.jpg" alt="Slide_14"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Observe and look at the details of the encountered problem and notes or updates associated with the ticket by other agents or administrators.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/60f0532e9c0785bccf463ae8e696465132046a18/images/Slide_15.jpg" alt="Slide_15"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li>Update the ticket and the way the problem was solved.< .</li>
      <li>As an example for this ticket we "Identified the outage as a temporary system error and brought the online banking back online by simply restarting the primary web service."</li>
      <li>Note that every time you update the ticket, the user gets a copy and they can respond to it as well.</li>
      <li>We can post the reply and change the ticket status to closed or resolved as you see highligted.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osTicket-Ticket-Lifecycle-Examples/blob/96e58f199e637cf10e79c97f0573e5995526305a/images/Slide_16.jpg" alt="Slide_16"/>
</p>
<br>
<hr>

<p>
  <ol type="1">
    <li></li>
  </ol>
</p>
<p>
<img src="" alt="Slide_17"/>
</p>
<br>
<hr>









