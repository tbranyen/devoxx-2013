Designed around events - Almost all built in constructs emit events about their state. 

Events are a powerful way to reduce coupling.

``` javascript
// Is a mixin.
var myObj = _.extend({}, Backbone.Events);

// Wait for the event `something` to be triggered.
myObj.on("something", function(data) {
  console.log(data);
});

// Trigger the event from anywhere, passing a String.
myObj.trigger("something", "with some data!");
```

<script type="speaker-notes">
~ 1 minute.

- Very useful design feature are that events are prolific.

- Backbone.Events is a mixin that can be added to any object.

- Contains `on`, `off`, `listenTo`, `stopListening` `once` and `listenToOnce`.

- Greatly reduce coupling, objects do not need to know about eachother.
  - Events stack.

- Documentation contains all emitted events.
</script>

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
