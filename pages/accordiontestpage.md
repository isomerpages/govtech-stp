---
title: Testpage accordion
permalink: /accordion
---

<html>

<head>
<meta charset="utf-8">
<title>CSS Accordion</title>

<style>

input {
    display: none;
}

label {
    display: block;    
    padding: 8px 22px;
    margin: 0 0 1px 0;
    cursor: pointer;
    background: #153855;
    border-radius: 3px;
    color: #FFF;
    transition: ease .5s;
	position: relative;
}

label:hover {
    background: #346f9e;
}

label::after {
	font-family: "Font Awesome 5 Free";
	content: '\2798';
	font-weight: bold;
	font-size: 22px;
	position: absolute;
	right: 10px;
	top: 6px;
}

input:checked + label::after {
	content: '\2798';
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

<body>


<input type="checkbox" id="title1" />
<label for="title1">1. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</label>

<div class="content">
	<p>The following FAQs apply to persons who are residents in countries/regions that have established RGL arrangements with Singapore seeking single-entry, short-term essential business and official visit into Singapore:</p>
<table>
<thead>
  <tr>
    <th style="border-top:3px solid #D8D8D8; border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED">Country/Region</th>
    <th style="border-top:3px solid #D8D8D8; border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED">NOTE</th>
  </tr>
</thead>
<tbody>
    <tr>
    <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED"><b>Brunei Darussalam</b></td>
      <td rowspan="2" style="text-align:left;border-right:1px solid #D8D8D8;">Travellers travelling from Brunei Darussalam and Mainland China may alternatively visit Singapore via the <a href="/atp/overview">Air Travel Pass.</a></td>
  </tr>
  <tr>
      <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED"><b>Mainland China (Chongqing, Guangdong, Jiangsu, Shanghai, Tianjin and Zhejiang)</b></td>
  </tr>
   <tr>
    <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED"><b>Germany </b></td>
    <td rowspan="5" style="text-align:left;border-right:1px solid #D8D8D8;"><span style="color:red;"><b>New applications have been suspended for these countries/regions.  However, travellers already approved for entry under the RGL can continue to use their existing SafeTravel Pass-RGL to enter Singapore.</b></span>
       <p style="margin-top:0px; margin-bottom:0px; font-size:16px;">Click below for the press releases regarding Singapore's RGL suspension for:</p>
      <ol style="margin-top:0px; margin-bottom:0px;display: none list-style-type:disc;">
<li style="margin-top:0px; margin-bottom:0px; font-size:16px;"><a href="https://www.mfa.gov.sg/Newsroom/Press-Statements-Transcripts-and-Photos/2021/01/20210101-Indon-Entry">Indonesia</a></li><li style="margin-top:0px; margin-bottom:0px; font-size:16px;"><a href="https://www.mfa.gov.sg/Newsroom/Press-Statements-Transcripts-and-Photos/2021/01/20210115-SG-JP-RGL-Suspension">Japan</a></li><li style="margin-top:0px; margin-bottom:0px; font-size:16px;"><a href="https://www.mfa.gov.sg/Newsroom/Press-Statements-Transcripts-and-Photos/2021/01/20210130-RGL-Suspension">Germany, Malaysia and the Republic of Korea</a></li>            
      </ol>
 </td>
  </tr>
  <tr>
    <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED" ><b>Indonesia</b></td>
  </tr>
  <tr>
    <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED"><b>Japan</b></td>
  </tr>
     <tr>
    <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED"><b>Malaysia</b></td>
  </tr>
    <tr>
      <td style="border-left:1px solid #D8D8D8; border-right:1px solid #D8D8D8; background-color:#EDEDED; border-bottom:1px solid #D8D8D8; "><b>Republic of Korea</b></td>
  </tr>
  </tbody>
  </table>
</div>

<input type="checkbox" id="title2" />
<label for="title2">Accordion Two</label>

<div class="content">
<p>Your content goes here.</p>
</div>

<input type="checkbox" id="title3" />
<label for="title3">Accordion Three</label>

<div class="content">
<p>Your content goes here.</p>
</div>
</body>




-----



<p>You can use this calculator to determine the period of your 14-day SHN.</p>
<div class="vt-container validity-tool-new">
    <div class="form-group">
        <div class="form-group form-error-msg" id="dateErrorMessage"></div>
        <p><span class="label">SHN issued on:</span>
            <label class="sr-only" for="day">Day</label>
            <select class="form-control" id="day" name="day">
<option selected="selected" value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
<option value="7">7</option>
<option value="8">8</option>
<option value="9">9</option>
<option value="10">10</option>
<option value="11">11</option>
<option value="12">12</option>
<option value="13">13</option>
<option value="14">14</option>
<option value="15">15</option>
<option value="16">16</option>
<option value="17">17</option>
<option value="18">18</option>
<option value="19">19</option>
<option value="20">20</option>
<option value="21">21</option>
<option value="22">22</option>
<option value="23">23</option>
<option value="24">24</option>
<option value="25">25</option>
<option value="26">26</option>
<option value="27">27</option>
<option value="28">28</option>
<option value="29">29</option>
<option value="30">30</option>
<option value="31">31</option>
</select>
            <label class="sr-only" for="month">Month</label>
            <select class="form-control" id="month" name="month">
<option value="Jan">Jan</option>
<option selected="selected" value="Feb">Feb</option>
<option value="Mar">Mar </option>
<option value="Apr">Apr</option>
<option value="May">May</option>
<option value="Jun">Jun</option>
<option value="Jul">Jul</option>
<option value="Aug">Aug</option>
<option value="Sep">Sep</option>
<option value="Oct">Oct</option>
<option value="Nov">Nov</option>
<option value="Dec">Dec</option>
</select>
            <label class="sr-only" for="year">Year</label>
            <select class="form-control" id="year" name="year">
<option value="2020">2020</option>
<option selected="selected" value="2021">2021</option>
</select>
        </p>
    </div>
    <div class="form-group">
        <div class="form-group form-error-msg dayErrorMessage"></div>
        <p>&nbsp;</p>
    </div>
    <div class="form-group">
        <p><button class="btn" type="submit">Submit</button></p>
    </div>
    <div class="form-group result">
        <p><span class="form-result">You can only leave your accommodation after  <span class="resultMessage"></span><span class="underline">, 12pm</span>, or until the result of your COVID-19 test is notified to you, whichever is later.</span>
        </p>
    </div>
</div>

