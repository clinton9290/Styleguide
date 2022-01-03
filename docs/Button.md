---
layout: default
title: Button
nav_order: 8
---



## Button Color
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.w3-button {width:150px;}
</style>
<body>
<div class="w3-container">
  <p><button class="w3-button w3-red">Red</button></p>
  <p><button class="w3-button w3-pink">Pink</button></p>
  <p><button class="w3-button w3-purple">Purple</button></p>
</div>
</body>
</html>

## Animated Button
<html>
<head>
<style>
.button {
  display: inline-block;
  padding: 15px 25px;
  font-size: 24px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #fff;
  background-color: #4CAF50;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}
.button:hover {background-color: #3e8e41}
.button:active {
  background-color: #3e8e41;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
</style>
</head>
<body>
<button class="button">Submit</button>
</body>
</html>

<html>
<head>
<style>
.button1 {
  display: inline-block;
  border-radius: 4px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}
.button1 span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}
.button1 span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}
.button1:hover span {
  padding-right: 25px;
}
.button:hover span:after {
  opacity: 1;
  right: 0;
}
</style>
</head>
<body>
<button class="button1" style="vertical-align:middle"><span>Hover </span></button>
</body>
</html>

## Button Borders
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.w3-btn {margin-bottom:10px;}
</style>
<body>
<div class="w3-container">
<p>
  <button class="w3-button w3-red w3-border">Button</button>
  <button class="w3-button w3-white w3-border w3-border-blue w3-round-large">Button</button>
</p>
</div>
</body>
</html>


