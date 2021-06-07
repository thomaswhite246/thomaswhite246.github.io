# thomaswhite246.github.io
DOCTYPE html>
<html lang="en">
  <head>
    <title>Audio PONG</title>
    <script src="../javascript/Tone.js"></script>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./pong-styles.css"/>

  </head>

  <body><center>
    <p>This is a generic PONG written in javascript, html, and css. The up and down arrows control the paddle on the right; w + s control the paddle on the left.</p>
    <div id="game">
      <div class="paddle" id="left-paddle"></div>
      <div class="paddle" id="right-paddle"></div>
      <div class="ball" id="ball"></div>
      <h1 class="score" id="left-score">0</h1>
      <h1 class="score" id="right-score">0</h1
    </div>

    <div id="instructions">
      <p>
        <strong><span style="text-decoration:underline;">INSTRUCTIONS:</span></strong><br/>
        <strong>W/S</strong> – move left paddle up/down<br/>
        <strong>cursor up/down</strong> – move right paddle up/down</br>
        <strong>R</strong> - reset</br>
        <strong>1</strong> – cycle right paddle computer control</br>
        <strong>2</strong> – toggle left paddle mouse control</br>
        <strong>M</strong> – toggle mute sound</br>
        <strong>N/B</strong> – volume up/down (0–10)</br></br>

      </p>
    </div>
    <div id="errors-debug">
      Computer control is <span id="computer-control-state">OFF</span><br/>
      Mouse control is <span id="mouse-control-state">OFF</span></br>
      Mute is <span id="mute-state">false</span><br/>
      Volume is <span id="volume-state">5</span> out of 10<br/><br/>
      ERRORS:<br/>
      <p id="errors"></p>
      DEBUG:<br/>
      <p id="debug"></p>
    </div>
    <script type="module" src="../javascript/pong-audio.js"></script>
    <script type="module" src="../javascript/pong-classes.js"></script>
    <script type="module" src="../javascript/pong-events.js"></script>
    <script type="module" src="../javascript/pong-util.js"></script>
    <script type="module" src="../javascript/pong-index.js"></script>
</center>  </body>
</html>
