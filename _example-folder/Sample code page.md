---
title: Sample code page
permalink: /example-folder/permalink/
description: ""
---
<p style="font-size:120%; margin-top: 0px; margin-bottom:20px; line-height:1.35; padding:10px 0 0 0"><b>HH 1:</b></p><p style="font-size:120%; color:red; margin-top: 0px; margin-bottom:20px; line-height:1.35;">(Click ‘+’ to expand for details)</p>
<input type="checkbox" id="Environment">
<label for="Environment" style="background-color: #60C090; color:#f7f7f7;"><b>Text 2</b></label><div class="content" style="background-color:#edf4fa;">
<p style="font-size:18px; margin-top: 2px; margin-bottom:0px; line-height:1.35;">Text 3</p></div>
<input type="checkbox" id="Healthy Living"><label for="Healthy Living" style="background-color: #E58265; color:#f7f7f7;"><b>Text 4</b></label>
<div class="content" style="background-color:#edf4fa;">
<p style="font-size:18px; margin-top: 2px; margin-bottom:0px; line-height:1.35;">Text 5</p></div>
<input type="checkbox" id="Lifelong Learning"><label for="Lifelong Learning" style="background-color: #7573B5; color:#f7f7f7;"><b>Text 6</b></label>
<div class="content" style="background-color:#edf4fa;">
<p style="font-size:18px; margin-top: 2px; margin-bottom:0px; line-height:1.35;"> Text 7</p></div>
<input type="checkbox" id="Social Good"><label for="Social Good" style="background-color: #F05A4D; color:#f7f7f7;"><b>Text 8</b></label>
<div class="content" style="background-color:#edf4fa;">
<p style="font-size:18px; margin-top: 2px; margin-bottom:0px; line-height:1.35;">
Text 9</p></div>
<table style="font-size:120%">
	


<style>

td {
		display: table-cell;
		vertical-align: middle;
}
	
input {
    display: none;
}

label {
    display: block;    
	  font-size: 120%;
    padding: 10px 30px;
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


	

	






	

	
</table>