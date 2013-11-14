### Defining a Router. ###

``` javascript
var Router = Backbone.Router.extend({
  routes: {
    "": "home",
    "weather/:city": "showWeather",
    "weather/:lat/:lng": "showWeatherByLatLng"
  },

  // Useful for setting up models and collections shared throughout the
  // application.
  initialize: function() {},

  // Called when `/` is hit.
  home: function() {},

  // Called when `/weather/someCityName` is hit.
  showWeather: function(city) {},

  // Called when `/weather/someLat/someLong` is hit.
  showWeatherByLatLng: function(lat, lng) {}
});
```

<style scoped>
  @host {
    background: #FFF;
  }

  h3 {
    color: #333;
  }

  pre {
    min-width: 100%;
  }

  pre code {
    line-height: 23px;
  }
</style>

<script type="speaker-notes">
- Very useful for loading individual modules without starting the application.
  - If you start the application you may have side effects that influence
    modules, which isn't very good for testing with a clean slate.

- With large applications you may want many routers to isolate concerns.
</script>
