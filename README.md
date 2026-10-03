# Skip Windows 11 Without a Microsoft Account and Internet

Have you ever setup Windows 11 but it prompts you that you need a Microsoft Account and Internet to be able to complete it?
Turns out there is a workaround for it, and here's how:

<h2>Steps</h2>
<ol>
  <li><b>Press Shift + F10</b> or <b>Press FN + Shift + F10</b></li>
    It wil open up the Command Prompt
  <li>Type the following:<pre><code>oobe\bypassnro</code></pre></li>
    Wait for your device to restart and proceed on the setup
  <li>Press the <b>I don't have internet</b></li>
  <li>Press <b>Continue with limited setup</b></li>
  <li>Proceed with the usual Windows setup, then it's finished</li>
</ol>

<h2>Alternative for Creating a Local Account</h2>
<ol>
  <li><b>Press Shift + F10</b> or <b>Press FN + Shift + F10</b></li>
    It would open up the Command Prompt
  <li>Type the following:<pre><code>start ms-cxh:localonly</code></pre></li>
    It will allow you to create a local user account 
  <li>Go through the typical Windows setup, once done you're good to go</li>
</ol>

<h2>Rufus</h2>
<p>If you're installing a fresh install of Windows 11, then you could
bypass the requirement needed as well as the possibility of being able
to create a local account</p>
<ol>
  <li>Go to Rufus</li>
  <li>Tick the Remove requirements boxes, Create a local username, Disable data collection</li>
  <li>When finished, go through the typical Windows installation and you're done</li>
</ol>

<h2>References</h2>
<a href="https://www.youtube.com/shorts/nDKec_qL1e">HOW TO SKIP WINDOWS 11 SETUP WITHOUT INTERNET! | LaptopFactory</a>
  <br>
<a href="https://www.youtube.com/shorts/ieUaZvZJ_s4">Set Up a Windows Laptop WITHOUT a Microsoft Account | davidbombal</a>
  <br>
<a href="https://4sysops.com/archives/bypass-windows-11-hardware-restrictions-and-install-on-unsupported-pcs-using-rufus-or-flyby11/">Bypass Windows 11 hardware restrictions and install on unsupported PCs using Rufus or Flyby11 | 4sysops</a>  
