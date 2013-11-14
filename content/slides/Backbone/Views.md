### Views

``` javascript
var SomeView = Backbone.View.extend({
  el: <element to attach to here>

  events: {
    // DOM Events added here.
  }
});

// Initialize the View.
var someView = new SomeView();
```

* Views can get super complex, look into a plugin to assist with large apps.
* No data binding out of the box (or even a usable `render` method).

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
