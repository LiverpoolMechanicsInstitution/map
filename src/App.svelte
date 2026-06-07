<script>
  import Map from "./lib/Map.svelte";
  const currentYear = new Date().getFullYear();
</script>

<div id="header">
  <h1>Liverpool Mechanics' School of Arts: Sites of Operation 1825-1905</h1>
</div>
<p>&copy; {currentYear} Isabel Robinson</p>
<Map />

<style>
  #header {
    position: fixed;
    top: 0px;
    left: 50%;
    transform: translate(-50%);
    font-size: 20px;
    padding: 5px 5px;
    background-color: black;
    z-index: 999;
    color: white;
    text-align: center;
    border-radius: 3px;
  }

  h1 {
    margin: 5px;
    font-size: 20px;
  }

  p {
    color: white;
    border-radius: 3px;
    margin: 0;
    padding: 5px 5px;
    background-color: black;
    position: fixed;
    bottom: 0px;
    left: 50%;
    font-weight: 600;
    transform: translateX(-50%);
    z-index: 999;
  }

</style>
