<template>
  <div class="slidmenu">
    <header>
        <div class="logo">
            <img src="../assets/s_LOGO_1-1.png"/>
        </div>
        <ul>
            <li><a href="#">PORTFOLIO</a></li>
            <li><a href="#">MAGAZINE</a></li>
            <li><a href="#">MOVIE CLIP</a></li>
            <li><a href="#">CONTACT</a></li>
            <li><a href="#">MEMBER’S</a></li>
        </ul>
        <div class="footer">
            <div>
                <p>kakao: rayseo@carrotglobal.com</p>
                <p>email: rayseo@carrotglobal.com</p>
            </div>
            <div>
                <i class="fab fa-facebook"></i>
                <i class="fab fa-instagram-square"></i> 
                <i class="fab fa-pinterest"></i>
            </div>
        </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'SideMenu',
  props: {  
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
body{
  margin:0px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.slidmenu{
    // height:100%;
}
header{
    padding:20px;
    background:black;
    // height:100%;
    max-width:25%;
    .logo{
        width:100%;
        text-align:100%;
        padding-top:80px;
        padding-bottom:20px;
        img{
            width:40%;
        }
    }
    ul{
        width:100%;
        li{
            width:100%;
            padding-top:30px;
            padding-bottom:30px;
            a{
                font-size:17px;
                color:#5b5b5b;;
                text-decoration:none;
                font-weight:bold;
            }
        }
    }
    .footer{
        margin-top:100px;
        overflow:hidden;
        div{
            // display:inline-block;
            float:left;
            width:69%;
             &:last-child{
                 width:30%;
                 padding-top:30px;
                 i{
                    color:#5b5b5b;
                    font-size:25px;
                    margin-left:15px;
                 }
             }
             p{
                color:#5b5b5b;;
             }
        }
        
    }
}
</style>
