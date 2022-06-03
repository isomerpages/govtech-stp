---
title: This is a unpublished test page for tabs
permalink: /tabs
description: ""
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
  transition: 0.2s transform ease;
}
details[open] > summary:before {
  transform: rotate(90deg);
  transition: 0.45s transform ease;
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
  animation: details-show 500ms ease-in-out;
  position: relative;
  z-index: 1;
  transition: all 0.3s ease-in-out;
  color: transparent;
  overflow: hidden;
}
details[open] > *:not(summary) { color: inherit; }

/* # Style 2 # */
details.style2 summary::before {
  content: "×";
  color: #FFF;
  font-size: 2rem;
  line-height: 1rem;
  transform: rotate(-45deg);
  top: 1.2rem;
  left: 0.5rem;
}
details[open].style2 > summary:before {
  transform: rotate(90deg);
  color: #F00 !important;
  transition: color ease 2s, transform ease 1s;
}

/* # Style 3 # */
details.style3 summary::before {
  content: "›";
  font-size: 2.5rem;
  line-height: 1rem;
  top: 1.3rem;
  left: 0rem;
  margin: -0.5rem -0.5rem 0 0.5rem;
  transform-origin: bottom center;
  transition: margin linear 0.05s;
}
details.style3:hover > summary:before {
  color: #FFF;
}
details[open].style3 > summary:before {
  left: 0rem;
  color: #CCC;
  transform: rotate(90deg);
  margin-left: 0.4rem;
  transition: color ease 2s, transform ease 1s, margin ease 1s;
}
@supports (-webkit-touch-callout: none) {
  details.style3 summary::before { top: 1.6rem; }
  details[open].style3 > summary:before { top: 1.3rem; transition: all 0.8s; }
}

/* # Style 4 # */
details.style4 summary {
  padding-right: 2.2rem;
  padding-left: 1rem;
}
details.style4 summary::before {
  content: "×";
  color: #FFF;
  font-size: 2rem;
  line-height: 1rem;
  transform: rotate(-45deg);
  top: 1.2rem;
  left: unset;
  right: 0.6rem;
}
details[open].style4 > summary:before {
  transform: rotate(90deg);
  color: #F00 !important;
  transition: color ease 2s, transform ease 1s;
}

/* # Style 5 # */
details.style5 summary {
  padding-right: 2.2rem;
  padding-left: 1rem;
}
details.style5 summary::before {
  content: "🙈";
  font-size: 1.5rem;
  top: 0.5rem;
  left: unset;
  right: 0.5rem;
  transform: rotate(0);
}
details.style5:hover > summary::before {
  content: "🙊";
}
details[open].style5 > summary::before {
  content: "🐵";
  transform: rotate(0deg);
}
details[open].style5 > summary:hover::before {
  content: "🙉";
}
details .monkey-see { display: inline; }
details .monkey-hide { display: none; }
details[open] .monkey-see { display: none; }
details[open] .monkey-hide { display: inline; }

/* # Style 6 # */
details.style6 summary {
  padding-right: 2.2rem;
  padding-left: 1rem;
}
details.style6 summary::before {
  content: "❔";
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

/* # Style 7 # */
details.style7 summary {
  padding-left: 3rem;
}
details[open].style7 summary,
details.style7:hover summary {
  background: #000;
  color: #CCC;
}
details[open].style7 summary strong,
details.style7:hover summary strong {
  color: #FDCE4C;
}
details.style7:hover summary strong { color: #ffdf87; }
details.style7 summary::before {
  content: "🌑";
  font-size: 1.5rem;
  top: 0.5rem;
  left: 0.5rem;
  transform: rotate(0);
}
details.style7:hover > summary::before {
  content: "🌕";
}
details[open].style7 > summary::before {
  content: "🌕";
  transform: rotate(0deg);
}
details[open].style7 > summary:hover::before {
  content: "🌕";
}
details .moon-new { display: inline; }
details .moon-full { display: none; }
details[open] .moon-new { display: none; }
details[open] .moon-full { display: inline; }
details.style7 .content { background: #DDD; }

/* # Just Some Pretty Styles # */
body { font-family: "Open Sans", sans-serif; padding-bottom: 400px; }
img { max-width: 100%; }
p { margin: 0; padding-bottom: 10px; }
p:last-child { padding: 0; }
details {
  max-width: 500px;
  box-sizing: border-box;
  margin-top: 5px;
  background: white;
}
summary {
  border: 4px solid transparent;
  outline: none;
  padding: 1rem;
  display: block;
  background: #666;
  color: white;
  padding-left: 2.2rem;
  position: relative;
  cursor: pointer;
}
details[open] summary,
summary:hover {
  color: #FFCA28;
  background: #444;
}
summary:hover strong,
details[open] summary strong,
summary:hover::before,
details[open] summary::before {
  color: #FFA128;
}
.content {
  padding: 10px;
  border: 2px solid #888;
  border-top: none;
}
</style>
</head>
	<body>
<details class="style6">
  <summary>Yet another <strong>STYLE</strong> of indicator.</summary>
  <div class="content">
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Modi unde, ex rem voluptates autem aliquid veniam quis temporibus repudiandae illo, nostrum, pariatur quae! At animi modi dignissimos corrupti placeat voluptatum!
    </p>
    <img src="https://placebear.com/400/200" alt="">
    <p>
      Facilis ducimus iure officia quos possimus quaerat iusto, quas, laboriosam sapiente autem ab assumenda eligendi voluptatum nisi eius cumque, tempore reprehenderit optio placeat praesentium non sint repellendus consequuntur? Nihil, soluta.
    </p>
  </div>
</details>
</body>
</html>

