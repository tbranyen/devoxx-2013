### Configuring RequireJS ###

``` javascript
require.config({
  paths: {
    "vendor": "../vendor",
    "almond": "../vendor/bower/almond/almond",
    "underscore": "../vendor/bower/lodash/dist/lodash.underscore",
    "lodash": "../vendor/bower/lodash/dist/lodash",
    "jquery": "../vendor/bower/jquery/jquery",
    "backbone": "../vendor/bower/backbone/backbone",
    "ldsh": "../vendor/bower/lodash-template-loader/loader"
  },

  shim: {
    "backbone": {
      deps: ["jquery", "underscore"],
      exports: "Backbone"
    }
  }
});
```

<script type="speaker-notes">
- app/config.js

- Need to manually specify the path to each dependency.

- Shimming is required for libraries that are not AMD compatible.

- More and more libraries are becoming AMD compliant.
  - The next version of Backbone will include AMD support.

- This configuration is only part of it.
- Still need to configure optimizer and runtime.
</script>

<style scoped>
  @host {
    background-color: #FFD3A3;
    color: #611F1F;
  }
</style>

