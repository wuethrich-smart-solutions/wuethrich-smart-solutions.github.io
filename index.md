---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<html>
	<body>
		<div class="pricing-table text-center">
			<div class="container">
				<h2 class="h1">Pricing Table</h2>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
				<div class="pricing-plan f-left">
					<h3>Free</h3>
					<span class="pricing">$0</span>
					<ul class="list-unstyled">
						<li>Disk Space: 1GB</li>
						<li>BandWidth: 2GB</li>
						<li>FTP Accounts: 5</li>
						<li>DataBase: 5</li>
						<li>Free Domain</li>
					</ul>
					<button>Shop Now</button>
				</div>
				
				<div class="pricing-plan f-left">
					<h3>Premium</h3>
					<span class="pricing">$10</span>
					<ul class="list-unstyled">
						<li>Disk Space: 50GB</li>
						<li>BandWidth: 100GB</li>
						<li>FTP Accounts: 25</li>
						<li>DataBase: 50</li>
						<li>Free Domain</li>
					</ul>
					<button>Shop Now</button>
				</div>
				
				<div class="pricing-plan f-left">
					<h3>Ultimate</h3>
					<span class="pricing">$50</span>
					<ul class="list-unstyled">
						<li>Disk Space: 150GB</li>
						<li>BandWidth: 200GB</li>
						<li>FTP Accounts: 50</li>
						<li>DataBase: 100</li>
						<li>Free Domain</li>
					</ul>
					<button>Shop Now</button>
				</div>
				<div class="clearfix"></div>
			</div>
		</div>

</body>
</html>



/* Start Pricing Table */
.pricing-table {padding: 20px 0; background-color: #F0F0F0}
.pricing-table .h1 {color: #555; font-size: 40px; margin-bottom: 25px; margin-top: 0}
.pricing-table p {color: #888; margin-bottom: 50px}
.pricing-table .pricing-plan {width: 32.3333%; position: relative}
.pricing-table .pricing-plan:first-of-type {left:32.3333%; margin: 0 1% 0 1%}
.pricing-table .pricing-plan:nth-of-type(2) {right:34.3333%}
.pricing-table .pricing-plan:not(:first-of-type) {margin-top: 40px}
.pricing-table .pricing-plan:first-of-type span {padding: 50px 20px 30px 20px}
.pricing-table .pricing-plan h3 
{
	color: #555;
	background-color: beige; 
	margin: 0; 
	padding: 15px 20px; 
	font-size: 22px;
	border-bottom: 1px solid brown;
	border-top-right-radius: 5px;
	border-top-left-radius: 5px
}
.pricing-table .pricing-plan span 
{    
	padding: 30px 20px 10px 20px;
    font-size: 75px;
    font-weight: bold;
    display: inherit;
    width: initial;
    background-color: beige;
	color: #555
}
.pricing-table .pricing-plan ul li {padding: 10px 20px; background-color: #fff; color: #555; margin-bottom: 10px}
.pricing-table .pricing-plan ul li:not(:last-of-type) { margin-bottom: 2px}
.pricing-table .pricing-plan button 
{
	
	-webkit-appearance: button;
    display: block;
    width: -webkit-fill-available;
    padding: 10px;
    background-color: brown;
    border: 0;
    color: #fff;
    font-weight: bold;
    font-size: 25px;
	transition: all .3s ease-in-out
}

.pricing-table .pricing-plan button:hover {box-shadow: 5px 5px 2px #ccc}
/* End Price Box */

/********* Start FrameWork *********/

.text-center {text-align: center}
.container {margin: auto; padding-right: 15px; padding-left: 15px}
.clearfix {clear: both}

.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {display: none}

.hidden-xs,
.hidden-sm,
.hidden-md,
.hidden-lg {display: block}

.f-left {float: left}
.f-right {float: right}

.h1 {font-size: 2em}
.h2 {font-size: 1.5em}

.responsive-paragraph{line-height: 1.7}
.img-responsive {width: 100%}
.list-unstyled {list-style: none; margin: 0; padding: 0}
/********* End FrameWork *********/

