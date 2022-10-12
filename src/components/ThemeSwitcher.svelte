<script>
  import sun from "/sun.svg";
  import moon from "/moon.svg";
  import { onMount } from "svelte";

  let currentTheme = "lofi";
  let rootTag;

  onMount(() => {
    rootTag = window.document.documentElement;
  });

  function switchTheme() {
    if (currentTheme === "lofi") {
      currentTheme = "night";
      rootTag.setAttribute("data-theme", "night");
    } else {
      currentTheme = "lofi";
      rootTag.setAttribute("data-theme", "lofi");
    }
  }
</script>

<button on:click={switchTheme} class="btn btn-circle btn-ghost">
  {#if currentTheme === "lofi"}
    <img src={sun} alt="icone tema claro" />
  {:else}
    <img src={moon} alt="icone tema escuro" />
  {/if}
</button>
