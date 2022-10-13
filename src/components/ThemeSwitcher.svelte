<script>
  import sun from "/sun.svg";
  import moon from "/moon.svg";
  import { onMount } from "svelte";

  let currentTheme = "lofi";
  let _localStorage;
  let rootTag;

  onMount(() => {
    _localStorage = localStorage;
    rootTag = window.document.documentElement;
    currentTheme = localStorage.getItem("theme") || "lofi";
    rootTag.setAttribute("data-theme", currentTheme);
  });

  function switchTheme() {
    if (currentTheme === "lofi") {
      currentTheme = "black";
      rootTag.setAttribute("data-theme", "black");
      _localStorage.setItem("theme", "black");
    } else {
      currentTheme = "lofi";
      rootTag.setAttribute("data-theme", "lofi");
      _localStorage.setItem("theme", "lofi");
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
