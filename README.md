<html lang="pt">
<head>

  <meta charset="UTF-8">
  <title>-/shadoww/-</title>
  <link rel="shortcut icon" href="DEVILSHYTINMYEYEZ.html" type="image/png">
  <link href="https://fonts.googleapis.com/css?family=Macondo" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="../cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
  <link rel="shortcut icon" sizes="196x196" href="images/icons/1.ico">
</head><span id="warning-container"><i data-reactroot=""></i></span>

<body>

<video autoplay="" loop="" id="video-background" muted="" plays-inline="">
  <source src="DEVILSHYTINMYEYEZ.mp4" type="video/mp4">
</video>
<audio autoplay="1" loop="1" volume="1">
	<source src="DEVILSHYTINMYEYEZ.mp3" type="audio/mp3">
</audio>
<div class="section">
  </svg>
</div>
<div class="title">S H A D O W W</div>

<div class="links">
"
<a class="clean-link" href="https://steamcommunity.com/id/shadowtkk" target="_blank"><span class="text-hover">Steam</span></a>  
"
<a class="clean-link" href="https://www.twitter.com/null/" target="_blank"><span class="text-hover">Twitter</span></a> 
"
<a class="clean-link" href="https://www.youtube.com/channel/UCN-sbM1_FqO8mq-u6q6dwgw?view_as=subscriber" target="_blank"><span class="text-hover">Youtube</span></a>
"
<br>
</div>
<div class="died" id="blyad">0 7 7 7</div>

<div class="curtain"></div>
<canvas id="canvas"></canvas>
</div>

<script src="../cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="js/index.js"></script>

<script>
  $(function() {
    var title = document.title,
      animSeq = ["/", "-", "\\", "|", "-"],
      animIndex = 0,
      titleIndex = 0;
  
    function doInverseSpinZeroPitch() {
      var loadTitle = title.substring(0, titleIndex);
      if(titleIndex > title.length) {
        animIndex = 0;
        titleIndex = 0
      }
      if(animIndex > 3) {
        titleIndex++;
        animIndex = 0
      }
      document.title = loadTitle + animSeq[animIndex];
      animIndex++
    }
    window.setInterval(doInverseSpinZeroPitch, 150);
  });
  </script>d

</body>
</html>
