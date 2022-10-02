<html>
<head>
    <title>Simple webspage desgin</title>
    <style>
        .main {
    width: 100%;
    background-image:url('3.jpg');
    background-position: center;
    background-size: cover;
    height: 100vh;
}
.navbar{
      width: 1200px;
      height: 75px;
      margin:auto;
}
.icon{
        width: 100px;
       float: left;
       height: 70px;
  }
  .logo{
    color:whitesmoke;
    font-size: 25px;
    font-family:Georgia;
    padding-left: 20px;
    float:left;
    padding-top: 10px;
  }
  .menu{
    width:100px;
    float: left;
    height: 70px;
  }
  ul{
    float:left;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  li{
    list-style: none;
    margin-left: 20px;
    margin-top: 10px;
    font-size: 15px;

  }
 a{
    color: white;
    font-family: Serif;
    font-weight: bold;
 }
 a:hover{
    color: blueviolet;
 }
.search{
    width:330px;
    float:right;
    margin-left:270px;
    margin-bottom: 40px;
    height:70px;

    
}
.srch{
 font-family:Arial;
 width:200px;
 height: 40px;
 background: transparent;
 margin-top: 13px;
 border: 1px solid;
 color:aliceblue;
 font-size: 16px;
 float:left;
 padding: 13px;
 border-bottom-left-radius:5px ;
 border-top-left-radius: 5px;
}

.btn{
    width:100px;
    height:40px;
    background-color:gray;
    margin-top:13px;
    color:white;
    border:2px solid;
    font-size: 15px;
    border-bottom-left-radius:5px ;
     border-top-left-radius: 5px;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.btn:hover{
    color:blueviolet;
}

.content{
    width:1200px;
    height:auto;
    position: relative;
}

.content .para{
    padding-left:20px;
    padding-bottom:25px;

}
.btn1{
    width:100px;
    height:40px;
    background-color:white;
    margin-top:13px;
    color:gray;
    border:2px solid;
    font-size: 15px;
    border-bottom-left-radius:5px ;
     border-top-left-radius: 5px;
}

.btn1:focus{
    outline: none;
}

.btn1:hover{
    color:blueviolet;
}
    </style>    
</head>


<body>
<div class="main">
    <div class="navbar">
        <div class="icon">
            <h1 class="logo">CRAFT</h1>
        </div>
        <div class ="menu">
            <ul>
                <li><a href="home.html"> HOME </a></li>
                <li><a href="#"> SERVICES </a></li>
                <li><a href="#"> DESIGN </a></li>
                <li><a href="#"> PRODUCTS </a></li>
                <li><a href="https://pmaymis.gov.in/"> CONTACT</a></li>
            </ul>
        </div>
        <div class ="search">
            <input class="srch" type="search" name="" placeholder="type to text">
            <a href="#"> <button class="btn">search</button></a>
        </div>
        </div>

        <div class="content">
            <h1> Welcome to simple  web page </h1>
            <p class ="para"> web page. A document which can be displayed in a web browser such as Firefox, Google Chrome, Opera,<br>
                 Microsoft Internet Explorer or Edge, or Apple's Safari. These are also often called just "pages." website.<br>
                 A collection of web pages which are grouped together and usually connected together in various ways</p>

                 <a href="#"> <button class="btn1"> Join US </button></a>
    </div>
</div>
</body>
</html>