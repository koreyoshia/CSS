<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title></title>
    <style>
        body{
            height: 2000px;
        }
        #div1{
            /*background: red;*/
           /* background-color: red;
            background-image: url("ccc.jpg");
            background-repeat: no-repeat;
            background-position: -175px -85px;

            background-attachment: fixed;*/
            height:500px;
            background: red url("ccc.jpg") -175px -85px no-repeat fixed;
        }
        #div2{
            width: 50px;
            height: 50px;
            /*background-image: url("sprite_chaoshi_index@1x.png");
            background-position: -100px 0px;
            background-repeat: no-repeat;*/
        }
        #div3{
            width: 200px;
            height: 300px;
            background: #ff0000;
            /*text-indent: 30px;*/
            text-align: center;
        }
        #div4{
            width: 200px;
            height: 300px;
            background: #ff0000;
            /*文字 行级元素 水平居中*/
            text-align: center;
            /*单行文字垂直居中 line-height = height*/
            line-height: 300px;

            /*多行文字垂直居中？*/

            /*块级元素水平居中*/
             margin:0 auto;
        }
        a{
            text-decoration: none;
            color: #f00;
            font-style: italic;
            font-weight:bold;
            font-size: 20px;
            font-family: sans-serif;
            /*font:*/
        }
        ul{
            list-style: none;
        }
    </style>
</head>
<body>
    <div id="div1">
        haha hehe
    </div>
    <div id="div2">
        
    </div>
    <!--<div id="div3">
        gfdhgdf dgegd  gudgf b kuyg  gfdhgdf dgegd  gudgf b kuyg gfdhgdf dgegd  gudgf b kuyg gfdhgdf dgegd  gudgf b kuyg gfdhgdf dgegd  gudgf b kuyg gfdhgdf dgegd  gudgf b kuyg
    </div>-->
    <div id="div4">
        df gdf ff <span>fasdfsd</span>
    </div>

    <a href="#">baidu</a>

    <ul>
        <li>111</li>
    </ul>





</body>
</html>
