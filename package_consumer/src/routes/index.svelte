<script lang="ts">
	import { Button as ButtonWorks } from 'package-internal';
	import { Button as ButtonError } from 'package-external';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<ButtonError easy="Bar">Foo</ButtonError>
<ButtonWorks easy="Foo">Foo</ButtonWorks>
