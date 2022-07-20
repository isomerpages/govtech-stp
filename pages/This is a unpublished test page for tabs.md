---
title: This is a unpublished test page for tabs
permalink: /tabs
description: ""
published: false
---

<!--<html>
<head>
<meta charset="utf-8">
<title>Test Accordion</title>

<style>

input { display: none; }
input + label { display: inline-block }

input ~ .tab { display: none }
#tab1:checked ~ .tab.content1,
#tab2:checked ~ .tab.content2,
#tab3:checked ~ .tab.content3,
#tab4:checked ~ .tab.content4,
#tab5:checked ~ .tab.content5 { display: block; }

input + label {
  border: 1px solid #999;
  background: #EEE;
  padding: 4px 12px;
  border-radius: 4px 4px 0 0;
  position: relative;
  top: 1px;
}
input:checked + label {
  background: #FFF;
  border-bottom: 1px solid transparent;
}
input ~ .tab {
  border-top: 1px solid #999;
  padding: 12px;
		}
</style>
</head>
<body>
<input type="radio" name="tabs" id="tab1" checked />
<label for="tab1">Tab1</label>

<input type="radio" name="tabs" id="tab2" />
<label for="tab2">Tab2</label>

<input type="radio" name="tabs" id="tab3" />
<label for="tab3">Tab3</label>

<input type="radio" name="tabs" id="tab4" />
<label for="tab4">tab4</label>

<input type="radio" name="tabs" id="tab5" />
<label for="tab5">tab5</label>

<div class="tab content1">Tab1 Contents</div>
<div class="tab content2">Tab2 Contents</div>
<div class="tab content3">Tab3 Contents</div>
<div class="tab content4">Tab4 Contents</div>
<div class="tab content5">Tab5 Contents</div>
</body>
</html>

<html>
<head>
<style>
  .pushable {
    background: hsl(345deg, 100%, 76%);
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
  }
  .front {
    display: block;
    padding: 12px 42px;
    border-radius: 12px;
    font-size: 1.25rem;
    background: hsl(345deg, 100%, 84%);
    color: white;
    transform: translateY(-6px);
  }

  .pushable:active .front {
    transform: translateY(-2px);
  }
</style>
	</head>
<body>	
<a href="/arriving/general-travel/fully-vaccinated"><button class="pushable">
  <span class="front">
	 <p style="font-size:20px; margin-top:10px; margin-bottom:0px; line-height:1.35; text-align:justify;"> <b>CLICK HERE for Travel Checklist for Fully Vaccinated Travellers</b></p>
  <ul style="list-style-type: disc; line-height:1.35; text-align:justify;">
	  <li style="line-height:1.35; font-size:20px;">Fully Vaccinated with WHO Emergency Use Listing Vaccines; or</li>
	   <li style="line-height:1.35; font-size:20px; text-align:justify;">Aged 12 and below regardless of vaccination status </li>
	  </ul>
	</span>
	</button></a>
</body>
</html>

 <p style="font-size:20px; margin-top:20px; margin-bottom:20px; line-height:1.35;"></p>

<html>
<head>
<style>
  .pushableT {
    background: hsl(205deg, 40%, 30%);
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
  }
  .frontT {
    display: block;
    padding: 12px 42px;
    border-radius: 12px;
    font-size: 1.25rem;
    background: hsl(205deg, 40%, 20%);
    color: white;
    transform: translateY(-6px);
  }

  .pushableT:active .front {
    transform: translateY(-2px);
  }
</style>
	</head>
<body>	
<a href="/arriving/general-travel/non-fully-vaccinated"><button class="pushableT">
  <span class="frontT">
	 <p style="font-size:20px; margin-top:10px; margin-bottom:0px; line-height:1.35; text-align:justify;"> <b>CLICK HERE for Travel Checklist for Non-Fully Vaccinated Travellers</b></p>
  <ul style="list-style-type: disc; line-height:1.35; width:auto;">
	  <li style="line-height:1.35; font-size:20px; text-align:justify;">Aged 13 and above and not fully vaccinated with <br> WHO Emergency Use Listing Vaccines; or  </li>
	   <li style="line-height:1.35; font-size:20px; text-align:justify;">Certified medically ineligible for COVID-19 vaccinations </li>
	  </ul>
	</span>
	</button></a>
</body>
</html>-->

<html>
<head>
<meta charset="utf-8">
<title>Test Accordion</title>
<style>
	
/* # The Rotating Marker # */
details summary::-webkit-details-marker { display: none; }
summary::before {
  font-family: "Hiragino Mincho ProN", "Open Sans", sans-serif;
  content: "▶";
  position: absolute;
  top: 1rem;
  left: 0.8rem;
  transform: rotate(0);
  transform-origin: center;
  /*transition: 0.2s transform ease;*/
}
details[open] > summary:before {
  transform: rotate(90deg);
  /*transition: 0.45s transform ease;*/
}

/* # The Sliding Summary # */
details { overflow: hidden; }
details summary {
  position: relative;
  z-index: 10;
}
@keyframes details-show {
  from {
    margin-bottom: -80%;
    opacity: 0;
    transform: translateY(-100%);
  }
}
details > *:not(summary) {
  /*animation: details-show 500ms ease-in-out;*/
  position: relative;
  z-index: 1;
  /*transition: all 0.3s ease-in-out;*/
  color: transparent;
  overflow: hidden;
}
details[open] > *:not(summary) { color: inherit; }

/* # Style 6 # */
details.style6 summary {
  padding-right: 2.2rem;
  padding-left: 1rem;
}
details.style6 summary::before {
  content: "\271A";
  font-size: 1.5rem;
  top: 0.5rem;
  left: unset;
  right: 0.5rem;
  transform: rotate(0);
}
details.style6:hover > summary:before {
  content: "\271A";
}
details[open].style6 > summary:before {
  content: "\2716";
  transform: rotate(0deg);
}


/* # Just Some Pretty Styles # */
body { font-family: "Open Sans", sans-serif; padding-bottom: 400px; }
img { max-width: 100%; }
p { margin: 0; padding-bottom: 10px; }
p:last-child { padding: 0; }
details {
  /*max-width: 500px;*/
  box-sizing: border-box;
  margin-top: 5px;
  background: white;
}
summary {
  border: 4px solid transparent;
  outline: none;
  padding: 1rem;
  display: block;
  background: #CEDEED;
  color: #000;
  padding-left: 2.2rem;
  position: relative;
  cursor: pointer;
}
details[open] summary,
summary:hover {
  color: #000;
  background: #9ac5ed;
}
summary:hover strong,
details[open] summary strong,
summary:hover::before,
details[open] summary::before {
  color: #000;
}
.contenttest {
  padding: 10px;
  border: 2px solid #888;
  border-top: none;
}
</style>
</head>
	<body>
<details class="style6">
	<summary><b>SHN Frequently Asked Questions</b></summary>
  <div style="border-bottom: 2px solid #E0E0E0; border-left:2px solid #E0E0E0;border-right:2px solid #E0E0E0; background-color:#edf4fa;" class="contenttest">
 <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;"> <b> Q1) Commuting to SHN location and to/from COVID-19 test site</b></p>
          <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">The commuting arrangement stated at <a href="#2B">Stage 2B</a> will continue to apply for the SHN duration. </p>
            <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;"><b>Q2) SHN end date:</b></p>
            <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">Use the <a href="/shn-calculator" target="_blank">SHN calculator</a> for your estimated SHN end date or refer to the illustrations below. If you need to leave your SHN for an emergency, e.g. funeral or hospital visits, submit a <a href="https://go.gov.sg/sto-enquiry" target="_blank">written request</a> to the SafeTravel Office for assistance.</p>
          <p style="font-size:18px; margin-top: 10px;  line-height:1.35;"><u>Illustration 1:</u></p>
            <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">Traveller A cleared immigration on 1 March 2022. The effective period of his SHN is 1 – 8 March 2022. He had received a negative PCR test on 8 March and can exit his SHN accommodation on the same day.</p>
            <p style="font-size:18px; margin-top: 10px; line-height:1.35;"><u>Illustration 2:</u></p>
            <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">Traveller B cleared immigration on 1 March 2022. The effective period of her SHN is 1 – 8 March 2022. As she did not receive a negative PCR test report on 8 March, she must remain in her SHN accommodation until she receives a negative PCR test result.</p>
          <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;"><b>Q3) Getting daily essentials:</b></p>
          <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">You can opt for home delivery service or enlist the help of others. When collecting these items, avoid collecting them personally. You may also contact the SafeTravel Helpline at 6812 5555 for advice.</p>
               <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;"><b>Q4) I received a call claiming to check on me during SHN, is it a scam?</b></p>
               <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">During the SHN period, randomised in-person or phone/video compliance calls will be conducted.</p>
               <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">All in-person or phone/video compliance checks are conducted by the Immigration & Checkpoints Authority (ICA), Ministry of Manpower (MOM), or the Ministry of Education (MOE). Authorised officers conducting house visits will produce their warrant cards or authorisation letters as proof of identity. For phone/video compliance checks, travellers will only be asked for the last four digits of their identity card or travel document for identity verification.</p>
          <p style="font-size:18px; margin-top: 10px; margin-bottom:20px; line-height:1.35;">Any request for payment or credit card details made over phone may be a scam. If you suspect you have received a scam call, please contact the Police hotline at 1800-255-0000.</p>
  </div>
</details>
</body>
</html>

