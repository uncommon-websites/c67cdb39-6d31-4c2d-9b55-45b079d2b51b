<script>
	let openIndex = 0;
	const faqs = [
		{
			question: "Who is Cal Uncommon designed for?",
			answer: "Cal Uncommon serves financial advisors at RIAs who need institutional-grade alternative investments. We work with advisors managing portfolios from $50M to multi-billion dollar firms, providing sophisticated strategies in accessible formats."
		},
		{
			question: "What are the minimum investment requirements?",
			answer: "Minimums vary by product. Our ETFs have no minimums and trade like stocks. Mutual funds typically have $2,500 minimums for retail accounts. Interval funds and separate accounts have higher minimums. Contact us for specific product details."
		},
		{
			question: "How do structured protection strategies work?",
			answer: "Structured protection strategies provide defined outcomes with downside buffers (typically 10-15%) and capped upside participation. They use options overlays to create asymmetric return profiles, protecting against market declines while maintaining growth potential."
		},
		{
			question: "Are Cal Uncommon products available on my platform?",
			answer: "Yes, our products are available on all major platforms including Schwab, Fidelity, TD Ameritrade, Pershing, and through wirehouses like Morgan Stanley, Merrill Lynch, UBS, and Wells Fargo."
		},
		{
			question: "What makes Cal Uncommon's convertible research different?",
			answer: "We have the largest dedicated convertible securities team in the industry with 40+ years of proprietary data. Our integrated capital structure analysis and quantitative screening combined with fundamental research provides unmatched depth."
		},
		{
			question: "Do you provide advisor education and support?",
			answer: "Absolutely. We offer comprehensive education through workshops, webinars, white papers, and dedicated advisor support. Our education-first approach helps RIAs confidently integrate alternatives into client portfolios."
		}
	];
</script>

<section class="py-24">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="grid grid-cols-1 gap-16 lg:grid-cols-12">
			<!-- Left Side -->
			<div class="lg:col-span-4">
				<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[06] FAQ</div>
				<h2 class="mb-6 text-4xl font-medium tracking-tight text-gray-900">Your questions, answered</h2>
				<p class="mb-8 text-lg leading-relaxed text-gray-600">
					We're here to help. Reach out to our team for guidance on integrating alternative investments into your client portfolios.
				</p>
				<a href="#" class="inline-block bg-gray-900 px-6 py-3 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Contact Us
				</a>
			</div>

			<!-- Right Side (Accordion) -->
			<div class="lg:col-span-8">
				<div class="divide-y divide-gray-200 border-t border-b border-gray-200">
					{#each faqs as faq, i}
						<div class="group">
							<button 
								class="flex w-full items-center justify-between py-6 text-left focus:outline-none"
								onclick={() => openIndex = openIndex === i ? -1 : i}
							>
								<span class="text-lg font-medium text-gray-900">{faq.question}</span>
								<span class="ml-4 flex h-6 w-6 items-center justify-center text-gray-400">
									{#if openIndex === i}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6L6 18M6 6l12 12"/></svg>
									{:else}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 5v14M5 12h14"/></svg>
									{/if}
								</span>
							</button>
							{#if openIndex === i}
								<div class="pb-6 text-gray-600 leading-relaxed">
									{faq.answer}
								</div>
							{/if}
						</div>
					{/each}
				</div>
			</div>
		</div>
	</div>
</section>