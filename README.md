<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nghe nhạc thư giãn</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w==" crossorigin="anonymous" />
<link rel="preconnect" href="https://fonts.gstatic.com">
<link rel="stylesheet" href="css/style.css">
<link rel="icon" href="imgs/logo192.png" />
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<div class="player">
  <!-- Dashboard -->
  <div class="dashboard">
    <!-- Header -->
    <header>
      <h4>Bản nhạc đang phát:</h4>
      <h2>String 57th & 9th</h2>
    </header>

    <!-- CD -->
    <div class="cd">
      <div class="cd-thumb">
      </div>
    </div>

    <!-- Control -->
    <div class="control">
      <div class="btn btn-repeat">
        <i class="fas fa-redo"></i>
      </div>
      <div class="btn btn-prev">
        <i class="fas fa-step-backward"></i>
      </div>
      <div class="btn btn-toggle-play">
        <i class="fas fa-pause icon-pause"></i>
        <i class="fas fa-play icon-play"></i>
      </div>
      <div class="btn btn-next">
        <i class="fas fa-step-forward"></i>
      </div>
      <div class="btn btn-random">
        <i class="fas fa-random"></i>
      </div>
    </div>

    <input id="progress" class="progress" type="range" value="0" step="1" min="0" max="100">

    <audio id="audio" src=""></audio>
  </div>

  <!-- Playlist -->
  <div class="playlist"></div>



  <script src="js/main.js"></script>
</div>
