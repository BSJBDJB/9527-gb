<!DOCTYPE html>
<html>
    <head>
        <meta charset="'utf-8">
        <title>我的网页</title>
    </head>
    <style>
        *{
            padding:0;
            margin:0;
        }
        .container
        {
            width:100vw;
            height:100vh;
            background-color:aliceblue;
            display:grid;
            grid-template-columns: 25% 25% 25% 25%;
            grid-template-rows:1fr 1fr 1fr;
            grid-row-gap: 10px;
            grid-column-gap: 10px;

        }
        .item
        {
            border: 1px solid aliceblue;
            background-color: blanchedalmond;

        }
        .one{
            grid-column: span 4;
            grid-row: span 2;
        }
        .two{
            text-align:center;
            background: linear-gradient(
            125deg,
            red,orange,yellow
            );
            border-radius: 25px 25px 25px 25px;
        box-shadow: 15px 10px 5px 0px orange;
        padding: 10px;
        }
        .two img{
            width: 100px;
        }
        .three{
            border-radius: 25px 25px 25px 25px;
            text-align:center;
            box-shadow: 8px 2px 5px 0px yellowgreen;
        }
        .three img{
            width: 90%;
            text-align:center;
            padding:10px;
        }
        .four{
            animation-duration: 2s;
            animation-delay: 1s;
            animation-iteration-count: 1;
        }
        .four:hover{
        transform: scale(1.2);
        }
    </style>
    <body>
        <div class="container">
            <div class="item one two four">
                <img src="D5010D3E0DE70CAD36623E64D7850B45.jpg"/>
                <h1>周家宝</h1>
        <p>来自湖北襄阳,计科1班</p>
        <p>喜欢踢球看小说</p>
            </div>
            <!--<div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
            <div class="item">5</div>
            <div class="item">6</div>
            <div class="item">7</div>
            <div class="item">8</div>-->
            <div class="item three four">
                <img src="4B6B87A6C53C4EE37C07D7D5F67546CF.jpg"/>
            <p>吃</p>
            </div>
            <div class="item three four">
                <img src="5A059306591DDD8124D662440053AF95.jpg"/>
            <p>喝</p>
            </div>
            <div class="item three four">
                <img src="804A2B9A0F35D6730ABE548743DA2327.jpg"/>
            <p>玩</p>
            </div>
            <div class="item three four">
                <img src="C333DEAE0F0009384759A21DDE48E50D.jpg"/>
            <p>乐</p>
            </div>    
        </div>
    </body>
</html>
