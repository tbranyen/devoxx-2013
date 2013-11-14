### Configuring Grunt ###

``` javascript
module.exports = function(grunt) {
  grunt.initConfig({
    // Task options go here.
  });

  // Load tasks installed from NPM.
  grunt.loadNpmTasks("grunt-some-plugin");

  // Required default task.
  grunt.registerTask("default", ["list", "of", "tasks"]);
};
```

``` bash
npm install -g grunt-cli
npm install grunt
grunt
```

<script type="speaker-notes">
- Create a Gruntfile.js in the root.

</script>

<style scoped>
  @host {
    background-color: #E48632;
    color: #FFF;
  }
</style>

