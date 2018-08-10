<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>DRAVAK</title>
  <meta name="viewport" content="widht-device-width">
  <style>
    body{
  font-family: sans-serif;
  font-size: 15px;
  line-height: 1.5;
  font:15px/1.5 sans-sherif;
  padding: 0;
  margin: 0;
  background-color: #f4f4f4;
}
.container{
  width:80%;
   margin: auto;
   overflow: hidden;
}
header{
  background: #35424a;
  color: #fff;
  padding-top: 30px;
  min-height: 70px;
  border-bottom: #e8491d 3px solid;
}
header a {
  color: #fff;
  text-decoration: none;
  text-transform: uppercase;
  font-size: 16px;
}
header ul{
  margin: 0;
  padding: 0;
}
header li{
  float:left;
  display:inline;
  padding:0 20px 0 20px;
}
header #meet{
  float:left;
}
header #meet{
  margin: 0;
}
header nav{
  float:right;
  margin-top: 33px;
}
header  .highlight,header .current a{
  color: #e8491d;
  font-weight: bold;
}
header a:hover{
  color: #cccccc;
  font-weight: bold;
}
#showcase{
  min-height: 400px;
  background: url("../images/pic2.jpg") no-repeat 0 -400px;
  background-size: cover;
  text-align: center;
  color: #fff;


}
#showcase h1{
  margin-top: 100px;
  font-size: 55px;
  margin-bottom: 10px;
}
#showcase p{
  font-size: 20px;
}
.button{
  height: 40px;
  border-radius: 20px;
  background: #e8491d;
  padding-left: 20px;
  padding-right: 20px;
  color: #fff;
}
.button:hover{
  cursor: pointer;
  background: #000;
  color: #fff;
}
#boxes{
  margin-top: 40px;
}
#boxes .box{
  float: left;
  text-align: center;
  width: 25%;
  padding: 10px;
}
#boxes .b1{
  margin-left: 60px;
}
#boxes .bb{
  margin-left: 60px;
  margin-top: 10px;
}
#boxes .box img{
  width: 100px;
}
footer{
  padding: 20px;
  margin-top: 20px;
  color: #fff;
  background-color: #e8491d;
  text-align: center;
}
aside#sidebar{
  float: left;
  width: 50%;
  margin-top: 10px;
}
article#picture{
  margin-top: 60px;
  width: 400px;
  height: 300px;
  float: right;
  border-bottom:#darkgray 4px solid;

}
aside#easy{
  float: right;
  width: 50%;
  margin-top: 10px;
}
article#pic{
  float: left;
  width: 3000px;
  height: 200px;
}
</style>
</head>
<body>
  <header>
  <div class="container">
    <div id="meet">
      <h1><span class="highlight" >DRAVAK</span> TECHNOLOGIES</h1>
    </div>
    <nav>
      <ul>
        <li class="current"><a href="index.html">home</a></li>
          <li><a href="products.html">products</a></li>
          <li><a href="contact.html">contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <section id="showcase">
    <div class="container">
      <h1>The Industrial IoT solution with patented hardware design.
</h1>
      <p>Protect and manage your valuable assets by using our integrated IoT hardware and cloud based software platform</p>
    </div>
    <div class="container">
      <button type="button" class="button">Download </button>
    </div>
  </section>
  <section id="boxes">
    <div class="container">
      <div class="box">
        <img src='./images/pic7.jpg'>
        <h3>Predictive Maintenance</h3>
        <p>Our data driven approach provides machine health monitoring and fault identification easy</p>
      </div>
      <div class="box">
        <div class="b1">
        <img src='./images/pic8.png'>
        <h3>Asset Management</h3>
        <p>Easily configure the charts for better understanding.</p>
      </div>
    </div>
      <div class="box">
        <div class="bb">
        <img src='./images/pic9.jpg'>
        <h3>Truly wireless</h3>
        <p>Our real time wireless vibration sensor hardware provides seemless connection for data analytics and asset maintenance.</p>
      </div>
    </div>
    </div>
  </section>
  <section id="main">
    <div class="container">
      <article id="picture">
        <img src="images/pic5.png">
      </article>
      <aside id="sidebar">
      <h1>WHAT WE PROVIDE</h1>
      <p>The Wireless Data Mote (WDM) is an IP-67 rated, portable and battery powered device for asset management and predictive maintenance in the industry. We help you remotly monitor machines and equipment thereby providing maximum uptime and increased productivity.

Bring your school into the 21st century and<strong>  revolutionise your next </strong></p>
</aside>
</section>
<section>
  <div class="container">
    <article id="pic">
      <img src="images/pic6.png">
    </article>
  <aside id="easy">
    <h1>HOW WE HANDLE</h1>
    <p>Plug-n-Play Predictive & Operative intelligence solution using edge computing, high frequency data and time series pattern recognition using Artificial Intelligence. Installs on any machine within a minute and digitizes it instantaneously.</p>
</aside>
</section>
<footer>
  <p>copyright DRAVAK 2018 &copy</p>
</footer>


</body>
</html>
