<script>
  import "../app.css";

  import Container from "$lib/components/containers/container.svelte";
  import Footer from "$lib/components/blocks/footer.svelte";
  import Nav from "$lib/components/nav/nav.svelte";

</script>

<div class="flex flex-col h-screen min-h-screen justify-between">
<Container> 
  <Nav />
</Container>
<slot />
<Container>
  <Footer />
</Container>
</div>