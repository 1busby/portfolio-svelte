<script>
	import Menu from './Menu.svelte';
	import Projects from './Projects.svelte';
	import About from './About.svelte';
	import Contact from './Contact.svelte';
	import Skills from './Skills.svelte';
</script>

<main>
	<Menu />
	<About />
	<Skills />
	<Projects />
	<Contact />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
</style>