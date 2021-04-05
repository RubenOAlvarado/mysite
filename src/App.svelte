<script>
	import Avatar from "./components/Avatar.svelte";
	import Backend from "./components/Backend.svelte";
	import Description from "./components/Description.svelte";
	import Frontend from "./components/Frontend.svelte";
  import Other from "./components/Other.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<main class="nes-container">
  <Avatar />
  <div>
    <Description />
    <Backend />
    <Frontend />
    <Other />
  </div>
  <Footer />
</main>