<h2>Obtaining Access to Summit for Training Events</h2>

Please follow the steps below to request access to Summit for OLCF training events.

<h3>Step 1: Fill out and submit an <a href="https://www.olcf.ornl.gov/for-users/documents-forms/olcf-account-application"><b>OLCF Account Application Form</b></a></h3>
Enter the requested information into the form. For "Project Information", enter the following:
<a href="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_1.png"><img src="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_1.png" /></a>

<!--
For "Project Information", enter the following:
<a href="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_2.png"><img src="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_2.png" /></a>
-->

For "Account Information", enter the following:
<a href="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_3.png"><img src="https://www.olcf.ornl.gov/wp-content/uploads/2019/01/Ascent_Account_Application_3.png" /></a>

><strong>NOTE:</strong> After submitting your application, it will need to pass through the approval process. This can take several days so please request access early. Once approved, each project member will be sent (overnight) an RSA token for 2-factor authentication to Summit. Once this is received, you will need to set up a quick (3-minute) video call with OLCF to verify that you, in fact, did receive the token.

<h3>Step 2: Authenticating to OLCF Systems</h3>
All OLCF systems currently employ two-factor authentication only. To login to OLCF systems, an RSA SecurID<sup>®</sup> Token (fob) is required.

<img class="kb-img-right" src="https://www.olcf.ornl.gov/wp-content/uploads/2012/03/rsa_securid_fob.gif" alt="Image of an RSA SecudID fob" width="40%" />

<h4>Activating a new SecurID<sup>®</sup> Token (fob)</h4>
Follow the steps described below to set up your new SecurID Token (fob).

<br>

<ol>
 	<li>Initiate an SSH connection to home.ccs.ornl.gov using your OLCF username.
(i.e., <code>ssh userid@home.ccs.ornl.gov</code>)</li>
 	<li>When prompted for a PASSCODE, enter the 6 digits displayed on your token.</li>
 	<li>When asked if you are ready to set your PIN, answer with "y".</li>
 	<li>You will then be prompted to enter a PIN. Enter a 4- to 8-character alphanumeric PIN you can remember. You will then be prompted to re-enter your PIN.</li>
 	<li>A message will appear stating that your PIN has been accepted. Press enter to continue.</li>
 	<li>Finally, you will be prompted again with "Enter PASSCODE". This time enter both your PIN <u>and</u> the 6 digits displayed on your token before pressing enter.</li>
 	<li>Your PIN is now set and you are logged into home.ccs.ornl.gov.</li>
</ol>

If you prefer to watch a video to learn how to set a PIN for your new RSA token, please see this <a href="https://vimeo.com/229862977">link</a> from our Vimeo channel.

<h4>Using a SecurID<sup>®</sup> Token (fob) to Log In to Summit</h4>

Initiate a connection to Summit using your OLCF username: <code>ssh userid<i></i>@summit.olcf.ornl.gov</code>

When prompted for your PASSCODE, enter your PIN followed by the 6 digits shown on your SecurID<sup>®</sup> token before pressing enter. For example, if your pin is <code>1234</code> and the 6 digits on the token are <code>000987</code>, enter <code>1234000987</code> when you are prompted for a PASSCODE.
<div class="kb-warning"><strong>Warning:</strong> The 6-digit code displayed on the SecurID token can only be used once. If prompted for multiple PASSCODE entries, always allow the 6-digit code to change between entries. Re-using the 6-digit code can cause your account to be automatically disabled.</div>



<hr>
