---
title: Testpage accordion
permalink: /accordion/testpage
---

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
    background: #6AAB95;
    border-radius: 3px;
    color: #FFF;
    transition: ease .5s;
}

label:hover {
    background: #4E8774;
}

label::after{
    font-family:"Font Awesome 5 Free";
    content: '\f078';
    font-weight:bold;
    font-size:22px;
    position:absolute;
    right:10px;
    top:6px;
}

.content {
    background: #FFFFFF;
    padding: 10px 25px;
    border: 1px solid #A7A7A7;
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
<label for="title1">Accordion One</label>

<div class="content">
<p>Your content goes here.</p>
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
