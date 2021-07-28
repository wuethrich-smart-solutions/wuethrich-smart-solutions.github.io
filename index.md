---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---



<html>

<head>
    <meta charset="UTF-8">

    <link rel="stylesheet prefetch" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
    <link rel="stylesheet prefetch" href="https://fonts.googleapis.com/css?family=Open+Sans:400,300,700&amp;subset=latin,cyrillic">
    <style>
        body {
            background: url("http://");
            background-size: cover;
        }
        
        .lm-underline {
            position: relative;
        }
        
        .lm-underline:after {
            position: absolute;
            content: ' ';
            right: 5%;
            left: 5%;
            bottom: 0;
            height: 1px;
            background-image: -webkit-linear-gradient(left, transparent, #fff, transparent);
            background-image: linear-gradient(90deg, transparent, #fff, transparent);
        }
        
        .lm-tabel {
            font-family: 'Open Sans';
            max-width: 1000px;
            width: 100%;
            padding-top: 10px;
            margin: 0 auto;
        }
        
        .lm-item-1 .lm-item-bottom,
        .lm-item-1 .lm-item-top {
            background-color: #341b37;
            background-image: -webkit-linear-gradient(135deg, #85468c, #241326);
            background-image: linear-gradient(-45deg, #85468c, #241326);
        }
        
        .lm-item-2 .lm-item-bottom,
        .lm-item-2 .lm-item-top {
            background-color: #e30a51;
            background-image: -webkit-linear-gradient(135deg, #f6266b, #7e052d);
            background-image: linear-gradient(-45deg, #f6266b, #7e052d);
        }
        
        .lm-item-3 .lm-item-bottom,
        .lm-item-3 .lm-item-top {
            background-color: #286caa;
            background-image: -webkit-linear-gradient(135deg, #4d93d5, #1a466f);
            background-image: linear-gradient(-45deg, #4d93d5, #1a466f);
        }
        
        .lm-item {
            -webkit-transform: scale(0.9);
            transform: scale(0.9);
            vertical-align: top;
            width: 33%;
            float: left;
            display: inline-block;
            position: relative;
            -webkit-transition: -webkit-transform 0.3s ease-out, -webkit-filter 0.3s;
            transition: -webkit-transform 0.3s ease-out, -webkit-filter 0.3s;
            transition: transform 0.3s ease-out, filter 0.3s;
            transition: transform 0.3s ease-out, filter 0.3s, -webkit-transform 0.3s ease-out, -webkit-filter 0.3s;
        }
        
        .lm-item:hover {
            -webkit-transform: scale(1);
            transform: scale(1);
        }
        
        .lm-item:not(:hover).blur {
            -webkit-filter: blur(3px);
            filter: blur(3px);
        }
        
        .lm-item:after,
        .lm-item:before {
            z-index: -1;
            content: ' ';
            position: absolute;
            left: 10px;
            top: 80%;
            bottom: 18px;
            right: 10px;
            -webkit-transform-origin: bottom center;
            transform-origin: bottom center;
            box-shadow: 0px 25px 10px -8px rgba(0, 0, 0, 0.4);
        }
        
        .lm-item:after {
            -webkit-transform: rotate(6deg) translate3d(15px, 0, 0);
            transform: rotate(6deg) translate3d(15px, 0, 0);
        }
        
        .lm-item:before {
            -webkit-transform: rotate(-6deg) translate3d(-15px, 0, 0);
            transform: rotate(-6deg) translate3d(-15px, 0, 0);
        }
        
        .lm-item-top {
            padding-top: 20px;
            text-transform: uppercase;
            border-top-left-radius: 7px;
            border-top-right-radius: 7px;
            text-align: center;
        }
        
        .lm-item-title {
            color: #e3dfe2;
            font: 100 30px/70px 'Open Sans';
        }
        
        .lm-item-price {
            background: rgba(255, 255, 255, 0.05);
            margin-top: 20px;
            font-size: 40px;
            line-height: 50px;
            color: #fff;
        }
        
        .lm-item-price i {
            font-size: 15px;
        }
        
        .lm-item-body {
            padding: 15px;
            background: #fff;
        }
        
        .lm-item-desc {
            text-align: center;
            margin-bottom: 15px;
            text-transform: uppercase;
        }
        
        .lm-item-desc strong {
            color: #868686;
            font: 400 16px 'Open Sans';
        }
        
        .lm-item-desc p {
            color: #b4b4b4;
            margin: 0;
        }
        
        .lm-item-list {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        
        .lm-item-list li {
            color: #b4b4b4;
            border-bottom: 1px dotted rgba(0, 0, 0, 0.1);
            margin-bottom: 5px;
        }
        
        .lm-item-list li:nth-child(2n+1) {
            background-color: #fbfbfb;
        }
        
        .lm-item-list .icon-cancel,
        .lm-item-list .icon-ok {
            float: right;
        }
        
        .lm-item-list .icon-ok {
            color: #75bc9a;
        }
        
        .lm-item-list .icon-cancel {
            color: #bf7375;
        }
        
        .lm-item-link {
            text-align: center;
            margin-top: 15px;
        }
        
        .lm-item-link a {
            text-decoration: none;
        }
        
        .lm-item-link display inline-block {
            height: 54px;
        }
        
        .lm-item-link display inline-block:hover {
            -webkit-transition: -webkit-transform 0.3s;
            transition: -webkit-transform 0.3s;
            transition: transform 0.3s;
            transition: transform 0.3s, -webkit-transform 0.3s;
            -webkit-transform: translate3d(0, -3px, 0);
            transform: translate3d(0, -3px, 0);
        }
        
        .lm-item-link display inline-block:active {
            -webkit-transition: -webkit-transform 0.1s;
            transition: -webkit-transform 0.1s;
            transition: transform 0.1s;
            transition: transform 0.1s, -webkit-transform 0.1s;
            -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
        }
        
        .lm-item-link text {
            font-size: 21px;
            font-weight: 700;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
        }
        
        .lm-item-bottom {
            text-align: center;
            border-bottom-left-radius: 7px;
            border-bottom-right-radius: 7px;
            padding: 15px;
            color: rgba(255, 255, 255, 0.5);
            font-weight: 100;
            min-height: 20px;
        }
        
        .lm-item-bottom span {
            color: #fff;
            font-weight: 400;
            margin-right: 3px;
            -webkit-transform: skewX(-10deg);
            transform: skewX(-10deg);
            display: inline-block;
        }
        
        @font-face {
            font-family: 'fontello';
            src: url("data:application/font-woff;base64,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") format('woff');
            font-weight: normal;
            font-style: normal;
        }
        
        [class^="icon-"]:before,
        [class*=" icon-"]:before {
            font-family: "fontello";
            font-style: normal;
            font-weight: normal;
            speak: none;
            display: inline-block;
            text-decoration: inherit;
            width: 1em;
            margin-right: 0.2em;
            text-align: center;
            font-variant: normal;
            text-transform: none;
            line-height: 1em;
            margin-left: 0.2em;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        
        .icon-dollar:before {
            content: '\e806';
        }
        
        .icon-cancel:before {
            content: '\e807';
        }
        
        .icon-ok:before {
            content: '\e808';
        }
    </style>
</head>

<body>

    <div class="lm-tabel">
        <div class="lm-item lm-item-2">
            <div class="lm-item-top"><span class="lm-item-title lm-underline">START</span>
                <div class="lm-item-price"><i class="icon-dollar"></i>0.995</div>
            </div>
            <div class="lm-item-body">
                <div class="lm-item-desc"><strong>CUSTOM AIR</strong>
                    <p>Air, air, air</p>
                </div>
                <ul class="lm-item-list">
                    <li>#1 24/8 support<i class="icon-cancel"></i></li>
                    <li>#2 10 cookies<i class="icon-ok"></i></li>
                    <li>#3 2 candy<i class="icon-ok"></i></li>
                    <li>#4 air form<i class="icon-cancel"></i></li>
                    <li>#5 air filter<i class="icon-cancel"></i></li>
                    <li>#6 air analytik<i class="icon-cancel"></i></li>
                </ul>
                <div class="lm-item-link">
                    <a href="#">
                        <svg width="152" height="52" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="lm-gr-2" x1="0" y1="0" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#7E052D"></stop>
                                    <stop offset="100%" stop-color="#F6266B"></stop>
                                </linearGradient>
                            </defs>
                            <rect x="1" y="1" width="150" height="50" rx="25" fill="#fff" stroke="url(#lm-gr-2)" stroke-width="1"></rect>
                            <text x="23%" y="65%" fill="url(&quot;#lm-gr-2&quot;)">CHOOSE</text>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="lm-item-bottom"></div>
        </div>
        <div class="lm-item lm-item-1">
            <div class="lm-item-top"><span class="lm-item-title lm-underline">BUSINESS</span>
                <div class="lm-item-price"><i class="icon-dollar"></i>2.997</div>
            </div>
            <div class="lm-item-body">
                <div class="lm-item-desc"><strong>CUSTOM AIR</strong>
                    <p>Air, air, air</p>
                </div>
                <ul class="lm-item-list">
                    <li>#1 24/8 support<i class="icon-ok"></i></li>
                    <li>#2 10 cookies<i class="icon-ok"></i></li>
                    <li>#3 2 candy<i class="icon-ok"></i></li>
                    <li>#4 air form<i class="icon-ok"></i></li>
                    <li>#5 air filter<i class="icon-cancel"></i></li>
                    <li>#6 air analytik<i class="icon-cancel"></i></li>
                </ul>
                <div class="lm-item-link">
                    <a href="#">
                        <svg width="152" height="52" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="lm-gr-1" x1="0" y1="0" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#241326"></stop>
                                    <stop offset="100%" stop-color="#85468C"></stop>
                                </linearGradient>
                            </defs>
                            <rect x="1" y="1" width="150" height="50" rx="25" fill="#fff" stroke="url(#lm-gr-1)" stroke-width="1"></rect>
                            <text x="23%" y="65%" fill="url(&quot;#lm-gr-1&quot;)">CHOOSE</text>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="lm-item-bottom"><span class="lm-underline">Choose now </span>and we meet tomorrow!</div>
        </div>
        <div class="lm-item lm-item-3">
            <div class="lm-item-top"><span class="lm-item-title lm-underline">PREMIUM</span>
                <div class="lm-item-price"><i class="icon-dollar"></i>5.005</div>
            </div>
            <div class="lm-item-body">
                <div class="lm-item-desc"><strong>CUSTOM AIR</strong>
                    <p>Air, air, air</p>
                </div>
                <ul class="lm-item-list">
                    <li>#1 24/8 support<i class="icon-ok"></i></li>
                    <li>#2 10 cookies<i class="icon-ok"></i></li>
                    <li>#3 2 candy<i class="icon-ok"></i></li>
                    <li>#4 air form<i class="icon-ok"></i></li>
                    <li>#5 air filter<i class="icon-ok"></i></li>
                    <li>#6 air analytik<i class="icon-ok"></i></li>
                </ul>
                <div class="lm-item-link">
                    <a href="#">
                        <svg width="152" height="52" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="lm-gr" x1="0" y1="0" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#1A466F"></stop>
                                    <stop offset="100%" stop-color="#4D93D5"></stop>
                                </linearGradient>
                            </defs>
                            <rect x="1" y="1" width="150" height="50" rx="25" fill="#fff" stroke="url(#lm-gr)" stroke-width="1"></rect>
                            <text x="23%" y="65%" fill="url(&quot;#lm-gr&quot;)">CHOOSE</text>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="lm-item-bottom"></div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-2.1.4.min.js"></script>
    <script>
        (function() {
            $(document).ready(function() {
                var arrItems;
                arrItems = $('.lm-item');
                return arrItems.hover(function() {
                    return arrItems.addClass('blur');
                }, function() {
                    return arrItems.removeClass('blur');
                });
            });

        }).call(this);
    </script>
</body>

</html>