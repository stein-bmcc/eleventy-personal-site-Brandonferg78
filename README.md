 <!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Text Center</title>
    <style type="text/css">
      body
      {
      Padding:0;
      margin: 0;
      background:#ffd200;
         }

      #title{
        padding:250px 0px;
        
      }
      
      h1
      {
        font-size: 5em;
        margin:0;
        padding:0;
        text-align: center;
        font-family:arial;
/*         position: absolute;
        top:50%;
        left: 50%;
        transform: translateX(-50%) translateY(-50%); */
      }

      {
        box-sizing: border-box;
        
      }
      .row{
/*         width:30%;
        float:left;
        margin- left: 30px;
        margin-center:40px;
        margin-right:40px;
        padding: 30px; */
      }

      .row img{
        height:400px;
      }
      footer{
        text-align:center;
      }

      #work{
        display:flex;
      }


      #work img{
        max-width:300px;
        
        padding:20px;
      }


      
      .btn{
        
        dispay:inline-block;
        background:#0f0;
        padding:20px;
      }

          #div1{
      background-color: green;
      width:23.33%;
      float: right;
    }
    #div2{
      background-color: green;
       width:23.33%;
      float: left;
    }
    #div3{
      background-color: green;
       width:53.33%;
      margin:0 auto;
    }
   
    </style>
    </head> 
<body>
  
  <section>
  <div id="div1">Brandon Ferguson</div>
  <div id="div2">College:BMCC</div>
  <div id="div3">Subject:Art History</div>
  <br style="clear:both;">
    
  </section>
  <section id="title">
<h1>ART History</h1>

</section>

  <section id="work">

       <img src="app photo 1.png"style="width: 100%">

       <img src="app photo 2.png"style="width: 100%">

       <img src="app photo.3"style="width: 100%">

     
  </section>
<footer>
 <body>
    <h1>Contact Us</h1>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br><br>
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" cols="30" required></textarea><br><br>
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
      
      