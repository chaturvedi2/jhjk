# jhjk
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <nav>
        <div class="logo">
            <img src="https://img.pagecloud.com/KP67Dw6F-A3GKDcAKHYv8Q5B02Q=/250x0/filters:no_upscale()/template-site-vigneto-auto/images/vignetto-wordmark-color.png" alt="">
        </div>
        <div class="lists">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">EVENTS</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
        </div>
    </nav>

    <div class="section1">
        <div class="child1">
            <p>Vigneto Vineyards</p>
        </div>
        <div class="child2">
            <h1>The ultimate food and <br> wine experience</h1>
        </div>
        <div class="child3">
            <p>I’m a text box. Double click me to edit the text or to change the way I look. You can change the font, size, color, and so much more.</p>
        </div>
    </div>

    <div class="section2">
        <div class="section2-content">
            <div class="content1">
                <p>Wine tasting experience</p>
            </div>
            <div class="content2">
                <h2>Every Empty Bottle Is Filled With A Great Story</h2>
            </div>
        </div>
    </div>

    <div class="section3">
        <div class="sec3-content1">
            <p>I’m a text box. Double click me to edit the text or to change the way I look. You can change the font, size, color, and so much more. For advanced styling options, click on “more” located on the right hand side of the text editing menu. Click once to move me or to bring up the resize handles and Squeegee Tool.</p>
        </div>
        <div class="sec3-content1">
            <p>The resize handles allow you to make me any size you want. The Squeegee Tool, located in the top left of any selected object, helps you move all objects below it up or down to create or remove space.  </p>
        </div>
    </div>

    <div class="section4">
        <div class="box1">
            <p>Montepulciano, Italy</p>
        </div>
        <div class="box2">
            <h1>Wine Pairs Nicely With <br> Good Friends</h1>
        </div>
        <div class="btn">
            <a href="#">Upcoming Events</a>
        </div>
    </div>

    <div class="section5">
        <div class="left-content">
          <h4>About</h4>
          <h1>Adventure Is The Best Way To Learn Something New</h1>
        </div>
        <div class="right-content">
          <p>I’m a text box. Double click me to edit the text or to change the way I look. You can change the font, size, color, and so much more. For advanced styling options, click on “more” located on the right-hand side of the text editing menu.</p>
          <p>Click once to move me or to bring up the resize handles and Squeegee Tool. The resize handles allow you to make me any size you want.</p>
          <p>I’m a text box. Double click me to edit the text or to change the way I look. You can change the font, size, color, and so much more.</p>
        </div>
      </div>

    <div class="section6">
    <section class="wine-tasting-section">
        <div class="image-container">
            <img src="https://img.pagecloud.com/1Su5UQTm0VNPZI1HR-FjUgNas_U=/1534x0:4873x3343/2100x0/filters:no_upscale()/classic-temp4/images/image-r2826.jpeg" alt="Wine Tasting">
        </div>
        <div class="content-container">
            <h4>Wine Tastings</h4>
            <h1>Book Your Next Adventure</h1>
            <p>I’m a text box. Double click me to edit the text or to change the way I look.</p>
            <a href="#" class="btn">Book A Tour</a>
        </div>
    </section>

    <section class="wine-tasting-section">
        <div class="content-container">
            <h4>Wine Tastings</h4>
            <h1>Book Your Next Adventure</h1>
            <p>I’m a text box. Double click me to edit the text or to change the way I look.</p>
            <a href="#" class="btn">Book A Tour</a>
        </div>
        <div class="image-container">
            <img src="https://img.pagecloud.com/-nyA88JQmxhP7pVrySt7wnYwvoc=/2100x0/filters:no_upscale()/classic-temp4/images/image-g9145.jpeg" alt="Wine Tasting">
        </div>
    </section>
</div>


    <div class="section7">
        <h3>A New Adventure Is Waiting <br> For You</h3>
    </div>

    <footer>
        <div class="logo">
            <img src="https://img.pagecloud.com/deTPIU0BHvuySlwiuGz44djGUjg=/250x0/filters:no_upscale()/template-site-vigneto-auto/images/vignetto-wordmark-white-2.png" alt="">
        </div>
        <div class="lists">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">EVENTS</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html,
  body {
    height: 100%;
    width: 100%;
  }
  
  a {
    text-decoration: none;
  }
  ul {
    list-style: none;
  }
  
  nav {
    width: 100%;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  
  .lists ul {
    display: flex;
    gap: 30px;
  }
  
  .lists ul li a {
    color: #000;
  }
  
  .section1 {
    min-height: 650px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 20px;
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url("https://img.pagecloud.com/7hnOrLYW57XbQ3_XqnxWMT9AeYg=/2100x0/filters:no_upscale()/collections/images/image-ID-b56c6a1d-367d-4c1d-eac3-fb4c3a5d2abb.jpeg");
  
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    color: white;
  }
  
  .section1 .child1 p {
    font-size: 16px;
    font-weight: 400;
    text-align: center;
    letter-spacing: 3px;
    line-height: 1.2;
    text-transform: uppercase;
  }
  .section1 .child2 h1 {
    text-align: center;
    line-height: 1;
    font-size: 62px;
    font-weight: 600;
  }
  .section1 .child3 p {
    width: 700px;
    text-align: center;
    line-height: 1.8;
    font-size: 18px;
    font-weight: 300;
  }
  
  
  .section2{
      padding-top: 100px;
      padding-left: 100px;
      padding-right: 100px;
      padding-bottom: 40px;
  }
  
  .section2-content{
      display: flex;
      flex-direction: column;
      align-items: flex-start;
  }
  
  .content1{
      height: auto;
      width: 540px;
      margin-bottom: 10px;
      color: #000;
      font-size: 15px;
      font-weight: 400;
      line-height: 1.2;
      text-transform: uppercase;
  }
  
  .content2{
      max-width: 800px;
      height: auto;
      color: #B09A08;
      text-align: left;
      font-size: 40px;
      font-weight: 600;
  }
  
  .section3{
      padding-top: 20px;
      padding-left: 100px;
      padding-right: 100px;
      padding-bottom: 140px;
      display: flex;
      align-items: center;
      justify-content: space-between;
  }
  
  .sec3-content1 p{
      line-height: 1.6;
      font-weight: 400;
      color: rgba(102, 108, 119);
      width: 540px;
  }
  
  .section4{
      display: flex;
      flex-direction: column;
      gap: 20px;
      height: 643px;
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url("https://img.pagecloud.com/KOm-w4J2svthj_4uhRxIlbB94eA=/2100x0/filters:no_upscale()/classic-temp4/images/image-d64bf.jpeg");
  
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;   
    color: white;
    padding-left: 200px;
    justify-content: center;
  }
  
  .section4 .box1 p{
      font-size: 14px;
      font-weight: 400;
      text-transform: uppercase;
      letter-spacing: 3px;
      line-height: 1.2;
  }
  
  .section4 .box2 h1{
      font-size: 64px;
      line-height: 1.2;
      font-weight: 600;
  }
  
  .section4 .btn:hover a{
      background-color: #B09A08;
      color: #F0F0F0;
  }
  
  .btn a{
      padding: 15px 25px;
      color: #B09A08;
      background-color: #F0F0F0;
      font-size: inherit;
      font-weight: inherit;
      line-height: inherit;
  }
  
  
  .section5 {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      padding-top: 100px;
      padding-left: 100px;
      padding-right: 100px;
  }
  
  .left-content {
  flex: 1;
  margin-right: 50px;
  }
  
  .left-content h4 {
  color: #B09A08; 
  font-size: 18px;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 10px;
  }
  
  .left-content h1 {
  font-size: 48px;
  font-weight: 700;
  line-height: 1.2;
  }
  
  .right-content {
  flex: 1;
  }
  
  .right-content p {
  margin-bottom: 20px;
  font-size: 16px;
  line-height: 1.8;
  }
  
  .section6 {
      background-color: #F0F0F0;
      padding: 50px;
  }
  
  /* Shared styles for both wine-tasting sections */
  .wine-tasting-section {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 auto;
    width: 1000px;
    background-color: white;
    height: 400px;
    padding: 20px;
    box-sizing: border-box;
  }
  
  .image-container {
    flex: 1;
    height: 100%; /* Makes sure the image takes up full container height */
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures image fills the container while maintaining aspect ratio */
    display: block;
  }
  
  .content-container {
    flex: 1;
    padding-left: 40px;
    height: 100%; /* Makes sure content takes up full container height */
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  
  .content-container h4 {
    color: #d4c45a;
    font-size: 16px;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 15px;
  }
  
  .content-container h1 {
    font-size: 42px;
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 20px;
  }
  
  .content-container p {
    font-size: 16px;
    margin-bottom: 20px;
    line-height: 1.6;
  }
  
  .wine-tasting-section .content-container .btn{
      padding: 15px 25px;
      /* background-color: #B09A08; */
      font-size: inherit;
      font-weight: inherit;
      line-height: inherit;
  }
  
  .section7{
      height: 500px;
      width: 100%;
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url("https://img.pagecloud.com/w7vuY6y4fZ9sZkbpl9ME-esgKnI=/2100x0/filters:no_upscale()/classic-temp4/images/image-t87ad.jpeg");
  
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
  .section7 h3{
      padding-top: 160px;
      padding-left: 100px;
      padding-right: 100px;
      padding-bottom: 160px;
      text-align: center;
      line-height: 1.5;
      font-size: 48px;
      font-weight: 600;
      letter-spacing: 1px;
      color: white;
  }
  
  footer{
      height: 300px;
      background-color: #242424;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 45px;
  }
  
  footer .lists ul li a{
      color: white;
  }
