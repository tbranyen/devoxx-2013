### Starting the application. ###

``` javascript
// This is triggered in the HTML once all the source code loads.
app.start = function() {
  // Store reference to Router.
  app.router = new Router();

  // Kick off the Backbone route handling.
  Backbone.history.start();
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
- Very useful for loading individual modules without starting the application.
  - If you start the application you may have side effects that influence
    modules, which isn't very good for testing with a clean slate.
</script>
