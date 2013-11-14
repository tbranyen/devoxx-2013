### Models and Collections

``` javascript
var Item = Backbone.Model.extend({
  // Point to an external REST resource to sync with.
  url: ""
});

var ItemCollection = Backbone.Collection.extend({
  model: Item
});

// Initialize the Model.
var item = new Item();

// Add a new property.
item.set("newProp", "someValue");
```

* Both Model and Collection proxy functional methods from underscore.

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
