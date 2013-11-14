For instance, there is no clean way to create a custom construct.

``` javascript
function CustomConstruct() {
  // Initialization code here.
}

// Instance properties
_.extend(CustomConstruct.prototype, {
  someMethod: function() {}
});

// Awkward tacking this on.
CustomConstruct.extend = Backbone.Model.extend;
```

<script type="speaker-notes">
~ 40 seconds

- Does not look very Backbone like.
- May not always work as it's undocumented.
</script>

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
