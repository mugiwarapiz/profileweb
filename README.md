<!DOCTYPE html>
<html>
<body>
<style>
body {
  background-image: url("background.jpg");
}
</style>

<h2>Creating text using JavaScript</h2>

<p id="demo"></p>
<p id="demo1"></p>
<p id="demo2" style="display:none">Why Click It?</p>

<button type="button" onclick="document.getElementById('demo2').style.display='block'">Don't Click</button>
<script>
document.getElementById("demo").innerHTML = "Tulis je apa2 dalam script document tu";
document.getElementById("demo1").innerHTML = "Macam2 boleh";

</script>

</body>
</html>
