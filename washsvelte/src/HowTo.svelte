<script>
  let cont = 0;
  function handleClick(cont) {
    return (cont += 1);
  }
</script>

<style>
  img {
    width: 80%;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
  }
</style>

<div bp="grid">

  <img
    bp="offset-5@md 4@md 12@sm"
    src="corona.jpg"
    alt="How to wash your hands." />
  <button on:click={handleClick} />

</div>
