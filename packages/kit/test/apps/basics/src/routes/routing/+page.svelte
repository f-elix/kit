<script>
	import { page } from '$app/stores';
</script>

<h1>Great success!</h1>

<a href="/routing/a">a</a>
<a href="/routing/ambiguous/ok.json" rel="external">ok</a>
<a href="http://localhost:{$page.url.searchParams.get('port')}">elsewhere</a>
<a href="/static.json">static.json</a>

<a href="/routing/b" data-sveltekit-reload>b</a>

<div class="hydrate-test" />
