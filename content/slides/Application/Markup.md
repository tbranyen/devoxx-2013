### Initial page markup ###

``` markup
<!doctype html>
<html lang="en">
<head>
  <title>WeatherProof</title>
</head>
<body>
  <div class="background"><img src="images/background.jpg"></div>

  <h1>Weather<span class="proof">prooF</span></h1>

  <form>
    <img class="detect" src="images/geolocation.png">
    <input type="text" placeholder="Find location.">
  </form>

  <div class="weather"></div>

  <footer>
    Powered by: <a href="http://openweathermap.org/">OpenWeatherMap</a>
  </footer>
</body>
</html>
```

<style scoped>
  @host {
    background: #FFF;
  }
</style>
