### A typical workflow. ###

* Create initial page markup.
* Define an application namespace to attach constructs from.
* Define Routers/Views/Models/etc.
* Once all code has loaded and all constructs are defined, start the app.
* The Router determines what to show.
* Views hook into the DOM and provide the necessary bridge.
* Models store data.
* Lots of glue to hold it together.

<style scoped>
  @host {
    background: #FFF;
  }

  h3 {
    color: #333;
  }

  ul {
    font-size: 20px;
  }

  li {
    line-height: 35px;
  }
</style>
