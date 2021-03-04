<script>
  export let name0;
</script>

<svelte:head>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl"
    crossorigin="anonymous"
  />

  <link
    href="https://unpkg.com/nes.css@2.3.0/css/nes.min.css"
    rel="stylesheet"
  />
</svelte:head>

<main>
  <div class="nes-container with-title is-centered">
    <p class="title">Project Eyes Only</p>
    <h1>For Your Eyes Only</h1>
    <p>The official character sheet.</p>
  </div>

  <div class="row">
    <div class="col-sm nes-field">
      <label for="name_field">Player Name</label>
      <input type="text" id="name_field" class="nes-input" />
    </div>

    <div class="col-sm nes-field">
      <label for="name_field">Character Name</label>
      <input type="text" id="name_field" class="nes-input" />
    </div>
  </div>
</main>

<style>
  main {
    display: grid;
    text-align: center;
    padding: 1em;
    /* max-width: 240px; */
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    font-size: 2em;
    /* font-weight: 100; */
  }

  @media (min-width: 640px) {
    main {
      /* max-width: 768px; */
    }
  }
</style>
