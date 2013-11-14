Backbone has inheritance that works, but it leaves much to be desired.

``` javascript
var ModelDefinition = Backbone.Model.extend({
  // Instance properties go here, shared on all instances.
}, {
  // Class properties go here, only available on `ModelDefinition`.
});

// Create an instance of the ModelDefinition.
var modelInstance = new ModelDefinition();
```

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>


<script type="speaker-notes">
~ 45 seconds

- All Backbone constructs are extended and initialized the same way.
- TitleCase the constructs.
- camelCase the instances.

- Declarative approach.

- Implementation is not exposed.

- `initialize` is a special method which is called automatically.
</script>
