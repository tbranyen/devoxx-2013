### Default behavior is to use location.hash fragments.

``` javascript
http://localhost/#my-route-identifier
```

<script type="speaker-notes">
~ 1 minute

Pros:

- Allows you to track state without refreshing the page.
- Do not require a configured web server to use.

Cons:

- These cannot be read by a web server. (No preloading)
- Unable to be parsed by search engines.
- Are abuse of the technology.
</script>

<style scoped>
  @host {
    background: #FFF;
  }

  ul {
    font-size: 20px;
  }
</style>
