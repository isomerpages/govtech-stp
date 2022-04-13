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
    background: hsl(340deg 100% 32%);
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
    background: hsl(345deg 100% 47%);
    color: white;
    transform: translateY(-6px);
  }

  .pushable:active .front {
    transform: translateY(-2px);
  }
</style>
	</head>
<body>	
<button class="pushable" action="https://google.com">
  <span class="front">
	 Push me
  </span>
</button>
</body>
</html>



