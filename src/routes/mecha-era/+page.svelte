<script lang="ts">
	import { base } from '$app/paths';
	let count = 0;
</script>

<div class="h-full my-8 flex justify-center">
	<div class="flex-col px-4 space-y-4">
		<h1 class="h1">Mecha Era!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
		<!-- Go back to home anchor -->
		<a href="{base}/" class="btn variant-filled">
			<b>Home~</b>
		</a>
		<div class="flex justify-start space-x-4">
			<button class="btn variant-ghost" on:click={() => (count += 1)}>
				Clicked {count}
				{count === 1 ? 'time' : 'times'}
			</button>
			<button class="btn variant-ghost" on:click={() => (count = 0)}> Reset </button>
		</div>
	</div>
</div>
