---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<html>

<head>
    <meta charset="UTF-8">

    <link rel="stylesheet prefetch" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
    <style>
        body {
            font: 16px Helvetica;
            background: #ecf0f1;
        }
        
        .container {
            max-width: 750px;
            margin: 100px auto;
        }
        
        .silver,
        .plat {
            float: left;
            width: 250px;
            background: white;
            text-align: center;
        }
        
        .gold {
            float: left;
            position: relative;
            width: 250px;
            top: -50px;
            padding: 50px 0;
            background: #3498db;
            text-align: center;
            border-radius: 5px;
        }
        
        .gold > .price {
            background: white;
            color: rgba(0, 0, 0, 0.7);
        }
        
        .gold > h1,
        .gold > h2,
        .gold > p,
        .gold > span {
            color: white;
        }
        
        h1 {
            margin: 20px 0 10px 0;
            font-size: 1.25em;
            color: rgba(0, 0, 0, 0.8);
        }
        
        h2 {
            font-size: .75em;
            color: rgba(0, 0, 0, 0.6);
            font-weight: 100;
            letter-spacing: 1px;
        }
        
        p {
            color: rgba(0, 0, 0, 0.4);
            margin: 10px 0;
            font-weight: 100;
            font-size: .75em;
        }
        
        span {
            margin-bottom: 20px;
            padding-bottom: 10px;
            display: inline-block;
            width: 125px;
            font-size: 1em;
            font-weight: 700;
            letter-spacing: 1px;
            color: rgba(0, 0, 0, 0.5);
            border-bottom: 1px solid rgba(0, 0, 0, 0.1);
        }
        
        .price {
            height: 100px;
            width: 100px;
            text-align: center;
            background-color: #e74c3c;
            border-radius: 50%;
            line-height: 100px;
            color: #fff;
            font-size: 1.5em;
            font-weight: 100;
            margin: 20px auto;
        }
        
        button {
            display: block;
            margin: 20px auto;
            width: 150px;
            height: 35px;
            border-bottom: 5px solid #c0392b;
            background: #e74c3c;
            border: none;
            border-radius: 5px;
            color: white;
            font-size: .75em;
            font-weight: 100;
            transition: all ease-in-out .2s;
        }
        
        button:hover {
            background: #c0392b;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="silver">
            <h1>Silver Plan</h1>
            <h2>Basic No-Frills Package</h2>
            <div class="price">$10/m</div>
            <p>Number of Courses</p>
            <span>4</span>
            <p>Downloads</p>
            <span>3</span>
            <p>Forums</p>
            <span>Courses Only</span>
            <button>Select Plan</button>
        </div>
        <div class="gold">
            <h1>Gold Plan</h1>
            <h2>The Standard Package</h2>
            <div class="price">$25/m</div>
            <p>Number of Courses</p>
            <span>10</span>
            <p>Downloads</p>
            <span>Unlimited</span>
            <p>Forums</p>
            <span>Courses Only</span>
            <button>Select Plan</button>
        </div>
        <div class="plat">
            <h1>Platinum Plan</h1>
            <h2>Elite! Enough Said!</h2>
            <div class="price">$45/m</div>
            <p>Number of Courses</p>
            <span>Unlimited</span>
            <p>Downloads</p>
            <span>Unlimited</span>
            <p>Forums</p>
            <span>ALL</span>
            <button>Select Plan</button>
        </div>
    </div>

</body>

</html>