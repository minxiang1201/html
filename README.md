<html>

<head>
    <title>Div-Slider</title>
    <link href="https://cdn.bootcss.com/flexslider/2.6.3/flexslider.min.css" rel="stylesheet">
    <script src="https://cdn.bootcss.com/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/flexslider/2.6.3/jquery.flexslider-min.js"></script>
    <script>
        $(window).load(function () {
            $('.flexslider').flexslider({
                animation: "slide"
            });
        });
    </script>
    <style>
        body {
            margin: 0px;
        }

        #b1 {
            background-color: lightgray;
            height: 100px;
            line-height: 100px; 
        }

        #b1 h1 {
            width: 400px;
            margin: auto; 
            color: blue;
            text-align: center;
            //border:1px red solid;
        }

        #b2 {
            height: 50px;
            background-color: gray;
            color: white;
            display: flex;
            align-items: center;
            justify-content: space-around;
            padding: 0px 600px;
        }

        .b2-1 {
            line-height: 50px;
            //border: 1px red solid;
        }

        .b2-1:hover {
            background-color: rgb(106, 106, 106);
        }

        /*nav*/
        .b2-1 ul {
            display: none;
            position: absolute;
            z-index: 1;
            background-color: rgb(106, 106, 106);
            min-width: 100px;
            list-style-type: none;
        }

        .b2-1:hover ul {
            display: block;
            margin: 0px;
            padding: 0px;
        }

        .b2-1:hover ul li:hover {
            background-color: white;
        }

        .b2-1 li a {
            color: white;
            text-decoration: none;
            display: block;
            text-align: left;
            padding: 0px 16px;
        }

        .b2-1:hover ul li:hover a {
            color: black;
        }

        /*nav end*/

        .slider {
            background-color: black;
        }

        #b3 {
            height: 730px;
            background-image: url(https://github.com/shhuangmust/html/raw/111-1/slider1.JPG);

        }

        #b3 h2 {
            color: white;
            padding: 50px 150px;
            margin: 0px;
        }

        #b4 {
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: space-around;
            padding: 0px 300px;
        }

        img {
            width: 200px;
            height: 300px;
            //border: 1px red solid;

        }

        #b5 {
            height: 70px;
            line-height: 70px;
            background-color: gray;
        }

        #b5 h4 {
            color: white;
            text-align: center;
            margin: 0px;
        }
    </style>
</head>

<body>
    <div id='b1'>
        <h1>明新科技大學胡閔翔</h1>
    </div>
    <div id="b2">
        <div class="b2-1">首頁</div>
        <div class="b2-1">興趣</div>
        <div class="b2-1">愛好
            <ul>
                <li><a href="#">爵士鼓</a></li>
                <li><a href="#">長笛</a></li>
                <li><a href="#">鋼琴</a></li>
		<li><a href="#">羽球</a></li>

            </ul>
        </div>

        <div class="b2-1">聯絡資訊</div>
    </div>
    <div class="slider">
        <div class="flexslider">
            <ul class="slides">
                <li><img src="https://github.com/shhuangmust/html/raw/111-1/slider1.JPG" /></li>
                <li><img src="https://github.com/shhuangmust/html/raw/111-1/slider2.JPG" /></li>
                <li><img src="https://github.com/shhuangmust/html/raw/111-1/slider3.JPG" /></li>
            </ul>
        </div>
    </div>
    <div id="b3">
        <h2>謝謝觀看</h2>
    </div>
    <div id="b4">
        <img src=https://github.com/shhuangmust/html/blob/master/faculty1.jpg?raw=true>
        <img src=https://github.com/shhuangmust/html/blob/master/faculty2.jpg?raw=true>
        <img src=https://github.com/shhuangmust/html/blob/master/faculty3.jpg?raw=true>
    </div>
    <div id="b5">
        <h4>明新科技大學資訊管理系 版權所有© All Rights Reserved. Designed and Maintained by IM MUST</h4>
    </div>
</body>

</html>
