<script>
  export let name0;
</script>

<svelte:head />

<main>
  <div class="nes-container with-title is-centered">
    <p class="title">Project Eyes Only</p>
    <h1>For Your Eyes Only</h1>
    <p>The official character sheet.</p>

    <div class="container">
      <div class="item nes-field">
        <label for="name_field">Player Name</label>
        <input
          type="text"
          id="name_field"
          class="nes-input"
          placeholder="ChessMaster48"
        />
      </div>
      <div class="item nes-field">
        <label for="name_field">Player Tags</label>
        <input
          type="text"
          id="name_field"
          class="nes-input"
          placeholder="For Campaign: L.O.L Surprise! Version 1"
        />
      </div>
    </div>
  </div>

  <div class="container">
    <div class="nes-container with-title is-centered">
      <p class="title">Basic Character Information</p>
      <div class="container">
        <div class="item nes-field">
          <label for="name_field">First Name</label>
          <input
            type="text"
            id="name_field"
            class="nes-input"
            placeholder="Elizabeth"
          />
        </div>

        <div class="item nes-field">
          <label for="name_field">Last Name</label>
          <input
            type="text"
            id="name_field"
            class="nes-input"
            placeholder="Harmon"
          />
        </div>

        <div class="item nes-field">
          <label for="name_field">Nickname</label>
          <input
            type="text"
            id="name_field"
            class="nes-input"
            placeholder="Beth"
          />
        </div>
      </div>
    </div>
  </div>
</main>

<style>
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
