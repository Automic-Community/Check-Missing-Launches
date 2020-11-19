*Check Missing Launches*
=============


Script to help with an issue that some customer are experiencing: sometimes the launch is not created for a task. 
http://github.com/Automic-Community/Check-Missing-Launches

<!-- List of attached files -->
Contents of Solution Package:

						
								*Check_Missing_Launches.zip
								
						


Documenation and Instructions
---

<div class="ipsType_textblock ipsPad_half description_content"><span><strong class="bbc">Description</strong></span><br />&nbsp;<br />This is a script to help with an issue that some customer are experiencing: sometimes the launch is not created for a task.&nbsp;<br />As it takes some time to notice the issue, the issue my not be addressed in time.<br />So this script was created to help customer check if they have such issue sooner:
<ul class="bbc">
<li><span>If the script completes: no issue</span></li>
<li><span>If the script aborts: there will be a missing launch&nbsp;</span></li>
</ul>
<span><strong class="bbc">Implementation</strong></span><br />&nbsp;<br />This app provide a script. It is recommended to create an Internal Script Uproc with the content of this script. Then it is recommended to execute this script everyday.<br />&nbsp;<br />&nbsp;<br /><span><strong class="bbc">Example of output</strong></span><br />&nbsp;<br />If there is an issue, the uproc will abort and you will have a log as follow:
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="typ">Launch</span><span class="pln"> </span><span class="kwd">not</span><span class="pln"> posted </span><span class="kwd">for</span><span class="pln"> MU</span><span class="pun">=</span><span class="pln">HKLPMSUP01 UPR</span><span class="pun">=</span><span class="pln">UPROC_LONG
&nbsp;
ERROR</span><span class="pun">:</span><span class="pln"> </span><span class="typ">At</span><span class="pln"> least </span><span class="lit">1</span><span class="pln"> task </span><span class="kwd">is</span><span class="pln"> scheduled </span><span class="kwd">and</span><span class="pln"> active but </span><span class="kwd">no</span><span class="pln"> launch </span><span class="kwd">is</span><span class="pln"> planned </span><span class="kwd">or</span><span class="pln"> executing</span><span class="pun">.</span><span class="pln">
&nbsp;
ACTION</span><span class="pun">:</span><span class="pln"> </span><span class="typ">This</span><span class="pln"> script </span><span class="kwd">as</span><span class="pln"> been created </span><span class="kwd">for</span><span class="pln"> ORSYP </span><span class="typ">Forum</span><span class="pln">
&nbsp; &nbsp; &nbsp; &nbsp; </span><span class="typ">To</span><span class="pln"> investigate the issue</span><span class="pun">,</span><span class="pln"> please generate a
&nbsp; &nbsp; &nbsp; &nbsp; uxtrace </span><span class="pun">-</span><span class="pln">option X </span><span class="lit">9</span><span class="pln"> CS</span><span class="pun">-</span><span class="pln"> </span><span class="kwd">and</span><span class="pln"> open a </span><span class="kwd">case</span><span class="pln"> on&nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; the support portal
&nbsp;
WORKAROUND</span><span class="pun">:</span><span class="pln"> </span><span class="typ">Once</span><span class="pln"> the uxtrace </span><span class="kwd">is</span><span class="pln"> taken</span><span class="pun">,</span><span class="pln"> you can force&nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; the creation of the launch </span><span class="kwd">by</span><span class="pln"> updating
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span class="kwd">and</span><span class="pln"> saving the task </span><span class="pun">-</span><span class="kwd">no</span><span class="pln"> change required</span><span class="pun">-<br /><br /></span></pre>
<strong class="title">Target environments:</strong> Windows</div>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
