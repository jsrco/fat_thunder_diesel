<script>
  import "../app.css";

  import Container from "$lib/components/containers/container.svelte";
  import Nav from "$lib/components/nav/nav.svelte"
</script>

<Container>
  <Nav/>
  <slot />
</Container>
