---
title: Sample code page
permalink: /example-folder/permalink/
description: ""
---
<p style="font-size:120%; margin-top: 0px; margin-bottom:20px; line-height:1.35; padding:10px 0 0 0"><b>Sample :</b></p><p style="font-size:120%; color:red; margin-top: 0px; margin-bottom:20px; line-height:1.35;">(Click ‘+’ to expand for details)</p>
<input type="checkbox" id="Sample 1"><label for="Sample 1" style="background-color: #60C090; color:#f7f7f7;"><b>Sample 1</b></label>
<div class="content" style="background-color:#edf4fa;"><p style="font-size:18px; margin-top: 2px; margin-bottom:0px; line-height:1.35;">Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem IpsumLorem Ipsum Lorem Ipsum .</p></div><table style="font-size:120%">
	
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