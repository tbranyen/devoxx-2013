### Routers and History

``` javascript
var ApplicationRouter = Backbone.Router.extend({
  routes: {
    // Mapping identifiers to methods goes here.
  },

  // Route methods here.
});

// Initialize the Router.
var applicationRouter = new ApplicationRouter();

// Tell Backbone to start monitoring the changes in browser history.
Backbone.history.start();
```

* Multiple routers can be used so long as the route paths are unique.
* Duplicate route identifiers will override the previously defined routes.

<script type="speaker-notes">
~ 1 minute

- Very important way to track state within the application.

- The router is designed to take key:val in the routes object.
  - These correspond to an identifier and a method name.

- Methods are defined on the construct prototype.

- You must initialize with at least one route.
- Duplicates are not recommended as the last one will override.
</script>

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
