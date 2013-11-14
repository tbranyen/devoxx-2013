### Create a reusable template with variable data. ###

``` markup
<script id="weather-template" type="text/template">
  <h4 class="forecast">
    <%= model.get("weather")[0].description %>
  </h4>

  <hr>

  <div class="region">
    <table class="pure-table pure-table-horizontal">
      <tbody>


  ...
</script>
```

<style scoped>
  @host {
    background: #FFF;
  }
</style>
