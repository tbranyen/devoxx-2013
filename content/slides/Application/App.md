### Defining application namespace. ###

<p>Useful for storing application specific constants and attaching modules to a
global namespace.</p>

``` javascript
var app = {
  // Where application is located in the DOM.
  mainElement: $("body"),

  // Store reference to API.
  api: "http://api.openweathermap.org/data/2.5/"
};
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

</script>
