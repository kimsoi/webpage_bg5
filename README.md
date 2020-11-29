# webpage
* <!-- <!DOCTYPE html>
<html>

<head>
    <title>배틀그라운드 연구소</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <style>
        img{
            position: absolute;
        }
        .vod{
            position: absolute;
        }
    </style>

    <script>
        let x=0;
        let y=0;
        let mx=0;
        let my=0;
        let speed =0.009;
        let _imgArr;

        window.onload = function(){
            _imgArr = document.getElementByTagName("img");

            window.addEventListener("mousemove",mouseFunc, false);

            function mouseFunc(e){
                x=(e.clientX - window.innerWidth /2);
                y=(e.clientY - window.innerHeight /2);
            }
            loop();
        }

        function loop(){
            mx += (x-mx) *speed;
            my += (y-my) * speed;
            _imgArr[0].style.transform ="trnaslate("+(mx/6) +"px," + -(my/6)+"px)";

            window.requestAnimationFrame(loop);

        }





    </script>
    </head>

    <body>
        <section>
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/1-b90e91a4.png">

            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/2-f3fd6cf5.png">
            
            <div class="vod"><video autoplay="" playsinline="" loop="" muted="" src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/videos/3-27c8c3ea.webm"></video></div>
            
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/4-105dd65b.png">
            
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/5-ac49bfdc.png">
        </section>
    </body>
    </html> -->

    <!DOCTYPE html>
<html>

<head>
    <title>배틀그라운드연구소</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <style>

        * {
            box-sizing: border-box;
            }
            /* Style the header */
        .header {
                background-color: #f1f1f1;
                padding: 20px;
                text-align: center;
        }
        .topnav {
                overflow: hidden;
                background-color: #333;
         }
         .topnav a {
                float: left;
                display: block;
                color: #f2f2f2;
                text-align: center;
                padding: 14px 16px;
                text-decoration: none;
        }
        .topnav a:hover {
                background-color: #ddd;
                color: black;
        }
    
        
        body{ 
            position: relative;
            background-color: black;
            /* cursor: none;    */
            overflow: hidden;
            margin:0;
        }
        h1{
            color: #fff;
        }
        .cursor_item{
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
            top:0;
            left:0;
            margin: -50px 0 0 -50px;
            transition: all 500ms cubic-bezier(0.930, 0.005, 0.040, 1.005);
                     
        }
    
        }
        button:hover{
            background: red;
            color: #fff;
            font-size: 80px;
            padding : 80px 150px;
        }
        .human{
            position: absolute;<!-- <!DOCTYPE html>
<html>

<head>
    <title>배틀그라운드 연구소</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <style>
        img{
            position: absolute;
        }
        .vod{
            position: absolute;
        }
    </style>

    <script>
        let x=0;
        let y=0;
        let mx=0;
        let my=0;
        let speed =0.009;
        let _imgArr;

        window.onload = function(){
            _imgArr = document.getElementByTagName("img");

            window.addEventListener("mousemove",mouseFunc, false);

            function mouseFunc(e){
                x=(e.clientX - window.innerWidth /2);
                y=(e.clientY - window.innerHeight /2);
            }
            loop();
        }

        function loop(){
            mx += (x-mx) *speed;
            my += (y-my) * speed;
            _imgArr[0].style.transform ="trnaslate("+(mx/6) +"px," + -(my/6)+"px)";

            window.requestAnimationFrame(loop);

        }





    </script>
    </head>

    <body>
        <section>
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/1-b90e91a4.png">

            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/2-f3fd6cf5.png">
            
            <div class="vod"><video autoplay="" playsinline="" loop="" muted="" src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/videos/3-27c8c3ea.webm"></video></div>
            
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/4-105dd65b.png">
            
            <img src="https://paidpost-assets.nyt.com/paidpost/allbirds/birds-eye-view/images/5-ac49bfdc.png">
        </section>
    </body>
    </html> -->

    <!DOCTYPE html>
<html>

<head>
    <title>배틀그라운드연구소</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <style>

        * {
            box-sizing: border-box;
            }
            /* Style the header */
        .header {
                background-color: #f1f1f1;
                padding: 20px;
                text-align: center;
        }
        .topnav {
                overflow: hidden;
                background-color: #333;
         }
         .topnav a {
                float: left;
                display: block;
                color: #f2f2f2;
                text-align: center;
                padding: 14px 16px;
                text-decoration: none;
        }
        .topnav a:hover {
                background-color: #ddd;
                color: black;
        }
    
        
        body{ 
            position: relative;
            background-color: black;
            /* cursor: none;    */
            overflow: hidden;
            margin:0;
        }
        h1{
            color: #fff;
        }
        .cursor_item{
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
            top:0;
            left:0;
            margin: -50px 0 0 -50px;
            transition: all 500ms cubic-bezier(0.930, 0.005, 0.040, 1.005);
                     
        }
    
        }
        button:hover{
            background: red;
            color: #fff;
            font-size: 80px;
            padding : 80px 150px;
        }
        .human{
            position: absolute;
            width: 500px;
            left:calc(50% - 150px) ; /*사진 가운데로*/ 
            z-index: 100;  /*사람 이미지 맨 앞으로 갖고오기*/
        }
        /* .bg{} */
        li {display: inline;}

    </style>
    
    
    <!-- <style type="text/css">
        body{cursor: url('cursor.cur'),auto;}

    </style> -->
    <script>
        let human;
        let bg;
        let h1;

        let x =0;
        let y =0;
        let mx=0;   //마우스  x
        let my=0; //마우스 y
        let speed =0.009; //마우스 얼마의 속도로 따라올지
        
        window.onload =function(){

            h1 = document.getElementsByTagName("h1")[0]; //마우스 부드럽게
            human = document.getElementsByClassName("human")[0];
            bg = document.getElementsByClassName("bg")[0];

            window.addEventListener("mousemove",mouseFunc,false);

            function mouseFunc(e){
                x= (e.clientX - window.innerWidth / 2); // 창의 반 크기를 마우스 움직임 크기에서 빼기
                y= (e.clientY - window.innerHeight / 2);
                
            }
            loop();  //마우스 부드럽게
        }  
        function loop(){
            mx += (x - mx) *speed;
            my += (y - my) *speed;
            //console.log(x,mx)
            // h1.innerHTML ="x:"+x+"mx:"+mx; //x와 mx의 값 출력
            human.style.transform = "translate("+-(mx/6)+"px,"+ -(my/6)+"px)";
            // my 대신에 -my주면 반대로 움직임
            // 사진을 더 조금 움직이게 하고 싶으면 mx,my값을 나눠준다 -> mx/6,my/원하는 수
            bg.style.transform = "translate("+ (mx/2)+"px,"+ (my/2)+"px)";

            window.requestAnimationFrame(loop);
        }
        
    </script>
    </head>
    <body>
        
          
          <div class="topnav">
            <a href="#">Player</a>
            <a href="#">Weapon</a>
            <a href="#">추천추천</a>
            <a href="https://www.google.com/">team 5</a>
          </div>

        <img src="lolo.png"  width ="100" height-= "100" class = "human" alt="배틀그라운드 로고"> 
        <img src="obj.png" class = "bg" alt="사막배경">
       
        
  </body>
  </html>


            width: 500px;
            left:calc(50% - 150px) ; /*사진 가운데로*/ 
            z-index: 100;  /*사람 이미지 맨 앞으로 갖고오기*/
        }
        /* .bg{} */
        li {display: inline;}

    </style>
    
    
    <!-- <style type="text/css">
        body{cursor: url('cursor.cur'),auto;}

    </style> -->
    <script>
        let human;
        let bg;
        let h1;

        let x =0;
        let y =0;
        let mx=0;   //마우스  x
        let my=0; //마우스 y
        let speed =0.009; //마우스 얼마의 속도로 따라올지
        
        window.onload =function(){

            h1 = document.getElementsByTagName("h1")[0]; //마우스 부드럽게
            human = document.getElementsByClassName("human")[0];
            bg = document.getElementsByClassName("bg")[0];

            window.addEventListener("mousemove",mouseFunc,false);

            function mouseFunc(e){
                x= (e.clientX - window.innerWidth / 2); // 창의 반 크기를 마우스 움직임 크기에서 빼기
                y= (e.clientY - window.innerHeight / 2);
                
            }
            loop();  //마우스 부드럽게
        }  
        function loop(){
            mx += (x - mx) *speed;
            my += (y - my) *speed;
            //console.log(x,mx)
            // h1.innerHTML ="x:"+x+"mx:"+mx; //x와 mx의 값 출력
            human.style.transform = "translate("+-(mx/6)+"px,"+ -(my/6)+"px)";
            // my 대신에 -my주면 반대로 움직임
            // 사진을 더 조금 움직이게 하고 싶으면 mx,my값을 나눠준다 -> mx/6,my/원하는 수
            bg.style.transform = "translate("+ (mx/2)+"px,"+ (my/2)+"px)";

            window.requestAnimationFrame(loop);
        }
        
    </script>
    </head>
    <body>
        
          
          <div class="topnav">
            <a href="#">Player</a>
            <a href="#">Weapon</a>
            <a href="#">추천추천</a>
            <a href="https://www.google.com/">team 5</a>
          </div>

        <img src="lolo.png"  width ="100" height-= "100" class = "human" alt="배틀그라운드 로고"> 
        <img src="obj.png" class = "bg" alt="사막배경">
       
        
  </body>
  </html>

