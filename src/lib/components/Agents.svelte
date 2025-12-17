<section class="py-24 bg-gray-50 border-t border-b border-gray-200">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="mb-12 text-center">
			<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[02] Product Suite</div>
			<h2 class="text-4xl font-medium tracking-tight text-gray-900">Comprehensive alternative investment solutions</h2>
		</div>

		<!-- Diagram Area -->
		<div class="relative mb-16 overflow-hidden rounded-xl bg-[#1a1a1a] p-12 min-h-[500px] flex items-center justify-center">
			<!-- Background Grid -->
			<div class="absolute inset-0 opacity-20" 
				style="background-image: linear-gradient(#ffffff 1px, transparent 1px), linear-gradient(to right, #ffffff 1px, transparent 1px); background-size: 50px 50px;">
			</div>
			
			<div class="relative z-10 w-full max-w-4xl">
				<!-- Central UI -->
				<div class="relative mx-auto max-w-2xl rounded-lg bg-white shadow-2xl overflow-hidden">
					<div class="border-b border-gray-100 bg-gray-50 px-4 py-2 flex justify-between items-center">
						<div class="text-xs font-semibold text-gray-600">Investment Solutions Portfolio</div>
					</div>
					<div class="p-4 space-y-3">
						<!-- List Items -->
						{#each [
							{name: 'Convertible Strategies', type: 'Mutual Funds & ETFs'},
							{name: 'Structured Protection', type: 'Defined Outcome ETFs'},
							{name: 'Alternative Liquid', type: 'Multi-Strategy Funds'},
							{name: 'Private Markets', type: 'Interval Funds'}
						] as product, i}
							<div class="flex items-center justify-between p-3 hover:bg-gray-50 rounded border border-gray-100">
								<div class="flex items-center gap-3">
									<div class="h-8 w-8 rounded bg-gray-900 flex items-center justify-center text-white text-xs font-bold">{product.name.substring(0, 2)}</div>
									<div>
										<div class="text-xs font-bold text-gray-900">{product.name}</div>
										<div class="text-[10px] text-gray-500">{product.type}</div>
									</div>
								</div>
								<div class="text-[10px] text-gray-400 uppercase tracking-widest">Available</div>
							</div>
						{/each}
					</div>
					
					<!-- Info Overlay -->
					<div class="absolute bottom-4 left-4 right-4 rounded-lg bg-white shadow-lg border border-gray-200 p-4">
						<div class="mb-2 text-xs text-gray-500">Accessible through major platforms</div>
						<div class="flex gap-2 flex-wrap">
							<div class="rounded bg-gray-100 px-3 py-1 text-[10px] text-gray-600 font-medium">Schwab</div>
							<div class="rounded bg-gray-100 px-3 py-1 text-[10px] text-gray-600 font-medium">Fidelity</div>
							<div class="rounded bg-gray-100 px-3 py-1 text-[10px] text-gray-600 font-medium">Pershing</div>
							<div class="rounded bg-gray-100 px-3 py-1 text-[10px] text-gray-600 font-medium">+5 More</div>
						</div>
					</div>
				</div>

				<!-- Floating Products -->
				<!-- ETFs -->
				<div class="absolute top-10 -left-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3s;">
					<div class="h-8 w-8 rounded bg-blue-100 flex items-center justify-center text-blue-600 text-xs font-bold">
						ETF
					</div>
					<div>
						<div class="text-xs font-bold text-blue-600">Structured Protection ETFs</div>
						<div class="text-[10px] text-gray-500">Defined outcome strategies</div>
					</div>
				</div>

				<!-- Mutual Funds -->
				<div class="absolute -top-6 right-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 4s;">
					<div class="h-8 w-8 rounded bg-purple-100 flex items-center justify-center text-purple-600 text-xs font-bold">
						MF
					</div>
					<div>
						<div class="text-xs font-bold text-purple-600">Mutual Funds</div>
						<div class="text-[10px] text-gray-500">Convertible & alternatives</div>
					</div>
				</div>

				<!-- Interval Funds -->
				<div class="absolute bottom-20 -right-8 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3.5s;">
					<div class="h-8 w-8 rounded bg-gray-900 flex items-center justify-center text-white text-xs font-bold">
						IF
					</div>
					<div>
						<div class="text-xs font-bold text-gray-900">Interval Funds</div>
						<div class="text-[10px] text-gray-500">Private market access</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Features Grid -->
		<div class="grid grid-cols-1 gap-8 md:grid-cols-3">
			<!-- Col 1 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-gray-100 px-2 py-1 text-[10px] font-bold tracking-widest text-gray-700 uppercase">
					ETFs & Mutual Funds
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Liquid alternative strategies</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Access <strong class="text-gray-900">institutional-grade alternatives</strong> through daily-liquid ETFs and mutual funds. Convertible securities, structured protection, and multi-strategy solutions available on all major platforms.
				</p>
			</div>

			<!-- Col 2 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-gray-100 px-2 py-1 text-[10px] font-bold tracking-widest text-gray-700 uppercase">
					Track Record
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">47 years of proven performance</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					<strong class="text-gray-900">Family-owned since 1977</strong>, Cal Uncommon has navigated multiple market cycles with disciplined risk management. Average portfolio manager tenure exceeds 15 years.
				</p>
			</div>

			<!-- Col 3 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-gray-100 px-2 py-1 text-[10px] font-bold tracking-widest text-gray-700 uppercase">
					Advisor Support
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Education-first approach</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Comprehensive <strong class="text-gray-900">advisor education</strong> through workshops, white papers, and dedicated support. Simplifying alternatives for RIA adoption with institutional-grade resources.
				</p>
			</div>
		</div>
	</div>
</section>