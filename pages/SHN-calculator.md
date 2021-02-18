---
permalink: /SHN-Calculator
---

<html>

<head>
<meta charset="utf-8">
<title>SHN Calculator</title>

<style>
  
[type="date"] {
  background:#fff url(https://cdn1.iconfinder.com/data/icons/cc_mono_icon_set/blacks/16x16/calendar_2.png)  97% 50% no-repeat ;
}
[type="date"]::-webkit-inner-spin-button {
  display: none;
}
[type="date"]::-webkit-calendar-picker-indicator {
  opacity: 0;
}

body {  
  font: 13px Verdana, sans-serif;
}
label {
  display: block;
}
input {
  border: 1px solid #c4c4c4;
  background-color: #fff;  
  width: 95px;
}

.coc-block-row {
    width: 100%;
    /*display:table-row;*/
}
.coc-block {
    display: table-cell;
    vertical-align: middle;
    padding-bottom: 3px;
}
.coc-block-label {
  font-family: Verdana;
  display: table-cell;
  vertical-align: middle;
  text-align: right;
  padding-bottom: 3px;
  padding-right: 5px;
  font-weight: bold;
  margin-bottom: 0;
}
.coc-input {
  font-family: Calibri;
  height: 20px;
  font-size: 12px;
  padding-left: 3px;
  padding-right: 3px;
  border: 1px solid #999;
 
}
.coc-form {
    padding-top: 5px;
    padding-left: 8px;
}

</style>
</head>

<body>

<h1>SHN End-date Calculator</h1>
<div class="coc-form">
  <div class="coc-block-row">
    <label class="coc-block-label" for="dateofbirth">SHN Start Date</label>
    <div class="coc-block">
      <input class="coc-input" type="date" name="dateofbirth" id="dateofbirth">
    </div>
  </div>
</div>
