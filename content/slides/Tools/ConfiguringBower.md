### Configuring Bower ###

``` javascript
{
  "name": "app.toweatherproof.me",

  "dependencies": {
    "pure": "~0.3.0",
    "almond": "~0.2.6",
    "lodash": "~2.2.1",
    "backbone": "~1.1.0",
    "jquery": "~2.0.3",
    "requirejs": "~2.1.9",
    "lodash-template-loader": "~0.1.3"
  }
}
```

``` bash
npm install -g bower
bower install
```

<script type="speaker-notes">
- bower.json in the root.
- Specify the packages and versions.
- Follows semver.

- Install with NPM.
- Once configured, run bower install to
fetch.
</script>

<style scoped>
  @host {
    background-color: #A3F4FF;
    color: #6B5F23;
  }
</style>
