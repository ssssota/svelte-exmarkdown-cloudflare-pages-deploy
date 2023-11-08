<script lang="ts">
	import Markdown from 'svelte-exmarkdown';
	let md = '# Hello world!';
</script>

<textarea bind:value={md} />
<Markdown {md} />
