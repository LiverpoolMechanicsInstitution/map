<script>
  import Map from "./lib/Map.svelte";
  const currentYear = new Date().getFullYear();
</script>

<p>&copy; {currentYear} Isabel Robinson</p>
<Map />

<style>
  p {
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
