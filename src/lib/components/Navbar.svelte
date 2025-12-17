<script>
	// Navbar
</script>

<div class="sticky top-0 z-50 w-full bg-white">
	<!-- Main Navigation -->
	<nav class="border-b border-gray-200 px-6 py-4">
		<div class="mx-auto flex max-w-[1400px] items-center justify-between">
			<!-- Logo and Left Links -->
			<div class="flex items-center gap-12">
				<a href="/" class="text-xl font-bold tracking-tight text-gray-900">
					Cal Uncommon
				</a>
				
				<div class="hidden items-center gap-8 md:flex">
					{#each ['Products', 'Solutions', 'Resources', 'About'] as item}
						<a href="#" class="flex items-center gap-1 text-[11px] font-semibold tracking-widest text-gray-600 hover:text-gray-900 uppercase">
							{item}
							{#if item === 'Products' || item === 'Solutions' || item === 'Resources'}
								<svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="opacity-50"><path d="m6 9 6 6 6-6"/></svg>
							{/if}
						</a>
					{/each}
				</div>
			</div>

			<!-- Right Actions -->
			<div class="flex items-center gap-6">
				<a href="#" class="text-[11px] font-semibold tracking-widest text-gray-600 hover:text-gray-900 uppercase">
					Advisor Login
				</a>
				<a href="#" class="bg-gray-900 px-4 py-2 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Contact Us
				</a>
			</div>
		</div>
	</nav>
</div>