<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col">
          <h1>Buttons</h1>
        </div>
      </div>

      <div class="row">
        <div class="col">
          <h3>Bootstrap buttons</h3>
          <p>
          The Bootstrap buttons look as you would expect out of the box.
          The colors can be changed by changing the "theme-colors.scss" file.
          </p>
        </div>
      </div>

      <div class="row">
        <div class="col">
          <button type="button" class="btn btn-primary mr-2 mt-3">Primary</button>
          <button type="button" class="btn btn-secondary mr-2 mt-3">Secondary</button>
          <button type="button" class="btn btn-success mr-2 mt-3">Success</button>
          <button type="button" class="btn btn-danger mr-2 mt-3">Danger</button>
          <button type="button" class="btn btn-warning mr-2 mt-3">Warning</button>
          <button type="button" class="btn btn-info mr-2 mt-3">Info</button>
          <button type="button" class="btn btn-light mr-2 mt-3">Light</button>
          <button type="button" class="btn btn-dark mr-2 mt-3">Dark</button>
          <button type="button" class="btn btn-link mr-2 mt-3">Link</button>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col">
          <h3>Hover Effects</h3>
          <p>
          Additional classes can be applied to the standard buttons to get
          different hover effects. Below are a few examples. The full examples
          can be found at the <a href="http://ianlunn.github.io/Hover/">Hover demo site</a>
          </p>
        </div>
      </div>

      <div class="row">
        <div class="col-3">
          <button class="btn btn-primary hvr-grow">
            Primary
          </button>
          <p>
            Grow
          </p>
        </div>

        <div class="col-3">
          <button class="btn btn-info hvr-sweep-to-right">
            Info
          </button>
          <p>
            Sweep to right
          </p>
        </div>

        <div class="col-3">
          <button class="btn btn-secondary hvr-float-shadow">
            Secondary
          </button>
          <p>
            Float shadow
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

  name: 'demo',
  components: {
  },
};
</script>
