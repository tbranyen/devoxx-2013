### HTML5 History API (commonly known as `pushState`) can be enabled with:

``` javascript
Backbone.history.start({ pushState: true });
```

Turns your urls into:

``` javascript
http://localhost/my-route-identifier
```

<script type="speaker-notes">
~ 1 minute

Pros:

- The preferred way to handle client side routing.
- Can be read by web servers.

Cons:

- Web server must be set up to handle requests,
  otherwise refreshing will be a 404.
</script>

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
