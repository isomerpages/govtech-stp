---
title: This is a unpublished test page for tabs
permalink: /tabs
description: ""
published: true
---

<html>
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
    background: hsl(150deg, 50%, 32%);
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
    background: hsl(150deg, 50%, 47%);
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
	 <p style="font-size:20px; margin-top:10px; margin-bottom:20px; line-height:1.35;"> <b>CLICK HERE for Travel Checklist for Fully Vaccinated Travellers</b></p>
  <ul style="list-style-type: disc; line-height:1.35; text-algin:left">
	  <li style="line-height:1.35; font-size:20px;">Fully Vaccinated with WHO Emergency Use Listing Vaccines; or</li>
	   <li style="line-height:1.35; font-size:20px;">Aged 12 and below regardless of vaccination status &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</li>
	  </ul>
	</span>
	</button></a>
</body>
</html>

<html>
<head>
<style>
  .pushableT {
    background: hsl(50deg, 100%, 62%);
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
    background: hsl(50deg, 100%, 70%);
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
	 <p style="font-size:20px; margin-top:10px; margin-bottom:20px; line-height:1.35;"> <b>CLICK HERE for Travel Checklist for Non-Fully Vaccinated Travellers</b></p>
  <ul style="list-style-type: disc; line-height:1.35; text-algin:left">
	  <li style="line-height:1.35; font-size:20px;">Aged 13 and above and not fully vaccinated with WHO Emergency Use Listing Vaccines; or</li>
	   <li style="line-height:1.35; font-size:20px;">Certified medically ineligible for COVID-19 vaccinations &nbsp; &nbsp;  &nbsp; &nbsp;  &nbsp; &nbsp;</li>
	  </ul>
	</span>
	</button></a>
</body>
</html>

