<script lang="ts">
  import Content from "./lib/Content.svelte";
</script>

<header>Project name</header>
<main><Content /></main>
<footer>
  <hr />
  <a href="http://github.com/peruibeloko/template-svelte">Link to source</a>
</footer>

<style>
  header,
  main,
  footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  main {
    flex-grow: 1;
  }

  header,
  footer {
    height: 5rem;
    width: 100%;
  }

  footer hr {
    width: 80%;
    color: var(--bg_s);
  }

  footer a {
    margin-top: 1rem;
    color: var(--aqua_dim);
  }

  footer a:hover {
    color: var(--aqua);
  }

  * {
    background-color: transparent;
    margin: 0;
    padding: 0;
    text-decoration: none;
  }
</style>
