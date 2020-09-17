<script>
  import pattern from '../assets/images/pattern-bg.png';
</script>

<style>
  .Header {
    width: 100vw;
    height: 30vh;
    margin: 0;
  }
  /* .Header img {
    width: 100%;
    height: 100%;
  } */

  .Header-nav-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-areas: "top-left top-center top-right"
                          "middle-left center middle-right"
                          "bottom bottom bottom";
    width: 100vw;
    height: 30vh;
  }

  .Header-nav-container h1 {
    justify-self: center;
    align-self: center;    grid-area: top-center;
  }

  .Header-form-container {
    justify-self: center;
    grid-area: center;
  }

  .Data {
    background-color: white;
    border-radius: 8px;
    width: 75vw;
    display: flex;
    justify-self: center;
    justify-content: center;
    grid-area: bottom;
  }

  .Data div {
    padding: 1rem;
    width: 25%;
    box-sizing: border-box;
  }
</style>

<header class="Header">
  <!-- <img src={pattern} alt=""> -->
  <nav class="Header-nav-container">
    <h1>IP Address</h1>
    <form class="Header-form-container" action="">
      <input type="text" />
    </form>
    <section class="Data">
      <div class="IP">
        <p>IP ADRESS</p>
        <h3>00000</h3>
      </div>
      <div class="IP">
        <p>LOCATION</p>
        <h3>00000</h3>
      </div>
      <div class="IP">
        <p>TIMEZONE</p>
        <h3>00000</h3>
      </div>
      <div class="IP">
        <p>ISP</p>
        <h3>00000</h3>
      </div>
    </section>
  </nav>
</header>