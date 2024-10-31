<script lang="ts">
	import mecha_era_preview from '$lib/assets/mecha_era_card_preview.png';
	let count = 0;
</script>

<div class="h-full my-8 flex justify-center">
	<div class="flex-col px-4 space-y-4">
		<h1 class="h1">Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
		<div class="flex justify-start space-x-4">
			<button class="btn variant-ghost transition ease-in-out delay-100 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-500" on:click={() => (count += 1)}>
				Clicked {count}
				{count === 1 ? 'time' : 'times'}
			</button>
			<button class="btn variant-ghost transition ease-in-out delay-100 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-red-500 duration-500" on:click={() => (count = 0)}> Reset </button>
		</div>
	</div>
</div>

<div class="w-full my-16 flex justify-center">
	<div class="grid sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3 mx-8 gap-4 justify-around">
		<div
			id="mecha-era"
			class="h-48 card p-0 overflow-hidden relative hover:origin-top-left hover:rotate-6 duration-500"
		>
			<header class="card-header bg-white bg-opacity-90 text-black relative z-10">
				<h2 class="flex justify-start">A very cute title for a very cute event~</h2>
			</header>
			<section class="p-0 absolute inset-0">
				<img
					class="object-cover h-full w-full"
					src={mecha_era_preview}
					alt="Mecha Era Card Preview"
				/>
			</section>
			<div class="absolute inset-0 bg-black bg-opacity-50 hover:bg-opacity-0 duration-500"></div>
			<footer class="card-footer text-black relative z-10 p-4 flex content-end justify-end">
				<button class="btn variant-filled">
					<a href="/mecha-era">
						<b>Dive~</b>
					</a>
				</button>
			</footer>
		</div>
		<section class="grid grid-cols-2 md:grid-cols-3 gap-4">
			<div class="flex-col content-start">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
			<div class="flex-col content-center">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1553184570-557b84a3a308?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzY2NTF8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
			<div class="flex-col content-end">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
		</section>
		<section class="grid grid-cols-2 md:grid-cols-3 gap-4">
			<div class="flex-col content-start">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
			<div class="flex-col content-center">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1553184570-557b84a3a308?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzY2NTF8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
			<div class="flex-col content-end">
				<img
					class="h-auto max-w-full rounded-lg"
					src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop"
					alt=""
				/>
			</div>
		</section>
	</div>
</div>
