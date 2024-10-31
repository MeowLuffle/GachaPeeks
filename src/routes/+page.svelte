<script lang="ts">
	let count = 0;
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="flex-col justify-center space-y-5">
		<h1 class="h1">Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
		<div class="flex justify-center space-x-5">
			<button class="btn variant-ghost" on:click={() => (count += 1)}>
				Clicked {count}
				{count === 1 ? 'time' : 'times'}
			</button>
			<button class="btn variant-ghost" on:click={() => (count = 0)}> Reset </button>
		</div>
	</div>
</div>
