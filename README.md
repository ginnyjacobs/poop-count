# poop-count
You read that right.
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>GJ Creative</title>
    <style>
      #ginny-headline { color: #3cb371 }
      body { font-family: avenir; }
    </style>
  </head>

  <body>
    <h1 id="ginny-headline">Ginny made a website!!!!</h1>
    <h4>Poop count: <span id="poop-count">0</span></h4>
    <button type="button" onclick="poop()">💩 POOP 💩</button>

    <script>
      let poopCount = 0

      function poop () {
        poopCount++
        console.log("Ginny is pooping, count: ", poopCount)
        let poopElement = document.getElementById("poop-count")
        poopElement.innerText = poopCount
      }
    </script>
  </body>
</html>
