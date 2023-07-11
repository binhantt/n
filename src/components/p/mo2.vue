<script>
      name:"mo2"
</script>
<template>
    <div class="menu2">
   <ul class="menu n ">
        <li class="n home borde">
            <a href=""><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="currentColor" class="bi bi-house-door-fill" viewBox="0 0 16 16">
  <path d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5Z"/>
</svg></a>
        </li>
        <li class="n borde "><a href="" class="mx">hot</a></li>
        <li class="n borde  "><a href="" class="mx">theo dõi</a></li>
        <li class="n  borde"><a href="" class="mx">lich sữ</a></li>
        <li class="n the-l2 borde">
            <li class="theloi2 ">
            <svg :class="thel2" xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
            </svg>
            <a class="n  efwfwf">Thể loại</a>
        </li>
            <ul class=" n the-l">
            <li><a href="">ngôn tình</a></li>
            <li><a href="">viễn tưởng</a></li>
            <li><a href="">anime</a></li>
            <li><a href="">hanh động</a></li>
            </ul>
        </li>
        <li class="n borde">
           <a class="mx"> xêp hang</a>

            <ul class=" n xep-hng">
                <li><a href="">top all</a></li>
                <li><a href="">op thang</a></li>
                <li><a href="">top ngay</a></li>
                <li><a href="">top tuan</a> </li>
            </ul>
        </li>
        <li class="n borde"><a href="" class="mx">tim truyện</a></li>
        <li class="n borde"><a href="" class="mx">con gai</a></li>
        <li class="n borde"><a href="" class="mx"> con trai</a></li>
        <li class="n borde"><a href="" class="mx">group</a></li>
        <li class="n borde"><a href="" class="mx">fanpge</a></li>
   </ul>
</div>
</template>
<style>
.menu2 .mx{
    padding: 17px;
}

.menu2 .home svg{
    padding: 17px;
}

.borde{
    border: 2px none;
    height: 45px;
}
.menu2>ul>li>.home> a:hover{
    background-color: #e4e4e4;
}
.borde a{
    padding-left: 0px;
    padding-bottom: 0px;
    padding-right: 5px;

    
}
.theloi2{
    display: flex;
    align-items: center;
     text-decoration: none;
    list-style: none;   
    padding-top: 16px;
    padding-right:17px ;
}
.menu2{
    background-color: #e4e4e4;
    width: 1363px;
    height: 50px;
}
.menu{
    text-decoration: none;
    list-style: none;
    float: left;
    margin-left: 159px;
    margin-bottom: 0px;
    display: flex;
    margin-right: 59px;
    margin-top: 0px;
    font-size: 14px;
    text-transform: uppercase;
   
    font-family: Tahoma,sans-serif,Helvetica,Arial;
}
.the-l{
    display: none;
}
.xep-hng{
    display: none;
}
.n{
    color: #5b4242;
    
}
a{
    list-style: none;
    text-decoration: none;
}
.menu2 a{
    color: #5b4242;
}
.menu2 ul>a::before{
    box-sizing: border-box;
}
.menu2::before{
    content: " ";
    display: table;
}
.n a::before{
    content: " ";
    display: table;
}
.bi-house-door::before{
   content:"\f015";
}
</style>