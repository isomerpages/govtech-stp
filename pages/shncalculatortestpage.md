---
title: Testpage calculator
permalink: /shncalculator
---


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

<form oninput="txtFullName.value = txtFirstName.value +' '+ txtLastName.value">
  First name : <input type="text" name="txtFirstName" /> <br><br>
  Last name : <input type="text" name="txtLastName" /> <br><br>
  Full name : <input type="text" name="txtFullName"  > <br><br>
</form>

<form onsubmit="return false" oninput="o.value = parseInt(a.value) + parseInt(b.value)">
  <input name="a" type="number" step="any"> +
  <input name="b" type="number" step="any"> =
  <output name="o"></output>
</form>

<form name="myForm" onSubmit="return false">
<input type="text" name="myText">
<input type="submit" value="Click Me" onclick="myFunction()">
    <label type="text" value="myText.value"></label>
    <p id="demo"></p>
<script>
function myFunction() {
 var x = document.getElementById("myText").value;
  document.getElementById("demo").innerHTML = x;
}
</script>
</form>



