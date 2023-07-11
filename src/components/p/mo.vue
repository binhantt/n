<template>
    <div class="hed">
        <div class="hed2">
        <div class="hed-logo">
            <div>
            <img src="https://st.nettruyenplus.com/data/logos/logo-nettruyen.png">
            </div>
        
        <div class="hed-seach-2">
            <div class="hed-sech-2-2">
                 <input type="text" placeholder="tim kiêm">
                 <button>
                     <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                     <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                     </svg>
                 </button>
             </div>
            </div>
         </div>
        <div class="Examples">
                 <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-lightbulb" viewBox="0 0 16 16">
                 <path d="M2 6a6 6 0 1 1 10.174 4.31c-.203.196-.359.4-.453.619l-.762 1.769A.5.5 0 0 1 10.5 13a.5.5 0 0 1 0 1 .5.5 0 0 1 0 1l-.224.447a1 1 0 0 1-.894.553H6.618a1 1 0 0 1-.894-.553L5.5 15a.5.5 0 0 1 0-1 .5.5 0 0 1 0-1 .5.5 0 0 1-.46-.302l-.761-1.77a1.964 1.964 0 0 0-.453-.618A5.984 5.984 0 0 1 2 6zm6-5a5 5 0 0 0-3.479 8.592c.263.254.514.564.676.941L5.83 12h4.342l.632-1.467c.162-.377.413-.687.676-.941A5 5 0 0 0 8 1z"/>
                 </svg>
        </div>
        <div class="Heading">
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-chat" viewBox="0 0 16 16">
            <path d="M2.678 11.894a1 1 0 0 1 .287.801 10.97 10.97 0 0 1-.398 2c1.395-.323 2.247-.697 2.634-.893a1 1 0 0 1 .71-.074A8.06 8.06 0 0 0 8 14c3.996 0 7-2.807 7-6 0-3.192-3.004-6-7-6S1 4.808 1 8c0 1.468.617 2.83 1.678 3.894zm-.493 3.905a21.682 21.682 0 0 1-.713.129c-.2.032-.352-.176-.273-.362a9.68 9.68 0 0 0 .244-.637l.003-.01c.248-.72.45-1.548.524-2.319C.743 11.37 0 9.76 0 8c0-3.866 3.582-7 8-7s8 3.134 8 7-3.582 7-8 7a9.06 9.06 0 0 1-2.347-.306c-.52.263-1.639.742-3.468 1.105z"/>
            </svg>
        </div>
    </div>
    <div class="login-2">
        <div class="login">
             <a href="">Đăng nhập</a>
        </div>
        <div class="Đng-ky ">
            <a href="">Đăng ký </a>
        </div>
    </div>
    </div>
</template>
<style>
    .hed{
        display: flex;
        align-items: center;
        width:1366px;
        height: 50px;
        background-image: url(https://st.nettruyenplus.com/Data/Sites/1/skins/comic/images/bg_header_2017.jpg);
    }
    .hed-logo{
        display: flex;
        align-items: center;
        margin-left: 200px;
    }
    .hed-seach{
        padding-left: 90px;
        padding-right: 90px;
       
    }
    .hed-seach-2{
        padding-left: 50px;
        padding-right: 50px;
    }
    .hed-sech-2-2{
        border:  none ;
        background-color: white;
        display: flex;
        align-items: center;
    }
    .hed-sech-2-2 input{
        width: 360px;
        height: 30px;
        border: none;
        outline: none;
        font-family: Tahoma,sans-serif,Helvetica,Arial;
        font-weight: 400;
        font-size: 14px;
    }
    .hed-sech-2-2 button{
        border: none;
        cursor: pointer;
    }
    .Examples{
        cursor: pointer;
        padding-right:5px;
    }
    .hed a{
        color: white;
        list-style: none;
        height: none;
        text-decoration: none;
    }
    .login{
        margin-left: 9px;
        box-sizing: inherit;
    }
    .hed2{
         display: flex;
    }
    .login-2{
        margin-left: 150px;
        display: flex;
    }
    .login-2>.login::after{
         content: "/";
         color: white;
    }
</style>
<script>
export default{
    name:"mo"
  
 }
</script>