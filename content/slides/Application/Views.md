#### WeatherView ####

``` javascript
// The easy one.
var WeatherView = Backbone.View.extend({
  initialize: function() {},

  render: function() {},

  renderFailure: function() {}
});
```

#### FormView ####

``` javascript
var FormView = Backbone.View.extend({
  el: ".pure-form",

  events: {},

  changeWeather: function(ev) {},
  showWeather: function(ev) {},
  autoDetect: function(ev) {},

  initialize: function() {}
});
```

<style scoped>
  @host {
    background: #FFF;
  }

  h4 {
    padding-bottom: 4px;
    display: block;
    width: 100%;
    margin-bottom: 0px;
    text-align: center;
  }
</style>
