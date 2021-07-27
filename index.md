---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<html>
	<body>
<div class="container">
	<div class="row">
	   <div class="col-sm-4">
	      <div class="card">
	         <div class="card-side card-side-front">
	            <div class="card-picture card-picture-1">
	               &nbsp;
	            </div>
	            <h4 class="card-heading">
	               <span class="card-heading-span card-heading-span-1">The Sea Explorer</span>
	            </h4>
	            <div class="card-details">
	               <ul>
	                  <li>3 day tours</li>
	                  <li>Up to 30 people</li>
	                  <li>2 tour guides</li>
	                  <li>Sleep in cozy hotels</li>
	                  <li>Difficulty: easy</li>
	               </ul>
	            </div>
	         </div>
	         <div class="card-side card-side-back card-side-back-1">
	            <div class="card-cta">
	               <div class="card-price-box">
	                  <p class="card-price-only">Only</p>
	                  <p class="card-price-value">$297</p>
	               </div>
	               <a href="#" class="btn btn-white">Book now!</a>
	            </div>
	         </div>
	      </div>
	   </div>


	   <div class="col-sm-4">
	      <div class="card">
	         <div class="card-side card-side-front">
	            <div class="card-picture card-picture-2">
	               &nbsp;
	            </div>
	            <h4 class="card-heading">
	               <span class="card-heading-span card-heading-span-2">The Forest Hiker</span>
	            </h4>
	            <div class="card-details">
	               <ul>
	                  <li>7 day tours</li>
	                  <li>Up to 40 people</li>
	                  <li>6 tour guides</li>
	                  <li>Sleep in provided tents</li>
	                  <li>Difficulty: medium</li>
	               </ul>
	            </div>

	         </div>
	         <div class="card-side card-side-back card-side-back-2">
	            <div class="card-cta">
	               <div class="card-price-box">
	                  <p class="card-price-only">Only</p>
	                  <p class="card-price-value">$497</p>
	               </div>
	               <a href="#" class="btn btn-white">Book now!</a>
	            </div>
	         </div>
	      </div>
	   </div>


	   <div class="col-sm-4">
	      <div class="card">
	         <div class="card-side card-side-front">
	            <div class="card-picture card-picture-3">
	               &nbsp;
	            </div>
	            <h4 class="card-heading">
	               <span class="card-heading-span card-heading-span-3">The Snow Adventurer</span>
	            </h4>
	            <div class="card-details">
	               <ul>
	                  <li>5 day tours</li>
	                  <li>Up to 15 people</li>
	                  <li>3 tour guides</li>
	                  <li>Sleep in provided tents</li>
	                  <li>Difficulty: hard</li>
	               </ul>
	            </div>

	         </div>
	         <div class="card-side card-side-back card-side-back-3">
	            <div class="card-cta">
	               <div class="card-price-box">
	                  <p class="card-price-only">Only</p>
	                  <p class="card-price-value">$897</p>
	               </div>
	               <a href="#" class="btn btn-white">Book now!</a>
	            </div>
	         </div>
	      </div>
	   </div>
	</div>
</div>
</body>
</html>


//variables
$color-primary-light: #7ed56f;
$color-primary-dark: #28b485;

$color-secondary-light: #ffb900;
$color-secondary-dark: #ff7730;

$color-tertiary-light: #2998ff;
$color-tertiary-dark: #5643fa;

$color-grey-light-1: #f7f7f7;
$color-grey-light-2: #eee;
$color-grey-dark: #777;

$color-white: #fff;
$color-black: #000;

body {
    background-color: $color-grey-light-1;
    padding:100px 0;
    font-family: "Lato", sans-serif;
    font-weight: 400;
    line-height: 1.7;
}
.card {
    perspective: 1500px;
    -moz-perspective: 1500px;
    position: relative;
    height: 520px;
    &-side {
        height: 520px;
        transition: all .8s ease;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        backface-visibility: hidden;
        border-radius: 3px;
        overflow: hidden;
        box-shadow: 0 15px 40px rgba($color-black, .15);
        &-front {
            background-color: $color-white;
        }
        &-back {
            transform: rotateY(180deg);
            &-1 {
                background-image: linear-gradient(to right bottom, $color-secondary-light, $color-secondary-dark);
            }
            &-2 {
                background-image: linear-gradient(to right bottom, $color-primary-light, $color-primary-dark);
            }
            &-3 {
                background-image: linear-gradient(to right bottom, $color-tertiary-light, $color-tertiary-dark);
            }
        }
    }
    &:hover &-side-front {
        transform: rotateY(-180deg);
    }
    &:hover &-side-back {
        transform: rotateY(0);
    }

    // FRONT SIDE STYLING
    &-picture {
        background-size: cover;
        height: 230px;
        background-blend-mode: screen;
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        border-top-left-radius: 3px;
        border-top-right-radius: 3px;
        &-1 {
            background-image: linear-gradient(to right bottom, $color-secondary-light, $color-secondary-dark), url(https://picsum.photos/400/250?image=1050);
        }
        &-2 {
            background-image: linear-gradient(to right bottom, $color-primary-light, $color-primary-dark), url(https://picsum.photos/400/250?image=1063);
        }
        &-3 {
            background-image: linear-gradient(to right bottom, $color-tertiary-light, $color-tertiary-dark), url(https://picsum.photos/400/250?image=1061);
        }
    }
    &-heading {
        font-size: 28px;
        font-weight: 300;
        text-transform: uppercase;
        text-align: right;
        color: $color-white;
        position: absolute;
        top: 120px;
        right: 20px;
        width: 75%;
       line-height: 1.7;
    }
    &-heading-span {
        padding: 1rem 15px;
        -webkit-box-decoration-break: clone;
        box-decoration-break: clone;
        &-1 {
            background-image: linear-gradient(to right bottom, rgba($color-secondary-light, .85), rgba($color-secondary-dark, .85));
        }
        &-2 {
            background-image: linear-gradient(to right bottom, rgba($color-primary-light, .85), rgba($color-primary-dark, .85));
        }

        &-3 {
            background-image: linear-gradient(to right bottom, rgba($color-tertiary-light, .85), rgba($color-tertiary-dark, .85));
        }
    }
    &-details {
        padding: 30px;
        ul {
            list-style: none;
            width: 80%;
            margin: 0 auto;
            padding:0;
            li {
                text-align: center;
                font-size: 15px;
                padding: 10px;
                &:not(:last-child) {
                    border-bottom: 1px solid $color-grey-light-2;
                }
            }
        }
    }

    // FRONT SIDE STYLING
    &-cta {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        text-align: center;
    }
    &-price-box {
        text-align: center;
        color: $color-white;
        margin-bottom: 80px;
    }
    &-price-only {
        font-size: 14px;
        text-transform: uppercase;
    }
    &-price-value {
        font-size: 60px;
        font-weight: 100;
    }
}
.btn {
    &, &:link, &:visited {
        text-transform: uppercase;
        text-decoration: none;
        padding: 15px 40px;
        display: inline-block;
        border-radius: 100px;
        transition: all .2s;
        position: relative;
        font-size: 16px;
        border: none;
        cursor: pointer;
       background-color: $color-white;
        color: $color-grey-dark;
    }
   &::after {
        content: "";
        display: inline-block;
        height: 100%;
        width: 100%;
        border-radius: 10rem;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
        transition: all .4s;
         background-color: $color-white;
    }
   &:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 20px rgba($color-black,.2);
        &::after {
            transform: scaleX(1.4) scaleY(1.6);
            opacity: 0;
        }
    }
    &:active, &:focus {
        outline: none;
        transform: translateY(-1px);
        box-shadow: 0 5px 10px rgba($color-black,.2);
    }
}
