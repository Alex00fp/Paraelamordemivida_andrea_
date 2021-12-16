<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <! - Las 3 metaetiquetas anteriores * deben * colocarse primero, y cualquier otro contenido * debe * seguirlo. ->
         <title> Feliz año nuevo </title>
 
    <!-- Bootstrap -->
    <link href="bootstrap/css/bootstrap.css" rel="stylesheet">
 
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://cdn.bootcss.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://cdn.bootcss.com/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
  
 
    <div class="container">
  <div class="row clearfix">
    <div class="col-md-12 column">
      <div class="row clearfix">
    
 
                         <h1 align = "center"> Feliz año nuevo </h1>
          <div class="form-horizontal" role="form" align="center">
 
            <div class="form-group">
               <label for="input" class="control-label" >PLEASE ENTER THE SECRET</label>
              <br>
                                 <input class = "form-control" id = "input" placeholder = "Ingrese el día que estuvimos juntos" />
      
            </div>
           
            <div class="form-group">
              <button align="center" type="submit" onclick="check()" class="btn btn-block btn-primary btn-lg ">ENTER</button>
              
            </div>
 
 
          </div>
        </div>
      
      </div>
    </div>
  </div>
</div>
    <script language="javascript">
      function check(){
        var value = document.getElementById("input").value; 
         
        if(value=="1023"||value=="171023"||value=="20171023"){
          window.location.href="formynana.html";
           return true;
          
        } 
         else{
          alert("secret is false");
          return false;
         }
       
      }
       
    document.onkeydown=keyListener;
    function keyListener(e){
             // Cuando se presiona la tecla enter, se ejecuta nuestro código
    if(e.keyCode == 13){
      check();
    }
}
    </script>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="bootstrap/js/jquery-1.11.3.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="bootstrap/js/bootstrap.min.js"></script>
  </body>
</html>
<!doctype html>
<html>
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, user-scalable=no" />
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=Edge">
<title>jwplayer</title>
<meta content="" name="Keywords">
<meta content="" name="Description">
<meta name="format-detection" content="telephone=no">
</head>
<body>
 
<div id="mediaplayer"></div> 
 
<script src="jwplayer/jwplayer.js"></script>
<script type="text/javascript">
jwplayer('mediaplayer').setup({
    'flashplayer': 'jwplayer/jwplayer.flash.swf',
	'image': 'image.jpg',
    'id': 'playerID',
    'width': '100%',
	'aspectratio':'16:9',
    'file': 'video.mp4'
  });
</script>
</body>
</html>
