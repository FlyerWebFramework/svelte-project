<script>
  let count = $state(0);
  
  function increment() {
      count += 1;
  }
</script>


<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<br>
<h1 class="text-3xl font-bold underline">
  Hello world!
</h1>
<br>
<article class='prose'>
<h2>Garlic bread with cheese: What the science tells us</h2>
</article>

<button on:click={increment} class='bg-blue-500 w-[200px] h-[50px]'>
  clicks: {count}
</button>
