Sebastian Melo Front Developer in Process...
Geeker Life & Platzerito
![Image of Banner](https://geekculture.co/wp-content/uploads/2020/05/halo-2-anniversary.jpg)

<!DOCTYPE html>
<html>
<style>
#div1 {
  font-size:48px;
}
</style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<body>

<div id="div1" class="fa"></div>

<script>
function chargebattery() {
  var a;
  a = document.getElementById("div1");
  a.innerHTML = "&#xf244;";
  setTimeout(function () {
      a.innerHTML = "&#xf243;";
    }, 1000);
  setTimeout(function () {
      a.innerHTML = "&#xf242;";
    }, 2000);
  setTimeout(function () {
      a.innerHTML = "&#xf241;";
    }, 3000);
  setTimeout(function () {
      a.innerHTML = "&#xf240;";
    }, 4000);
}
chargebattery();
setInterval(chargebattery, 5000);
</script>

<p>This example demonstrates how to use an icon library to make an animated effect.</p>
</body>
</html>
