---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

.columns-pricebox {
  float: left;
  width: 33.3%;
  padding: 8px;
}

.price-pricebox {
  list-style-type: none;
  border: 1px solid #eee;
  margin: 0;
  padding: 0;
  -webkit-transition: 0.3s;
  transition: 0.3s;
}

.price-pricebox:hover {
  box-shadow: 0 8px 12px 0 rgba(0,0,0,0.2)
}

.price-pricebox .header {
  background-color: #111;
  color: white;
  font-size: 25px;
}

.price-pricebox li {
  border-bottom: 1px solid #eee;
  padding: 20px;
  text-align: center;
}

.price-pricebox .grey {
  background-color: #eee;
  font-size: 20px;
}

.button-pricebox {
  background-color: #04AA6D;
  border: none;
  color: white;
  padding: 10px 25px;
  text-align: center;
  text-decoration: none;
  font-size: 18px;
}

@media only screen and (max-width: 600px) {
  .columns-pricebox {
    width: 100%;
  }
}



div.b {
  position: absolute;
  left: auto;
  
} 




</style>
</head>
<body>

<h2 style="text-align:center">Responsive Pricing Tables</h2>
<p style="text-align:center">Resize the browser window to see the effect.</p>

<div class="columns-pricebox">
  <ul class="price-pricebox">
    <li class="header">Basic</li>
    <li class="grey">$ 9.99 / year</li>
    <li>10GB Storage</li>
    <li>10 Emails</li>
    <li>10 Domains</li>
    <li>1GB Bandwidth</li>
    <li class="grey"><a href="#" class="button-pricebox">Sign Up</a></li>
  </ul>
</div>

<div class="columns-pricebox">
  <ul class="price-pricebox">
    <li class="header" style="background-color:#04AA6D">Pro</li>
    <li class="grey">$ 24.99 / year</li>
    <li>25GB Storage</li>
    <li>25 Emails</li>
    <li>25 Domains</li>
    <li>2GB Bandwidth</li>
    <li class="grey"><a href="#" class="button-pricebox">Sign Up</a></li>
  </ul>-
</div>

<div class="columns-pricebox">
  <ul class="price-pricebox">
    <li class="header">Premium</li>
    <li class="grey">$ 49.99 / year</li>
    <li>50GB Storage</li>
    <li>50 Emails</li>
    <li>50 Domains</li>
    <li>5GB Bandwidth</li>
    <li class="grey"><a href="#" class="button-pricebox">Sign Up</a></li>
  </ul>
</div>



<div class="b">This div element has position: absolute and left: auto.</div>
	



</body>
</html>
