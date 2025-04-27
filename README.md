# cs352--assignment-project-1-wireshark-solved
**TO GET THIS SOLUTION VISIT:** [CS352- Assignment: Project 1-Wireshark Solved](https://www.ankitcodinghub.com/product/cs352-assignment-project-1-wireshark-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;83031&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS352-  Assignment: Project 1-Wireshark Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<h1>Objective/Description</h1>
The aim of this lab is to use Wireshark for packet sniffing. Wireshark is an open source software tool that allows you to examine packets captured by any network interface on your machine. We recommend that you first install this software on your personal machine.

Please work through each of the tasks discussed below. Each task will specify material you are required to hand in. You will need to cut several snapshots and put them into a document and convert that document (is possible) to a PDF file. For submission please submit the PDF file (with your NetID as its name) via Sakai.

For presenting your answers

<ul>
<li>Submit <strong>one PDF </strong>document with a summary of all your answers including the images that you have captured.</li>
<li>Be sure to include your name and NetID in your submission</li>
<li>Label or number the answer for each question. For example the answer for 3a should be labeled <strong>3a </strong>or <strong>Question 3 Part a.</strong></li>
<li>Be sure to answer questions</li>
<li>Provide citations for and references used</li>
</ul>
<h1>Software Installation</h1>
See the slides titles <strong>CS352-Summer2021-Wireshark</strong>

<strong>Note 1: This assignment/project is based on the fact that you will use your personal laptop to run Wireshark. Also, the laptop in use is connected to the Internet through a Wi-Fi router (Access point), at home or somewhere else.&nbsp; Note 2: Make sure to clear your web browser’s cache</strong>

<h1>Assignment</h1>
OK, let’s start with Wireshark!

<ul>
<li>Start a capture session using Wireshark. From the main screen of Wireshark, you need to select the interface you are using to connection to the Internet, example: Wi-Fi, see below screenshot</li>
</ul>
Capture traffic when you are opening a web page in your browser. Open the web page <a href="http://www.ox.ac.uk/">http://www.ox.ac.uk</a>. Please save the trace you use in the lab and submit it with your answers. To save go to “File” and select save file (e.g., call it NetID (which is your NetID)).

<ul>
<li>Stop capturing and examine the trace and find the exchange of packets between your machine and the web server (the host providing the web pages to your machine). In the trace you can see many protocols listed. Some of these protocols are called transport protocols. Answer the following:
<ul>
<li>Which transport protocol is used between your machine and the web server?</li>
<li>You will see that other protocols are captured in your trace. One such protocol is HTTP. What is the relationship between the transport protocol you identified and HTTP? c- Type in “http” (without the quotes, and in lower case – all protocol names are in lower case in Wireshark) into the display filter specification window at the top of the main Wireshark window. Then select Apply (to the right of where you entered “http”). This will cause only HTTP messages to be displayed in the packet-listing window. To see the exchange of HTTP messages with the web server, click statistics → flow graph → then check the “limit to display filter” box. Take a snapshot or copy/paste the packets displayed on the monitor (no need to scroll down and copy all).</li>
</ul>
</li>
<li>In the trace you will find IP addresses within the packets. Answer the following:
<ul>
<li>Find an example packet in the trace where the IP address associated with your machine is present. Provide this example packet with your submission (take a screen dump or cut and paste the packet).</li>
<li>We discussed protocol layers in class. Which layer is the IP associated with? Which layer is the transport protocol you identified in sec. 2 a is associated with? Which layer is the HTTP protocol associated with?</li>
</ul>
</li>
</ul>
Make sure to provide your answer in the required sequence. You may use a table like this to answer this section:

<table width="460">
<tbody>
<tr>
<td width="216">Layer</td>
<td width="244">Protocol</td>
</tr>
<tr>
<td width="216"></td>
<td width="244"></td>
</tr>
<tr>
<td width="216"></td>
<td width="244"></td>
</tr>
<tr>
<td width="216"></td>
<td width="244"></td>
</tr>
</tbody>
</table>
<ul>
<li>Let’s examine some MAC information.
<ul>
<li>We discussed the MAC (medium access control) address in class. You can find the MAC address of your machine using ifconfig /all a on unix, Linux, windows, and OSX machines – at the command line. If you are using the WLAN, look for <strong>Physical Address </strong>under</li>
</ul>
</li>
</ul>
<strong>Wireless LAN adapter Wi-Fi</strong>. Take a snapshot for this part, the output should be like this:

<ul>
<li>Can you find the MAC address for your machine in the trace?. What is the MAC address of your machine? Hint: you should click on a message originated from your machine and then click on Ethernet II in the packet details pane to see the MAC address (shown as Src address). (take a screen dump for the Ethernet II details that show this).</li>
<li>What is the 48-bit destination address in the Ethernet frame? Is this the Ethernet address of <a href="http://www.ox.ac.uk/">ox.ac.uk</a> ? (<strong>Hint: the answer is no</strong>).</li>
</ul>
What device has this as its Ethernet address (MAC address)? Based on the answer you will provide, why this the address of this device and not that of the web server that is hosting ox.ac.uk?

<ul>
<li>Answer the following:
<ul>
<li>Before doing this part, start capturing a new trace (make sure that you save the previous trace file).</li>
</ul>
</li>
</ul>
Now, at the command line on your machine, type ping <a href="http://www.ox.ac.uk/">www.ox.ac.uk</a><a href="http://www.ox.ac.uk/">.</a> Did you get 4 replies? If so, stop capturing via Wireshark. Take a snapshot for the output of the ping command.

What does the <strong>time </strong>(in <em>ms</em>) given there (at the command line) refer to? Hence it is related to the delay components we covered in the 1<sup>st </sup>lecture. FYI, you can see the packets resulted from typing ping, captured by the Wireshark. To see these, type ICMP in the filter field.

Take a screen dump or cut and paste the packet that shows these packets. There should be 8 packets.

<ul>
<li>Repeat part a for <a href="http://www.lincoln.ac.nz/">lincoln.ac.nz</a></li>
</ul>
For this part, include screen dumps or cut and paste packets as in a.

Why is the time in <em>ms </em>greater when compared to that in part a? What do you think? You may use a simple equation and one line of description to answer this question.
