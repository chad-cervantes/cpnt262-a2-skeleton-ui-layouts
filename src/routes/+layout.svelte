<script>
	import '../app.postcss';
	import Header from '../lib/components/Header.svelte';
	import Footer from '../lib/components/Footer.svelte';
	import PageFooter from '../lib/components/PageFooter.svelte';
</script>

<Header />
<slot />
<PageFooter />
<Footer />
