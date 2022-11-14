<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>木一珘的个人网站</title>
    <style>
        body{
            margin:0;
            background-color: #eee;
            display: flex;
            height:100vh;
        }
       
        .hezi{
            background-color: white;
            box-shadow: 0 2px 3px #c8c8c8; 
        }
        .ma8{
            margin: 8px;
        }
        .mgzyx{
            margin: 0 8px 8px 8px;
        }
        .mgt{
            margin-top: 8px;
        }
        .left{
            width:200px;
            z-index: 2;
            display: flex;
            flex-direction: column;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 20px;
        }   
        .right{
            flex: 1;
            display: flex;
            flex-direction: column;
        }
       
        .dingbu{
           height: 60PX;
           z-index: 1;
        }
        .neirong{
            flex: 1;
            display: flex;
            flex-direction: row;
            overflow: auto;
        }
     
       .zuobian{
            flex:3;
            display: flex;
            flex-direction: column;
       }
       .shuju{
    
            display: flex;

       }
       .liebiao{
        display: flex;
        flex-direction: column;
       }

       .youbian{
            flex:1;
            flex-direction: column;
       }
       .touxiang{
            height: 100px;
            border-bottom: 3px solid #eee;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
       }
       img{
            margin: 5px;
       }
       @media screen and (max-width=600px){
        .yincang{
            display: none;
        }
       }
       
    </style>
</head>
<body>
    <!-- 侧边栏 -->
    <div class="left hezi yincang">
        <div class="touxiang">
            <img src="img/个人中心.png" style="width: 60px;" alt="">
            Mu Yizhou
        </div>
        <div class="daohanglan">
            <div class="daohang1"></div>
        </div>
    
    </div>
    <!-- 主区域 -->
    <div class="right ">
        <!-- 顶部导航栏 -->
        <div class="dingbu hezi">

        </div>
        <!-- 内容区 -->
        <div class="neirong">
               <!-- 左边 -->
               <div class="zuobian">
                    <!-- 数据区 -->
                    <div class="shuju">
                        <div class="shuju1 hezi ma8" style="flex: 1; height: 100px;"></div>
                        <div class="shuju2 hezi ma8" style="flex: 1;height: 100px;"></div>
                        <div class="shuju3 hezi ma8" style="flex: 1; height: 100px;"></div>
                        <div class="shuju4 hezi ma8" style="flex: 1; height: 100px;"></div>
                    </div>
                    <div class="liebiao">
                        <div class="liebiao1 hezi mgzyx" style="height: 160px;"></div>
                        <div class="liebiao1 hezi mgzyx" style="height: 160px;"></div>
                        <div class="liebiao1 hezi mgzyx" style="height: 160px;"></div>
                    </div>
               </div>
               <!-- 右边 -->
               <div class="youbian">
                    <!-- 消息区 -->
                    <div class="xiaoxi hezi mgt  " style="height: 200px;"></div>
                    <div class="tishi hezi mgt" style="height: 300px;"></div>
               </div>
        </div>

    </div>
</body>
</html>re01-one
