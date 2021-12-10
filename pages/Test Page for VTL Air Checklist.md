---
title: Test Page for VTL Air Checklist
permalink: /vtl-air/checklist
description: ""
published: true
---

### VTL (Air) Travel Checklist


<html>
<head>
<meta charset="utf-8">
<title>Test Accordion</title>

<style>
	
input {
    display: none;
}

label {
    display: block;    
    padding: 10px 30px;
    margin: 0 0 1px 0;
    cursor: pointer;
    background: #153855;
    border-radius: 3px;
    color: #FFFFFF;
    transition: ease .5s;
	position: relative;
}

label:hover {
    background: #346f9e;
}

label::after {
	font-family: "Font Awesome 5 Free";
	content: '\271A';
	font-weight: bold;
	font-size: 22px;
	position: absolute;
	right: 10px;
	top: 6px;
}

input:checked + label::after {
	content: '\2716';
}

.content {
    background: #FFFFFF;
    padding: 10px 25px;
    margin: 0 0 1px 0;
    border-radius: 3px;
}

input + label + .content {
    display: none;
}

input:checked + label + .content {
    display: block;
}
  
</style>
</head>
</html>

<p style="font-size:18px; line-height:1.4; margin-top:10px; margin-bottom:0px;"><b>For all travellers arriving in Singapore via designated VTL flights including the following:</b></p>

<p style="font-size:18px; line-height:1.4; margin-top:10px; margin-bottom:0px;"><span style="font-size:25px; color:green;"><b>&#10003;</b></span>&nbsp;<b>Singapore Citizens</b> and <b>Permanent Residents ("SC/PRs")</b></p>

<p style="font-size:18px; line-height:1.4; margin-top:10px; margin-bottom:0px;"><span style="font-size:25px; color:green;"><b>&#10003;</b></span>&nbsp; <b>Holders of a Singapore-issued Long-Term Pass ("LTPHs")</b> (<i>i.e. Holders of Work Pass issued by the Ministry of Manpower, Student’s Pass issued by the Ministry of Education, or Long-Term Visit Pass issued by the Immigration & Checkpoints Authority</i>)</p>

<p style="font-size:18px; margin-top:10px; margin-bottom:30px;"><span style="font-size:25px; color:green;"><b>&#10003;</b></span>&nbsp; <b>Short-term Visitors ("STVs")</b> (i.e. travellers who are not SC/PRs or LTPHs)</p>

<p style="font-size:18px; line-height:1.4; margin-top:10px; margin-bottom:0px;"><b>Not allowed to enter Singapore via VTL (Air):</b></p>

<p style="font-size:18px; line-height:1.4; margin-top:10px; margin-bottom:0px;"><span style="font-size:25px;  color:red;"><b>&#10005;</b></span> &nbsp; Travellers arriving in Singapore by bus via the Causeway. Fully vaccinated travellers who intend to enter Singapore from Malaysia via the Causeway should check the <a href="/vtl-land/overview" target="_blank">Vaccinated Travel Lane (Land)</a> for more details.</p>
<p style="font-size:18px; margin-top:10px; margin-bottom:0px; line-height:1.4;"><span style="font-size:25px; color:red;"><b>&#10005;</b></span> &nbsp; Non-Malaysian male Work Permit or S Pass workers in the Construction, Marine shipyard or Process (CMP) Sector</p>
<p style="font-size:18px; margin-top:10px; margin-bottom:0px; line-height:1.4;"><span style="font-size:25px; color:red;"><b>&#10005;</b></span> &nbsp; Workers staying in dormitories</p>
<p style="font-size:18px;margin-top:10px;margin-bottom:0px; line-height:1.4;"><span style="color:red; font-size:30px;">&#9888;</span>&nbsp; <b>[If ALL applicable requirements below are not met]</b> SC/PRs will be subjected to prevailing Stay-Home Notice and testing requirements. All other travellers may be denied entry into Singapore. If you are not eligible for the VTL, refer to the <a href="/arriving/overview" target="_blank">Travelling to Singapore</a> page for the available non-VTL lanes.</p>
<p style="font-size:18px; margin-top:10px;margin-bottom:0px;  line-height:1.4;"><span style="color:black; font-size:25px;"><b>&#9997;</b></span> &nbsp; Travellers may check against the box (&#9744;) for completed actions.</p>


<div style="background: linear-gradient(90deg, #072b4b, #61788c); border-left:10px #072b4b solid; color: #FFFFFF; font-size: 18px; line-height: 28px; padding: 15px 20px 15px 20px;	margin: 20px 0px 20px 0px;"><b>Stage 1: Before Travelling to Singapore</b></div>

<div style="padding:10px 10px 5px 10px; margin-bottom:10px; line-height:1.5; background-color:#f8f8f8; font-size:18px;">
	<p style="font-size:18px; margin-bottom: 10px; line-height:1.5;">
&#9744;&nbsp;<b>(A) Obtain an accepted proof of vaccination</b></p>
</div>
<div style="position: relative;width: 100%;overflow: hidden;padding-top: 56.25%; margin-bottom:20px;"> 
  <iframe style="position: absolute;top: 0;left: 0;bottom: 0;right: 0; width: 100%; height: 100%; border: none;" src="https://www.checkfirst.gov.sg/c/747b8567-273f-4193-a46e-fa1d06f47c16"></iframe>
</div>


<div style="padding:10px 10px 5px 10px; margin-bottom:10px; line-height:1.5; background-color:#f0f0f0; font-size:18px;">
	<p style="font-size:18px; margin-bottom: 10px; line-height:1.5;">
&#9744;&nbsp;<b>(B) Verify your proof of vaccination</b>
<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px;">Some QR codes/vaccination certificates can be verified by travellers themselves before application. Travellers are strongly encouraged to verify these using the verification tools below.</p>
<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px;">Once you have verified them to be valid, proceed to the next step (Step C).</p>
<input type="checkbox" id="verify" />
	<label for="verify" style="background:#D8D8D8;color:black;"><b>(Click Here) Verification Tools for Proof of Vaccinations based on Countries/Regions of Issuance</b></label>
	<div class="content" style="background-color:#e7e7e7;">
		<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px; color:#d36363;"><u><b>Singapore</b></u></p>
		<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px;"><b>Self-Verifiable Proofs of Vaccination</b>: Singapore Vaccination HealthCerts issued via the <a href="https://www.notarise.gov.sg/" target="_blank">Notarise portal</a></p>
				<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px;"><b>Available Self-Verification Tools</b>: <a href="https://www.verify.gov.sg/" target="_blank">Verify.gov.sg</a> or regular QR code scanner on your mobile device</p>
				<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px; color:#d36363;"><u><b>Australia</b></u></p>
			<p style="font-size:18px; margin-bottom:10px; line-height:1.5; margin-top:0px;"><b>Self-Verifiable Proofs of Vaccination</b>: Singapore Vaccination HealthCerts issued via the <a href="https://www.notarise.gov.sg/" target="_blank">Notarise portal</a></p>
	</div>
	</p>
	</div>
