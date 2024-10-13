<script>
    /** @type {import('./$types').PageData} */
    
    console.log("Received data in +page.svelte:", data);
	export let data
    let people = data.people
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
