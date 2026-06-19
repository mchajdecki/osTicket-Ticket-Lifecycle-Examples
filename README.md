# osTicket-Ticket-Lifestyle-Examples
osTicket Lifestyle Examples

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifestyle Examples</h1>
In this lab, we will be creating tickets as end users and observing all the ticket properties and responding to them as help desk professionals
<br/>


<h2>Video Demonstration</h2>

- ### [YouTube: osTicket Post Installation Configuration](https://www.youtube.com)

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
<li><a href="#"></a></li>
<li><a href="#"></a></li>
<li><a href="#"></a></li>
<li><a href="#"></a></li>
<li><a href="#"></a></li>
</ul>
</br>


<h1 id="clean"><i>Clean Up Departments.</i></h1>
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


<h1 id="create"><i>Create Ticket as an End User.</i></h1>
<h2></h2>

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



