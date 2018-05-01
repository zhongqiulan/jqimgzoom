# 用法：

1、导入css
<link rel="stylesheet" type="text/css" href="css/magnifier.css">


2、html结构
<div class="magnifier" id="magnifier1">
    <div class="magnifier-container">
        <div class="images-cover"></div>
        <!--当前图片显示容器-->
        <div class="move-view"></div>
        <!--跟随鼠标移动的盒子-->
    </div>
    <div class="magnifier-assembly">
        <div class="magnifier-btn">
            <span class="magnifier-btn-left">&lt;</span>
            <span class="magnifier-btn-right">&gt;</span>
        </div>
        <!--按钮组-->
        <div class="magnifier-line">
            <ul class="clearfix animation03">
                <li>
                    <div class="small-img">
                        <img src="images/1.png" />
                    </div>
                </li>
                <li>
                    <div class="small-img">
                        <img src="images/2.png" />
                    </div>
                </li>
                <li>
                    <div class="small-img">
                        <img src="images/3.png" />
                    </div>
                </li>
                <li>
                    <div class="small-img">
                        <img src="images/4.png" />
                    </div>
                </li>
                <li>
                    <div class="small-img">
                        <img src="images/1.png" />
                    </div>
                </li>
            </ul>
        </div>
        <!--缩略图-->
    </div>
    <div class="magnifier-view"></div>
    <!--经过放大的图片显示容器-->
</div>

3、导入js
    <script src="http://www.jq22.com/jquery/jquery-1.10.2.js"></script>
    <script type="text/javascript" src="js/magnifier.js"></script>

4、初始化插件
$(function() {
      $('#magnifier1').imgzoon({magnifier:'#magnifier1'});
 });
